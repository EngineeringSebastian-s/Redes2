
R3>
R3>enable
R3#erase star
R3#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
R3#
R3#
*Nov 10 22:35:48.655: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram▒
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
Self decompressing the image : ######################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        ########################################################################## [OK]

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

Would you like to enter the initial configuration dialog? [yes/no]: no

Would you like to terminate autoinstall? [yes]: yes


Press RETURN to get started!


*Jan  2 00:00:02.179: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek                                                                                                                        9 and License = ipbasek9
*Nov 10 22:38:07.615: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Nov 10 22:38:18.555: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Nov 10 22:38:24.171: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Nov 10 22:38:24.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
*Nov 10 22:38:24.175: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Nov 10 22:38:24.175: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Nov 10 22:38:25.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Nov 10 22:38:25.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 10 22:38:25.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Nov 10 22:38:25.291: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Nov 10 22:39:34.499: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Nov 10 22:39:34.499: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Nov 10 22:39:34.499: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Nov 10 22:39:34.499: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Nov 10 22:39:34.499: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Nov 10 22:39:35.499: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to do                                                                                                                        wn
*Nov 10 22:39:36.095: %IP-5-WEBINST_KILL: Terminating DNS process
*Nov 10 22:39:45.435: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
Router>hostname R3
        ^
% Invalid input detected at '^' marker.

Router>enable
Router#hostname R3
        ^
% Invalid input detected at '^' marker.

Router#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#hostname R3
R3(config)#exit
R3#wr
*Nov 10 22:44:32.143: %SYS-5-CONFIG_I: Configured from console by console
Building configuration...
[OK]
R3#username cisco priviliege 15 password cisco
    ^
% Invalid input detected at '^' marker.

R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#username cisco privilegie 15 password cisco
                                  ^
% Invalid input detected at '^' marker.

R3(config)#username cisco pri
R3(config)#username cisco privilege 15 password cisco
R3(config)#exit
R3#wr
*Nov 10 22:46:14.171: %SYS-5-CONFIG_I: Configured from console by console
Building configuration...
[OK]
R3#eixt
% Bad IP address or host name
Translating "eixt"...domain server (255.255.255.255)
 (255.255.255.255)
% Unknown command or computer name, or unable to find computer address
R3#exit

































R3 con0 is now available





Press RETURN to get started.





R3>clear
% Type "clear ?" for a list of subcommands
R3>enable cisco
          ^
% Invalid input detected at '^' marker.

R3>enable
R3#clear
% Type "clear ?" for a list of subcommands
R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#exit
R3#config
Configuring from terminal, memory, or network [terminal]?
*Nov 10 22:56:45.183: %SYS-5-CONFIG_I: Configured from console by console
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#exit
R3#
*Nov 10 22:56:53.603: %SYS-5-CONFIG_I: Configured from console by console
R3#config
Configuring from terminal, memory, or network [terminal]? terminal
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#▒
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
Self decompressing the image : ######################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        #####################################################################################################################                                                                                                                        ########################################################################## [OK]

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

%Error: This command applies only to DCE interfaces


Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek                                                                                                                        9 and License = ipbasek9
*Nov 10 23:00:43.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Nov 10 23:00:54.555: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Nov 10 23:01:00.155: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Nov 10 23:01:00.155: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to
R3> down
*Nov 10 23:01:00.155: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Nov 10 23:01:00.155: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Nov 10 23:01:01.267: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Nov 10 23:01:01.271: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Nov 10 23:01:01.271: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Nov 10 23:01:01.271: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Nov 10 23:01:02.487: %SYS-5-CONFIG_I: Configured from memory by console
*Nov 10 23:01:03.095: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
*Nov 10 23:01:04.379: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Nov 10 23:01:04.387: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Nov 10 23:01:04.391: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Nov 10 23:01:04.399: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Nov 10 23:01:04.463: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Nov 10 23:01:05.379: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to do                                                                                                                        wn
R3>enable
R3#config
Configuring from terminal, memory, or network [terminal]? yes
?Must be "terminal", "memory" or "network"
R3#config
Configuring from terminal, memory, or network [terminal]? network
Host or network configuration file [host]?
This command has been replaced by the command:
         'copy <url> system:/running-config'
Address or name of remote host [255.255.255.255]?
Source filename [r3-confg]?
Configure using tftp://255.255.255.255/r3-confg? [confirm]
%Error opening tftp://255.255.255.255/r3-confg (Socket error)
R3#config
Configuring from terminal, memory, or network [terminal]? memory

%Error: This command applies only to DCE interfaces
R3#
*Nov 10 23:02:09.979: %SYS-5-CONFIG_I: Configured from memory by console
R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#inteface g0/0
               ^
% Invalid input detected at '^' marker.

R3(config)#interface g0/0
R3(config-if)#no shut
R3(config-if)#
*Nov 10 23:03:11.615: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Nov 10 23:03:14.163: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Nov 10 23:03:15.163: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
R3(config-if)#encapp pp
                   ^
