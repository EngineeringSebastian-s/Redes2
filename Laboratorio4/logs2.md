Cisco CISCO1941/K9 (revision 1.0) with 487424K/36864K bytes of memory.
Processor board ID FJC2052L0PP
2 Gigabit Ethernet interfaces
2 Serial(sync/async) interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)

SETUP: new interface Serial0/0/0 placed in "shutdown" state
SETUP: new interface Serial0/0/1 placed in "shutdown" state


Press RETURN to get started!


*Jan  2 00:00:02.179: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Nov 24 23:14:11.615: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Nov 24 23:14:22.555: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Nov 24 23:14:28.183: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Nov 24 23:14:28.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to d
R4>
R4>
R4>
R4>
R4>
R4>
R4>own
*Nov 24 23:14:28.187: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Nov 24 23:14:28.187: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Nov 24 23:14:29.287: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Nov 24 23:14:29.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 24 23:14:29.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up
*Nov 24 23:14:29.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Nov 24 23:14:30.455: %SYS-5-CONFIG_I: Configured from memory by console
*Nov 24 23:14:31.211: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
*Nov 24 23:14:31.215: %SNMP-5-COLDSTART: SNMP agent on host R4 is undergoing a cold start
*Nov 24 23:14:32.403: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Nov 24 23:14:32.455: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Nov 24 23:14:32.523: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Nov 24 23:14:33.403: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Nov 24 23:14:33.455: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
R4>
R4>erase startup-config
    ^
% Invalid input detected at '^' marker.

R4>enable
R4#erase star
R4#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
R4#
*Nov 24 23:18:09.587: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram▒
System Bootstrap, Version 15.0(1r)M16, RELEASE SOFTWARE (fc1)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 2012 by cisco Systems, Inc.

Total memory size = 512 MB - On-board = 512 MB, DIMM0 = 0 MB
CISCO1941/K9 platform with 524288 Kbytes of main memory
Main memory is configured to 64/-1(On-board/DIMM0) bit mode with ECC disabled


Readonly ROMMON initialized
program load complete, entry point: 0x80803000, size: 0x1b340
program load complete, entry point: 0x80803000, size: 0x1b340


IOS Image Load Test
___________________
Digitally Signed Release Software
program load complete, entry point: 0x81000000, size: 0x481ac1c
Self decompressing the image : ######################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################### [OK]

Smart Init is enabled
smart init is sizing iomem
                 TYPE      MEMORY_REQ
          HWIC Slot 0      0x00200000
    Onboard devices &
         buffer pools      0x01E8F000
-----------------------------------------------
               TOTAL:      0x0208F000

Rounded IOMEM up to: 36MB.
Using 7 percent iomem. [36MB/512MB]

              Restricted Rights Legend

Use, duplication, or disclosure by the Government is
subject to restrictions as set forth in subparagraph
(c) of the Commercial Computer Software - Restricted
Rights clause at FAR sec. 52.227-19 and subparagraph
(c) (1) (ii) of the Rights in Technical Data and Computer
Software clause at DFARS sec. 252.227-7013.

           cisco Systems, Inc.
           170 West Tasman Drive
           San Jose, California 95134-1706



Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team


This product contains cryptographic features and is subject to United
States and local country laws governing import, export, transfer and
use. Delivery of Cisco cryptographic products does not imply
third-party authority to import, export, distribute or use encryption.
Importers, exporters, distributors and users are responsible for
compliance with U.S. and local country laws. By using this product you
agree to comply with applicable laws and regulations. If you are unable
to comply with U.S. and local laws, return this product immediately.

A summary of U.S. laws governing Cisco cryptographic products may be found at:
http://www.cisco.com/wwl/export/crypto/tool/stqrg.html

If you require further assistance please contact us by sending email to
export@cisco.com.

Cisco CISCO1941/K9 (revision 1.0) with 487424K/36864K bytes of memory.
Processor board ID FJC2052L0PP
2 Gigabit Ethernet interfaces
2 Serial(sync/async) interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)


         --- System Configuration Dialog ---

Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
%Error opening tftp://255.255.255.255/network-confg (Timed out)
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]: no

