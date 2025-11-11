# 📋 Guía Completa: Laboratorio 4 - Gestión Básica de Red

## 1\. Objetivo

[cite\_start]Implementar el monitoreo SNMP en una red empresarial simulada que presta servicios, utilizando routers Cisco y un servidor Issabel, gestionado por el software PRTG[cite: 4].

## 2\. Topología de Red

[cite\_start]Esta es la topología objetivo de la práctica[cite: 31].

## 3\. Paso a Paso: Configuración de la Infraestructura

### Paso 3.1: Configuración de Routers (Interfaces y Enrutamiento)

[cite\_start]Implementa la red de la Figura 1[cite: 6]. [cite\_start]La configuración base para cada router incluye la configuración de sus interfaces y el enrutamiento con **RIPv2**[cite: 35].

A continuación, se muestra la configuración limpia y funcional para cada uno de los 4 routers.

-----

#### 📍 Router R1 (Central)

```bash
enable
configure terminal

! Configurar interfaces
hostname R1

! Conexión a PC3
interface GigabitEthernet0/0
 [cite_start]ip address 192.168.255.1 255.255.255.0 [cite: 11]
 no shutdown
 exit

! Conexión a R2
interface Serial0/0/0
 [cite_start]ip address 10.0.0.1 255.255.255.252 [cite: 12]
 no shutdown
 exit

! Conexión a R3
interface Serial0/0/1
 [cite_start]ip address 20.0.0.1 255.255.255.252 [cite: 13]
 no shutdown
 exit

! Configurar Enrutamiento RIPv2
router rip
 [cite_start]version 2 [cite: 35]
 network 192.168.255.0
 network 10.0.0.0
 network 20.0.0.0
 no auto-summary
 exit

! Guardar configuración
end
[cite_start]write memory [cite: 36]
```

-----

#### 📍 Router R2 (Izquierda)

*(Esta es la configuración que estabas realizando en tu consola, organizada y limpia)*.

```bash
enable
configure terminal

! Configurar interfaces
hostname R2

! Conexión a SW2/R4
interface GigabitEthernet0/0
 [cite_start]ip address 40.0.0.1 255.255.255.0 [cite: 19]
 no shutdown
 exit

! Conexión a R1
interface Serial0/0/0
 [cite_start]ip address 10.0.0.2 255.255.255.252 [cite: 16]
 no shutdown
 exit

! Configurar Enrutamiento RIPv2
router rip
 [cite_start]version 2 [cite: 35]
 network 40.0.0.0
 network 10.0.0.0
 no auto-summary
 exit

! Guardar configuración
end
[cite_start]write memory [cite: 36]
```

-----

#### 📍 Router R3 (Derecha)

```bash
enable
configure terminal

! Configurar interfaces
hostname R3

! Conexión a SW3
interface GigabitEthernet0/0
 [cite_start]ip address 30.0.0.1 255.255.255.0 [cite: 20]
 no shutdown
 exit

! Conexión a R1 (IP corregida de 20.0.0.230 a 20.0.0.2)
interface Serial0/0/0
 [cite_start]ip address 20.0.0.2 255.255.255.252 [cite: 15]
 no shutdown
 exit

! Configurar Enrutamiento RIPv2
router rip
 [cite_start]version 2 [cite: 35]
 network 30.0.0.0
 network 20.0.0.0
 no auto-summary
 exit

! Guardar configuración
end
[cite_start]write memory [cite: 36]
```

-----

#### 📍 Router R4 (Abajo)

```bash
enable
configure terminal

! Configurar interfaces
hostname R4

! Conexión a SW2/R2
interface GigabitEthernet0/0
 [cite_start]ip address 40.0.0.2 255.255.255.0 [cite: 27]
 no shutdown
 exit

! Conexión a SW4
interface GigabitEthernet0/1
 [cite_start]ip address 50.0.0.1 255.255.255.0 [cite: 29]
 no shutdown
 exit

! Configurar Enrutamiento RIPv2
router rip
 [cite_start]version 2 [cite: 35]
 network 40.0.0.0
 network 50.0.0.0
 no auto-summary
 exit

! Guardar configuración
end
[cite_start]write memory [cite: 36]
```

-----

### Paso 3.2: Configuración de DHCP en Routers

[cite\_start]En cada router que sirva a una LAN (R1, R2, R3, R4), configura un pool de DHCP[cite: 37].

**Ejemplo para R2 (Red 40.0.0.0):**

```bash
configure terminal

! Excluir la IP del router para que no sea asignada
ip dhcp excluded-address 40.0.0.1

! Crear el pool de DHCP
ip dhcp pool LAN_40
 [cite_start]network 40.0.0.0 255.255.255.0 [cite: 40]
 [cite_start]default-router 40.0.0.1 [cite: 41]
 [cite_start]domain-name redes2.poli.edu [cite: 41]
 exit

end
[cite_start]write memory [cite: 42]
```

> **Acción:** Repite esta configuración en R1 (para la red `192.168.255.0`), R3 (para `30.0.0.0`) y R4 (para `50.0.0.0`), ajustando las direcciones IP correspondientes.

### Paso 3.3: Configuración de SNMP en Routers

