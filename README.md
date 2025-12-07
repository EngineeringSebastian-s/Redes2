# Portafolio de Gestión de Redes y Servicios (Redes II)

Este repositorio documenta las prácticas de laboratorio realizadas en la asignatura de **Gestión de Redes**, enfocadas en la configuración, administración y monitoreo de infraestructura de red utilizando **hardware real Cisco** (Routers Serie 1900/2900) mediante conexión serial.

**Autor:** Sebastián López Osorno
**Institución:** Politécnico Colombiano Jaime Isaza Cadavid
**Enfoque:** Infraestructura física, Enrutamiento Avanzado y Gestión SNMP.

-----

## 🛠️ Metodología y Equipamiento

A diferencia de entornos simulados, este proyecto se desarrolló interactuando directamente con la **NVRAM** y las interfaces físicas de los dispositivos.

  * **Hardware:** Routers Cisco ISR (Series 1941/2901), Switches Catalyst, PCs y Servidores Linux/Windows.
  * **Conectividad:** Cable de consola (Rollover) RS-232/USB, Serial (V.35) para WAN y GigabitEthernet para LAN.
  * **Herramientas de Gestión:** Putty/TeraTerm (CLI), Wireshark (Análisis de tráfico), PRTG (Monitoreo), Issabel (VoIP).

-----

## 📂 Módulos del Laboratorio

[Image of cisco router network topology diagram with management server]

### 1\. Fundamentos de IOS y Enrutamiento Dinámico

Ubicación: `/Laboratorio1`

  * **Objetivo:** Recuperación de desastres y configuración base de una red WAN.
  * **Actividades Clave:**
      * **Hard Reset:** Borrado de `startup-config` y configuración inicial vía *System Configuration Dialog*.
      * **Seguridad:** Configuración de usuarios locales (privilegio 15), acceso VTY (Telnet) y encriptación de contraseñas.
      * **Enrutamiento Híbrido:** Implementación coexistente de **RIPv2**, **OSPF** (Área 0 y 2) y **EIGRP** en el mismo dispositivo para pruebas de distancia administrativa.
  * **Evidencia:** Logs de consola de `R1` mostrando la convergencia de rutas.

### 2\. IPv6 y Servicios de Red

Ubicación: `/Laboratorio2`

  * **Objetivo:** Implementación de pila dual (Dual Stack) y servicios de autoconfiguración.
  * **Actividades Clave:**
      * **IPv6:** Asignación de direcciones globales (`ABCD::/64`) y enlace local.
      * **DHCPv6:** Configuración del router como servidor DHCP *Stateful* para la entrega de IPs y DNS a clientes Windows.
      * **EIGRPv6:** Configuración de enrutamiento dinámico para IPv6 (AS 32000).
      * **Análisis de Tráfico:** Captura de paquetes `.pcapng` demostrando el handshake de Telnet y anuncios de router (RA).

### 3\. Gestión de Red y Monitoreo (NMS)

Ubicación: `/Laboratorio4`

  * **Objetivo:** Implementación de un sistema de gestión centralizado para una topología compleja de 4 routers.
  * **Arquitectura:**
      * **NMS (Network Management System):** PRTG Network Monitor sobre Windows 10.
      * **Servicios:** Servidor Issabel (CentOS) para VoIP y pruebas de servicio.
      * **Protocolo:** Configuración de agentes **SNMP** (Comunidad `ELPOLI`) en todos los routers para lectura remota de métricas (Tráfico, CPU, Estado de interfaces).
  * **Topología:** Diseño de red en malla parcial con enrutamiento RIPv2 y pools DHCP distribuidos por segmento.

-----

## 📝 Registro de Logs (Troubleshooting)

Este repositorio incluye los **logs crudos** de las sesiones de consola. Estos archivos son una evidencia verídica del proceso de configuración, incluyendo:

1.  **Errores de Sintaxis y Corrección:** Intentos de comandos fallidos y su resolución en tiempo real.
2.  **Mensajes de Sistema (Syslog):** Notificaciones de `LINK-3-UPDOWN` y `OSPF-5-ADJCHG`.
3.  **Verificación:** Salidas de `show ip route`, `show run` y `debug`.

Puedes encontrar estos registros en las carpetas `logs/commands/` de cada laboratorio.

-----

## 🚀 Guía de Navegación

Para ver el detalle técnico de cada práctica, navega a los README individuales:

  * [📘 Ver Laboratorio 1 (Setup & Routing)](https://www.google.com/search?q=./Laboratorio1/README.md)
  * [📗 Ver Laboratorio 2 (IPv6 & Sniffing)](https://www.google.com/search?q=./Laboratorio2/README.md)
  * [📙 Ver Laboratorio 4 (Gestión SNMP & PRTG)](https://www.google.com/search?q=./Laboratorio4/README.md)


Al igual que en los otros proyectos, dado que aquí tienes archivos `.pcapng` (capturas de Wireshark) que son binarios y pueden ser pesados, y logs que a veces generan archivos temporales, te recomendaría generar un `.gitignore` específico para redes (ignorando temporales de editores, archivos de bloqueo de Wireshark, etc.).

**¿Quieres que genere ese archivo `.gitignore` para limpiar el repo?**