Would you like to terminate autoinstall? [yes]: yes
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)


Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Nov 24 23:21:56.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Nov 24 23:22:07.559: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Nov 24 23:22:13.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Nov 24 23:22:13.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to d
Router>
%Error opening tftp://255.255.255.255/cisconet.cfg (Timed out)own
*Nov 24 23:22:13.187: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Nov 24 23:22:13.191: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Nov 24 23:22:14.295: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Nov 24 23:22:14.295: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 24 23:22:14.295: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up
*Nov 24 23:22:14.295: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Nov 24 23:22:37.771: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Nov 24 23:22:42.151: AUTOINSTALL: GigabitEthernet0/0 is assigned 50.0.0.2
*Nov 24 23:23:22.235: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up
*Nov 24 23:23:36.331: %PNP-6-HTTP_CONNECTING: PnP Discovery trying to connect to PnP server http://pnpserver.redes2.poli.edu/pnp/HELLO
*Nov 24 23:23:41.315: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Nov 24 23:23:43.131: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Nov 24 23:23:43.131: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Nov 24 23:23:43.131: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Nov 24 23:23:43.131: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Nov 24 23:23:44.131: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Nov 24 23:23:45.099: %IP-5-WEBINST_KILL: Terminating DNS process
*Nov 24 23:23:54.539: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team

Router>hostname
%Error opening tftp://255.255.255.255/router-confg (T
Router>hostname R3
        ^
% Invalid input detected at '^' marker.

Router>enable
Router#host
*Nov 24 23:25:11.711: %PNP-6-HTTP_CONNECTING: PnP Discovery trying to connect to PnP server http://pnpserver.redes2.p                                                                                                                        oli.edu/pnp/H
Router#hostname R3
        ^
% Invalid input detected at '^' marker.

Router#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#hostname R3
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:25:37.887: %SYS-5-CONFIG_I: Configured from console by console
%Error opening tftp://255.255.255.255/ciscortr.cfg (Timed out)[OK]
R3#
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)
R3#
username cisco privilege 15 password cisco
    ^
% Invalid input detected at '^' marker.

R3#username cisco privilege 15 password cisco
%Error opening tftp://255.255.255.255/network-confg (Timed out)
    ^
% Invalid input detected at '^' marker.

R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#username cisco privilege 15 password cisco
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:26:43.135: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#
%Error opening tftp://255.255.255.255/cisconet.cfg (Timed out)
%Error opening tftp://255.255.255.255/R3-confg (Timed out)
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)
%Error opening tftp://255.255.255.255/R3-confg (Timed out)

Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)

R3#
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)
R3#
enable
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface g0/0
R3(config-if)#no shut
R3(config-if)#band
R3(config-if)#bandwidth 1000
R3(config-if)#ip add
R3(config-if)#ip address 40.0.0.3 255.255.255.0
R3(config-if)#exit
R3(config)#wr
% Incomplete command.

R3(config)#exti
             ^
% Invalid input detected at '^' marker.

R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:32:26.171: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface s0/0/0
R3(config-if)#enca
R3(config-if)#encap ppp
R3(config-if)#ban
R3(config-if)#ban
R3(config-if)#ban
R3(config-if)#bandwidth 64
R3(config-if)#ip add
R3(config-if)#ip address 10.0.0.2 255.255.255
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255).252
R3(config-if)#ip address 10.0.0.2 255.255.255.252

R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:34:25.155: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface s0/0/0
R3(config-if)#no shut
R3(config-if)#exit
R3(config)#
*Nov 24 23:35:03.263: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to upex
*Nov 24 23:35:03.283: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:35:07.255: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#show run
Building configuration...

Current configuration : 1297 bytes
!
! Last configuration change at 23:35:07 UTC Mon Nov 24 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.3 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login
 transport input none
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3#
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)
R3#inter
% Incomplete command.

R3#interface g0/0
    ^
% Invalid input detected at '^' marker.

R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface g0/0
R3(config-if)#ip add
R3(config-if)#ip address 40.0.0.1 255.255.255.0
R3(config-if)#no shutdown
R3(config-if)#exit
R3(config)#interface s0/0/0
R3(config-if)#ip add
R3(config-if)#ip address 10.0.0.2 255.255.255.252
R3(config-if)#exit
R3(config)#wr
% Incomplete command.

R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:41:46.999: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#show run
Building configuration...

Current configuration : 1297 bytes
!
! Last configuration change at 23:41:46 UTC Mon Nov 24 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login
 transport input none
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES unset  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES unset  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    up
Serial0/0/1                unassigned      YES unset  administratively down down
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interfac g0/1
R3(config-if)#no shut
R3(config-if)#ip add
R3(config-if)#ip address 60
*Nov 24 23:45:02.195: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed .0.0
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255).1^Z              ^
% Invalid input detected at '^' marker.

R3#
*Nov 24 23:45:14.575: %SYS-5-CONFIG_I: Configured from console by console

R3#conft t
       ^