[cite\_start]Para permitir que PRTG monitoree los routers, debes habilitar SNMP con una comunidad de solo lectura (RO)[cite: 43].

**Comando (ejecutar en R1, R2, R3 y R4):**

```bash
configure terminal
[cite_start]snmp-server community ELPOLI RO [cite: 44]
end
write memory
```

-----

### Paso 3.4: Instalación del Servidor Issabel y SNMP

1.  **Instalación del SO:**

      * [cite\_start]Crea una máquina virtual (VM) para Issabel con las especificaciones: 1 Vcore, 4GB RAM y 10G de almacenamiento[cite: 63].
      * [cite\_start]Instala Issabel (basado en CentOS 7.5)[cite: 63].
      * Asígnale una **dirección IP estática** que pertenezca a una de tus LAN (por ejemplo, `40.0.0.5` si está conectado a SW2).

2.  **Configuración de SNMP en Issabel (CentOS):**

      * [cite\_start]Conéctate a la consola de tu servidor Issabel y obtén privilegios de root[cite: 69].

    <!-- end list -->

    ```bash
    sudo -i
    ```

      * [cite\_start]Instala los paquetes de SNMP[cite: 74]:

    <!-- end list -->

    ```bash
    yum -y install net-snmp net-snmp-utils
    ```

      * [cite\_start]Crea un backup de la configuración original[cite: 76]:

    <!-- end list -->

    ```bash
    mv /etc/snmp/snmpd.conf /etc/snmp/snmpd.conf.original
    ```

      * [cite\_start]Crea y edita el nuevo archivo de configuración[cite: 79]:

    <!-- end list -->

    ```bash
    vim /etc/snmp/snmpd.conf
    ```

      * [cite\_start]Presiona `i` para insertar y pega el siguiente texto[cite: 80]. **Importante:** Reemplaza `<Dir ip del equipos donde está el PRTG>` con la IP estática de tu máquina Windows 10.

    <!-- end list -->

    ```text
    [cite_start]rocommunity private ELPOLI <Dir ip del equipos donde está el PRTG> [cite: 81]
    [cite_start]rocommunity private ELPOLI 127.0.0.1 [cite: 82]
    [cite_start]rocommunity public 127.0.0.1 [cite: 83]
    [cite_start]syslocation "DATACENTER PARA ISSABEL4" [cite: 84]
    [cite_start]syscontact redes2.poli.edu.co [cite: 85]
    ```

      * [cite\_start]Presiona `Esc` y luego escribe `:wq` y presiona `Enter` para guardar y salir[cite: 86].
      * [cite\_start]Inicia el servicio de SNMP[cite: 88]:

    <!-- end list -->

    ```bash
    service snmpd start
    ```

      * [cite\_start]Habilita el servicio para que inicie automáticamente con el sistema[cite: 92]:

    <!-- end list -->

    ```bash
    chkconfig snmpd on
    ```

      * [cite\_start]Verifica que funcione localmente[cite: 97]:

    <!-- end list -->

    ```bash
    snmpwalk -v 2c -c public 127.0.0.1 | more
    ```

      * [cite\_start]*Deberías ver la información de `syslocation` y `syscontact` que acabas de configurar[cite: 98].*

-----

### Paso 3.5: Instalación y Configuración de PRTG

1.  **Instalación:**

      * [cite\_start]Prepara una máquina virtual con **Windows 10**[cite: 45].
      * [cite\_start]Asígnale una **dirección IP estática** que esté en la misma red que tu servidor Issabel o en otra LAN (ej. `192.168.255.10` si está en la LAN de R1)[cite: 46].
      * [cite\_start]Descarga e instala PRTG Network Monitor desde el sitio de Paessler[cite: 60]. [cite\_start]Sigue las instrucciones del video "Cómo instalar PRTG en 2 minutos"[cite: 58, 59].

2.  **Configuración de Monitoreo:**

      * Abre la interfaz web de PRTG.
      * **Añadir Routers:**
          * Ve a "Dispositivos" \> "Añadir Dispositivo".
          * Introduce la IP de tu primer router (ej. R1: `192.168.255.1` o `10.0.0.1`).
          * En la sección "Credenciales para SNMP", desmarca la herencia e introduce `ELPOLI` como la "Comunidad String".
          * Haz clic en "OK". PRTG comenzará a escanearlo.
          * [cite\_start]**Repite este proceso** para R2, R3 y R4[cite: 131].
      * **Añadir Servidor Issabel:**
          * Añade otro dispositivo. [cite\_start]Introduce la IP estática de tu servidor Issabel (ej. `40.0.0.5`)[cite: 132].
          * En la sección SNMP, introduce `ELPOLI` como comunidad.
      * **Añadir Sensores:**
          * Haz clic en uno de tus routers (ej. R2).
          * Haz clic en "Añadir Sensor".
          * Busca un sensor de tipo **"SNMP Traffic"**.
          * [cite\_start]Selecciona las interfaces que deseas monitorear (ej. `GigabitEthernet0/0` y `Serial0/0/0`)[cite: 130].
          * Haz clic en "Crear".
          * **Repite** para los sensores que quieras ver (CPU, Ping, etc.) en todos los dispositivos.

-----
