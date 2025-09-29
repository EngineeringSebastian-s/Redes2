# Informe de acciones en el laboratorio uno

## Router Uno:

1. **Borrado de configuración previa**

    * Se intentó varias veces ejecutar `erase restart` (comando inválido).
    * Finalmente se logró ejecutar `erase startup-config`, lo que eliminó la configuración guardada en NVRAM y reinició el router.

2. **Configuración inicial (Setup Dialog)**

    * Se asignó el hostname `test`.
    * Se configuraron contraseñas (enable secret, enable password, VTY).
    * Se habilitó SNMP.
    * Se configuró la interfaz **GigabitEthernet0/1** con la IP `192.168.0.2/24`.

3. **Reinicio y nueva configuración**

    * El router tomó el hostname `R1`.
    * Se creó un usuario local `cisco` con privilegio 15 y contraseña `cisco`.
    * Se activó `login local` en consola y VTY, permitiendo acceso con usuario/contraseña.
    * Se habilitó Telnet (`transport input telnet`).

4. **Configuración de interfaces**

    * **GigabitEthernet0/0**: `192.168.255.1/24`, estado UP.
    * **Serial0/0/0**: `20.0.0.1/30`, encapsulación PPP, estado UP.
    * **Serial0/0/1**: `10.0.0.1/30`, encapsulación PPP, estado UP.
    * **Loopback0**: `1.1.1.1/32`.

5. **Protocolos de enrutamiento**

    * Se configuró **RIP v2** con redes `10.0.0.0`, `20.0.0.0`, `192.168.255.0`.
    * Luego se habilitó **OSPF** (process ID 1000) con las redes anteriores (área 0 y 2).
    * También se configuró **EIGRP 20**, aunque parece que se superponía con OSPF/RIP.

6. **Pruebas de conectividad**

    * Se hicieron múltiples pings:

        * `192.168.255.1` → exitoso.
        * `20.0.0.1` → exitoso.
        * `10.0.0.2` → al inicio fallaba, luego quedó activo.
        * Se detectaron rutas vía RIP hacia `30.0.0.0`.
        * Se agregaron rutas OSPF hacia `30.0.0.0`.
        * También aparecieron rutas RIP hacia `40.0.0.0` y `50.0.0.0`.

7. **Observaciones finales**

    * El router quedó con varias configuraciones de enrutamiento (RIP, OSPF y EIGRP coexistiendo).
    * Se presentaron errores de sintaxis al escribir comandos (`ban`, `ex`, etc.), pero se corrigieron.
    * La última configuración estable muestra al router **R1** con interfaces activas, usuario local y protocolos de enrutamiento funcionando.