% Invalid input detected at '^' marker.

R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface g0/1
R3(config-if)#no shut
R3(config-if)#ip add
R3(config-if)#ip address 60.0.0.1 255.255.255.0
R3(config-if)#band
R3(config-if)#bandwidth 1000
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:46:06.455: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#
R3#
R3#show run
Building configuration...

Current configuration : 1323 bytes
!
! Last configuration change at 23:46:06 UTC Mon Nov 24 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 bandwidth 1000
 ip address 60.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login
 transport input none
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3# conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#line vty 0 4
R3(config-line)#login local
R3(config-line)#transport input telnet
R3(config-line)#exit
R3(config)#eixt
            ^
% Invalid input detected at '^' marker.

R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:49:41.859: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#router rip
R3(config-router)#version 2
R3(config-router)#network 10.0.0.0
R3(config-router)#network 40.0.0.0
R3(config-router)#no ait
R3(config-router)#no aut
R3(config-router)#no auto-summary
R3(config-router)#exit
R3(config)#exit
R3#w
*Nov 24 23:50:25.595: %SYS-5-CONFIG_I: Configured from console by consoler
Building configuration...
[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface loo
R3(config)#interface loopback0
R3(config-if)#op
*Nov 24 23:50:58.467: %LINEPROTO-5-UPDOWN: Line protocol on Interface Loopback0, changed state to
R3(config-if)#ip add
R3(config-if)#ip address 3.3.3.3 255.255.255.255
R3(config-if)#exit
R3(config)#router ospf 1000
R3(config-router)#log
R3(config-router)#log-adjacency-changes
R3(config-router)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:51:25.627: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#router opsf 1000
                   ^
% Invalid input detected at '^' marker.

R3(config)#router ospf 1000
R3(config-router)#log
R3(config-router)#log-adjacency-changes
R3(config-router)#net
R3(config-router)#network 10.0.
Translating "pnpntpserver.redes2.poli.edu"...domain server (255
R3(config-router)#network 10.0.0
R3(config-router)#network 10.0.0.0 0.0.0.3 area 0
R3(config-router)#network 40.0.0.0 0.0.0.255 area 1
R3(config-router)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:52:51.547: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#ip dhcp pool LAN40
R3(dhcp-config)#network 40.0.0.0 255.255.255.0
R3(dhcp-config)#defult
                   ^
% Invalid input detected at '^' marker.

R3(dhcp-config)#de
R3(dhcp-config)#default-router 40.0.0.1
R3(dhcp-config)#doma
R3(dhcp-config)#domain-name redes2.poli.edu
R3(dhcp-config)#exit
R3(config)#eit
            ^
% Invalid input detected at '^' marker.

R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:53:58.259: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#ip dhcp pool LAN60
           ^
% Invalid input detected at '^' marker.

R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#ip dhcp pool LAN60
R3(dhcp-config)#net
R3(dhcp-config)#networ
R3(dhcp-config)#network 60.0.0.0 255.255.255.0
R3(dhcp-config)#defau
R3(dhcp-config)#default-router 60.0.0.1
R3(dhcp-config)#exit
R3(config)#exit
R3#
*Nov 24 23:54:55.047: %SYS-5-CONFIG_I: Configured from console by consolewr
Building configuration...
[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#snm
R3(config)#snmp-s
R3(config)#snmp-server comm
R3(config)#snmp-server community ELPOLI
R3(config)#snmp-server community ELPOLI RO
R3(config)#ip d
R3(config)#ip dhc
R3(config)#ip dhcp pool LAN40
R3(dhcp-config)#ip dhc
R3(dhcp-config)#ip dhcp excluded
R3(dhcp-config)#ip dhcp excluded-a
R3(dhcp-config)#exit
R3(config)#ip dhcp ex
R3(config)#ip dhcp excluded-address 40.0.0.1
R3(config)#ip dhcp excluded-address 40.0.0.6
R3(config)#ip dhcp excluded-address 40.0.0.5
R3(config)#ip dhcp excluded-address 40.0.0.7
R3(config)#no shut
% Incomplete command.

R3(config)#interface s0/0/0
R3(config-if)#no shut
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:57:54.183: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#ip d
R3(config)#ip dhcp pool LAN60
R3(dhcp-config)#domain
R3(dhcp-config)#domain-name redes2.poli.edu
R3(dhcp-config)#exit
R3(config)#ip dhcp
R3(config)#ip dhcp excl
R3(config)#ip dhcp excluded-address 60.0.0.5
R3(config)#ip dhcp excluded-address 60.0.0.6
R3(config)#exit
R3#wr
Building configuration...

*Nov 24 23:59:11.831: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#
R3#show run
Building configuration...

Current configuration : 2005 bytes
!
! Last configuration change at 23:59:11 UTC Mon Nov 24 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
ip dhcp excluded-address 40.0.0.1
ip dhcp excluded-address 40.0.0.6
ip dhcp excluded-address 40.0.0.5
ip dhcp excluded-address 40.0.0.7
ip dhcp excluded-address 60.0.0.5
ip dhcp excluded-address 60.0.0.6
!
ip dhcp pool LAN40
 network 40.0.0.0 255.255.255.0
 default-router 40.0.0.1
 domain-name redes2.poli.edu
!
ip dhcp pool LAN60
 network 60.0.0.0 255.255.255.0
 default-router 60.0.0.1
 domain-name redes2.poli.edu
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
interface Loopback0
 --More--
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)                                ip addres                                                                                                                        s 3.3.3.3 255.255.255.255
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 bandwidth 1000
 ip address 60.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
router ospf 1000
 network 10.0.0.0 0.0.0.3 area 0
 network 40.0.0.0 0.0.0.255 area 1
!
router rip
 version 2
 network 10.0.0.0
 network 40.0.0.0
 no auto-summary
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
snmp-server community ELPOLI RO
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login local
 transport input telnet
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#router rip
R3(config-router)#network 60.0.0.0
R3(config-router)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 25 00:03:42.327: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#ip dhcp exc
R3(config)#ip dhcp excluded-address 60.0.0.1
R3(config)#exit
R3#wr
Building configuration...

*Nov 25 00:04:18.295: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#show run
Building configuration...

Current configuration : 2057 bytes
!
! Last configuration change at 00:04:18 UTC Tue Nov 25 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
ip dhcp excluded-address 40.0.0.1
ip dhcp excluded-address 40.0.0.6
ip dhcp excluded-address 40.0.0.5
ip dhcp excluded-address 40.0.0.7
ip dhcp excluded-address 60.0.0.5
ip dhcp excluded-address 60.0.0.6
ip dhcp excluded-address 60.0.0.1
!
ip dhcp pool LAN40
 network 40.0.0.0 255.255.255.0
 default-router 40.0.0.1
 domain-name redes2.poli.edu
!
ip dhcp pool LAN60
 network 60.0.0.0 255.255.255.0
 default-router 60.0.0.1
 domain-name redes2.poli.edu
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
 --More--
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)                               interface                                                                                                                         Loopback0
 ip address 3.3.3.3 255.255.255.255
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 bandwidth 1000
 ip address 60.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
router ospf 1000
 network 10.0.0.0 0.0.0.3 area 0
 network 40.0.0.0 0.0.0.255 area 1
!
router rip
 version 2
 network 10.0.0.0
 network 40.0.0.0
 network 60.0.0.0
 no auto-summary
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
snmp-server community ELPOLI RO
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login local
 transport input telnet
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3#show run
Building configuration...

Current configuration : 2057 bytes
!
! Last configuration change at 00:04:18 UTC Tue Nov 25 2025
!
version 15.4
service config
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
!
hostname R3
!
boot-start-marker
boot-end-marker
!
!
!
no aaa new-model
!
!
!
!
!
!
!
!
!
!
!
ip dhcp excluded-address 40.0.0.1
ip dhcp excluded-address 40.0.0.6
ip dhcp excluded-address 40.0.0.5
ip dhcp excluded-address 40.0.0.7
ip dhcp excluded-address 60.0.0.5
ip dhcp excluded-address 60.0.0.6
ip dhcp excluded-address 60.0.0.1
!
ip dhcp pool LAN40
 network 40.0.0.0 255.255.255.0
 default-router 40.0.0.1
 domain-name redes2.poli.edu
!
ip dhcp pool LAN60
 network 60.0.0.0 255.255.255.0
 default-router 60.0.0.1
 domain-name redes2.poli.edu
!
!
!
ip cef
no ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PP
!
!
username cisco privilege 15 password 0 cisco
!
redundancy
!
!
!
!
!
!
interface Loopback0
 ip address 3.3.3.3 255.255.255.255
!
interface Embedded-Service-Engine0/0
 no ip address
 shutdown
!
interface GigabitEthernet0/0
 bandwidth 1000
 ip address 40.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 bandwidth 1000
 ip address 60.0.0.1 255.255.255.0
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 ip address 10.0.0.2 255.255.255.252
 encapsulation ppp
!
interface Serial0/0/1
 no ip address
 shutdown
 clock rate 2000000
!
router ospf 1000
 network 10.0.0.0 0.0.0.3 area 0
 network 40.0.0.0 0.0.0.255 area 1
!
router rip
 version 2
 network 10.0.0.0
 network 40.0.0.0
 network 60.0.0.0
 no auto-summary
!
ip forward-protocol nd
!
no ip http server
no ip http secure-server
!
!
!
!
snmp-server community ELPOLI RO
!
control-plane
!
!
!
line con 0
line aux 0
line 2
 no activation-character
 no exec
 transport preferred none
 transport output pad telnet rlogin lapb-ta mop udptn v120 ssh
 stopbits 1
line vty 0 4
 login local
 transport input telnet
!
scheduler allocate 20000 1000
ntp server pnpntpserver.redes2.poli.edu
!
end

R3#show ip run
            ^
% Invalid input detected at '^' marker.

R3#show ip root
             ^
% Invalid input detected at '^' marker.

R3#show ip ru
            ^
% Invalid input detected at '^' marker.

R3#show ip router
                ^
% Invalid input detected at '^' marker.

R3#show ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2
       i - IS-IS, su - IS-IS summary, L1 - IS-IS level-1, L2 - IS-IS level-2
       ia - IS-IS inter area, * - candidate default, U - per-user static route
       o - ODR, P - periodic downloaded static route, H - NHRP, l - LISP
       a - application route
       + - replicated route, % - next hop override

Gateway of last resort is not set

      3.0.0.0/32 is subnetted, 1 subnets
C        3.3.3.3 is directly connected, Loopback0
      10.0.0.0/8 is variably subnetted, 3 subnets, 2 masks
C        10.0.0.0/30 is directly connected, Serial0/0/0
C        10.0.0.1/32 is directly connected, Serial0/0/0
L        10.0.0.2/32 is directly connected, Serial0/0/0
      40.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        40.0.0.0/24 is directly connected, GigabitEthernet0/0
L        40.0.0.1/32 is directly connected, GigabitEthernet0/0
R     192.168.255.0/24 [120/1] via 10.0.0.1, 00:00:20, Serial0/0/0
R3#
*Nov 25 00:12:18.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to up
*Nov 25 00:12:19.187: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to up
*Nov 25 00:16:02.187: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 25 00:16:03.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
*Nov 25 00:16:07.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to up
*Nov 25 00:16:08.187: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to up
R3#show ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2
       i - IS-IS, su - IS-IS summary, L1 - IS-IS level-1, L2 - IS-IS level-2
       ia - IS-IS inter area, * - candidate default, U - per-user static route
       o - ODR, P - periodic downloaded static route, H - NHRP, l - LISP
       a - application route
       + - replicated route, % - next hop override

Gateway of last resort is not set

      3.0.0.0/32 is subnetted, 1 subnets
C        3.3.3.3 is directly connected, Loopback0
      10.0.0.0/8 is variably subnetted, 3 subnets, 2 masks
C        10.0.0.0/30 is directly connected, Serial0/0/0
C        10.0.0.1/32 is directly connected, Serial0/0/0
L        10.0.0.2/32 is directly connected, Serial0/0/0
      40.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        40.0.0.0/24 is directly connected, GigabitEthernet0/0
L        40.0.0.1/32 is directly connected, GigabitEthernet0/0
      60.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        60.0.0.0/24 is directly connected, GigabitEthernet0/1
L        60.0.0.1/32 is directly connected, GigabitEthernet0/1
R     192.168.255.0/24 [120/1] via 10.0.0.1, 00:00:09, Serial0/0/0
R3#

































R3 con0 is now available





Press RETURN to get started.











Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)

*Nov 25 00:42:18.187: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 25 00:42:19.187: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
Translating "pnpntpserver.redes2.poli.edu"...domain server (255.255.255.255)

R3>telnet R2
Translating "R2"...domain server (255.255.255.255)

% Bad IP address or host name
R3>
R3>
R3>telnet R2
Translating "R2"...domain server (255.255.255.255)

% Bad IP address or host name
R3>
R3>
R3>
R3>
R3>
R3>
R3>
R3>telnet 10.0.0.1
Trying 10.0.0.1 ...
% Connection refused by remote host

R3>telnet 50.0.0.1
Trying 50.0.0.1 ...
% Destination unreachable; gateway or host down

R3>telnet 20.0.01
% Bad IP address or host name
R3>exit

































R3 con0 is now available





Press RETURN to get started.


R3>
*Nov 25 00:51:04.543: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Nov 25 00:51:04.543: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