% Invalid input detected at '^' marker.

R3(config-if)#encap pp
                    ^
% Invalid input detected at '^' marker.

R3(config-if)#encap ppp
                    ^
% Invalid input detected at '^' marker.

R3(config-if)#ban
R3(config-if)#bandwidth 1000
R3(config-if)#ip add
R3(config-if)#ip address 40.0.0.3 255.255.255.0
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:05:22.263: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface serial 0/0/0
R3(config-if)#no shut
R3(config-if)#enca
*Nov 10 23:05:43.355: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Nov 10 23:05:44.355: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to
% Incomplete command.

R3(config-if)#encap ppp
R3(config-if)#ban
R3(config-if)#bandwidth
*Nov 10 23:05:52.419: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down64
R3(config-if)#ip add
R3(config-if)#ip address 10.0.0.2 255.255.255.252
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:06:57.359: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#
R3#R3(config)#interface g0/0
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#no shut
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#$ %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Nov 10 23:03:11.615: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed stat^e to down

% Invalid input detected at '^' marker.

R3#$ %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Nov 10 23:03:14.163: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed stat^e to up

% Invalid input detected at '^' marker.

R3#$: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Nov 10 23:03:15.163: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEth^ernet0/0, changed state to up

% Invalid input detected at '^' marker.

R3#R3(config-if)#encapp pp
    ^
% Invalid input detected at '^' marker.

R3#                   ^
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#% Invalid input detected at '^' marker.
   ^
% Invalid input detected at '^' marker.

R3#
R3#R3(config-if)#encap pp
    ^
% Invalid input detected at '^' marker.

R3#                    ^
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#% Invalid input detected at '^' marker.
   ^
% Invalid input detected at '^' marker.

R3#
R3#R3(config-if)#encap ppp
    ^
% Invalid input detected at '^' marker.

R3#                    ^
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#% Invalid input detected at '^' marker.
   ^
% Invalid input detected at '^' marker.

R3#
R3#R3(config-if)#ban
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3(config-if)#bandwidth 1000
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3(config-if)#ip add
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#ip address 40.0.0.3 255.255.255.0
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#exit
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3(config)#exit
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3#wr
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#Building configuration...
     ^
% Invalid input detected at '^' marker.

R3#
R3#$05:22.263: %SYS-5-CONFIG_I: Configured from console by console[OK]
*Nov 10 23:05:22.263: %SYS-5-CONFIG_I: Configured from console by console[OK]
^
% Invalid input detected at '^' marker.

R3#R3#config
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#Configuring from terminal, memory, or network [terminal]?
% Unrecognized command
R3#Configuring from terminal, memory, or network [terminal]
           ^
% Invalid input detected at '^' marker.

R3#Enter configuration commands, one per line.  End with CNTL/Z.
     ^
% Invalid input detected at '^' marker.

R3#R3(config)#interface serial 0/0/0
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#no shut
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#enca
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#$05:43.355: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Nov 10 23:05:43.355: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up^

% Invalid input detected at '^' marker.

R3#$O-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to
*Nov 10 23:05:44.355: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/^0, changed state to

% Invalid input detected at '^' marker.

R3#% Incomplete command.
   ^
% Invalid input detected at '^' marker.

R3#
R3#R3(config-if)#encap ppp
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#ban
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3(config-if)#bandwidth
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#$: Line protocol on Interface Serial0/0/0, changed state to down64
*Nov 10 23:05:52.419: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/^0, changed state to down64

% Invalid input detected at '^' marker.

R3#R3(config-if)#ip add
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#ip address 10.0.0.2 255.255.255.252
    ^
% Invalid input detected at '^' marker.

R3#R3(config-if)#exit
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3(config)#exit
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#R3#wr
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#Building configuration...
     ^
% Invalid input detected at '^' marker.

R3#
R3#$06:57.359: %SYS-5-CONFIG_I: Configured from console by console[OK]
*Nov 10 23:06:57.359: %SYS-5-CONFIG_I: Configured from console by console[OK]
^
% Invalid input detected at '^' marker.

R3#R3#
% Bad IP address or host name
% Unknown command or computer name, or unable to find computer address
R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface g0/0
R3(config-if)#no shut
R3(config-if)#ip add
R3(config-if)#bandwidth 1000
R3(config-if)#ip add
R3(config-if)#ip address 40.0.0.1 255.255.255.0
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:11:34.415: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#config
Configuring from terminal, memory, or network [terminal]?
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#line vty 0 4
R3(config-line)#login local
R3(config-line)#transport input telnet
R3(config-line)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:14:01.639: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    down
Serial0/0/1                unassigned      YES NVRAM  administratively down down
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#router rip
R3(config-router)#version 2
R3(config-router)#network network 10.0.0.0
                          ^
% Invalid input detected at '^' marker.

R3(config-router)#network 10.0.0.0
R3(config-router)#network 40.0.0.0
R3(config-router)#no au
R3(config-router)#no auto-summary
R3(config-router)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:18:10.411: %SYS-5-CONFIG_I: Configured from console by console[OK]
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

      40.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        40.0.0.0/24 is directly connected, GigabitEthernet0/0
L        40.0.0.1/32 is directly connected, GigabitEthernet0/0
R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    down
Serial0/0/1                unassigned      YES NVRAM  administratively down down
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#interface loopback0
R3(config-if)#ip
*Nov 10 23:22:49.879: %LINEPROTO-5-UPDOWN: Line protocol on Interface Loopback0, changed state to
R3(config-if)#ip a
R3(config-if)#ip add
R3(config-if)#ip address 3.3.3.3 255.255.255.255
R3(config-if)#exit
R3(config)#router ospf 1000
R3(config-router)#log-adjacency-changes
R3(config-router)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:23:52.455: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#router ospf 1000
R3(config-router)#log-adjacency-changes
R3(config-router)#network 10.0.0.0 0.0.0.3 area 0
R3(config-router)#network 40.0.0.0 0.0.0.255 area 1
R3(config-router)#end
R3#wr
Building configuration...

*Nov 10 23:25:26.379: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    down
Serial0/0/1                unassigned      YES NVRAM  administratively down down
Loopback0                  3.3.3.3         YES manual up                    up
R3#ping 40.0.0.2
Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 40.0.0.2, timeout is 2 seconds:
.!!!!
Success rate is 80 percent (4/5), round-trip min/avg/max = 1/1/1 ms
R3#ping 40.0.0.2
Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 40.0.0.2, timeout is 2 seconds:
!!!!!
Success rate is 100 percent (5/5), round-trip min/avg/max = 1/1/4 ms
R3#
R3#
*Nov 10 23:34:19.155: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEth                                                                                                                                                             ernet0/0, changed state to down
*Nov 10 23:34:21.163: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEth                                                                                                                                                             ernet0/0, changed state to up
R3#wr
Building configuration...
[OK]
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
      40.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        40.0.0.0/24 is directly connected, GigabitEthernet0/0
L        40.0.0.1/32 is directly connected, GigabitEthernet0/0
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#ip dhcp pool LANX
R3(dhcp-config)#network 40.0.0.0 255.255.255.0
R3(dhcp-config)#default
*Nov 10 23:41:21.407: %DHCPD-4-PING_CONFLICT: DHCP address conflict:  server pinged 4
R3(dhcp-config)#default-router 40.0.0.1
R3(dhcp-config)#domain
R3(dhcp-config)#domain-name redes2.poli.edu
R3(dhcp-config)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 10 23:42:12.191: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#snmp-
R3(config)#snmp-server comm
R3(config)#snmp-server community ELPOLI
R3(config)#snmp-server community ELPOLI RO
R3(config)#ip dhcp pool LANX
R3(dhcp-config)#exit
R3(config)#ip dhcp excluded-add
R3(config)#ip dhcp excluded-address 40.0.0.1
R3(config)#ip dhcp excluded-address

































R3 con0 is now available





Press RETURN to get started.


*Nov 11 00:01:49.775: %SYS-5-CONFIG_I: Configured from console by console
R3>config
Translating "config"...domain server (255.255.255.255)

% Bad IP address or host name
Translating "config"...domain server (255.255.255.255)
 (255.255.255.255)
Translating "config"...domain server (255.255.255.255)

% Unknown command or computer name, or unable to find computer address
R3>
R3>
R3>
R3>enable
R3#config t
Enter configuration commands, one per line.  End with CNTL/Z.
R3(config)#dhcp exclu
R3(config)#dhcp excl
R3(config)#dhcp excluded
R3(config)#ip dhcp ex
R3(config)#ip dhcp excluded-address 40.0.0.6
R3(config)#ip dhcp excluded-address 40.0.0.5
R3(config)#ip dhcp excluded-address 40.0.0.7
R3(config)#interface serial 0/0/0
R3(config-if)#no shut
R3(config-if)#exit
R3(config)#exit
R3#wr
Building configuration...

*Nov 11 00:24:40.863: %SYS-5-CONFIG_I: Configured from console by console[OK]
R3#
R3#sh
% Type "show ?" for a list of subcommands
R3#show ip config
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
      40.0.0.0/8 is variably subnetted, 2 subnets, 2 masks
C        40.0.0.0/24 is directly connected, GigabitEthernet0/0
L        40.0.0.1/32 is directly connected, GigabitEthernet0/0
R3#show ip vlan brief
            ^
% Invalid input detected at '^' marker.

R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    down
Serial0/0/1                unassigned      YES NVRAM  administratively down down
Loopback0                  3.3.3.3         YES manual up                    up
R3#
R3#
*Nov 11 00:31:35.475: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up
R3#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         40.0.0.1        YES manual up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                10.0.0.2        YES manual up                    up
Serial0/0/1                unassigned      YES NVRAM  administratively down down
Loopback0                  3.3.3.3         YES manual up                    up
R3#config
