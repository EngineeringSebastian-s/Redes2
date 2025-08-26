
R2>enable
R2#erase restart
R2#erase restart
         ^
% Invalid input detected at '^' marker.

R2#erase
R2#erase
R2#erase
% Incomplete command.

R2#erase restart
         ^
% Invalid input detected at '^' marker.

R2#erase restart
R2#erase restart+
R2#erase restart+
         ^
% Invalid input detected at '^' marker.

R2#help
Help may be requested at any point in a command by entering
a question mark '?'.  If nothing matches, the help list will
be empty and you must backup until entering a '?' shows the
available options.
Two styles of help are provided:
1. Full help is available when you are ready to enter a
   command argument (e.g. 'show ?') and describes each possible
   argument.
2. Partial help is provided when an abbreviated argument is entered
   and you want to know what arguments match the input
   (e.g. 'show pr?'.)

R2#erase
R2#erase
R2#erase
R2#erase
R2#erase
R2#erase start
% Incomplete command.

R2#erase start
R2#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]y[OK]
Erase of nvram: complete
R2#
R2#
*Aug 25 22:50:09.503: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram▒
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
    Onboard devices &
         buffer pools      0x01E8F000
-----------------------------------------------
               TOTAL:      0x01E8F000

Rounded IOMEM up to: 32MB.
Using 6 percent iomem. [32MB/512MB]

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

Cisco CISCO1941/K9 (revision 1.0) with 491520K/32768K bytes of memory.
Processor board ID FJC2052L0PP
2 Gigabit Ethernet interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)


         --- System Configuration Dialog ---

Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]: yes

At any point you may enter a question mark '?' for help.
Use ctrl-c to abort configuration dialog at any prompt.
Default settings are in square brackets '[]'.

Basic management setup configures only enough connectivity
for management of the system, extended setup will ask you
to configure each interface on the system

Would you like to enter basic management setup? [yes/no]: yes
Configuring global parameters:

  Enter host name [Router]: test

  The enable secret is a password used to protect access to
  privileged EXEC and configuration modes. This password, after
  entered, becomes encrypted in the configuration.
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret: 1234

  The enable password is used when you do not specify an
  enable secret password, with some older software versions, and
  some boot images.
  Enter enable password: 1234
% Please choose a password that is different from the enable secret
  Enter enable password: 1234

  The virtual terminal password is used to protect
  access to the router over a network interface.
  Enter virtual terminal password: 123
  Configure SNMP Network Management? [yes]: yes
    Community string [public]:

Current interface summary


Any interface listed with OK? value "NO" does not have a valid configuration

Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      NO  unset  initializing          down
GigabitEthernet0/0         unassigned      NO  unset  down                  down
GigabitEthernet0/1         unassigned      NO  unset  down                  down

Enter interface name used to connect to the
management network from the above interface summary:
% No defaulting allowed

Enter interface name used to connect to the
management network from the above interface summary:
% No defaulting allowed

Enter interface name used to connect to the
management network from the above interface summary: GigabitEthernet0/1

Configuring interface GigabitEthernet0/1:
  Configure IP on this interface? [yes]: yes
    IP address for this interface: 1203210321
% Bad Internet address.
% Enter an Internet address of the form 'X.X.X.X', where each
% letter corresponds to a decimal number between 0 and 255.

    IP address for this interface: 192.168.0.2
    Subnet mask for this interface [255.255.255.0] : 255.255.255.255
% Bad subnet mask.
% Enter a subnet mask of the form 'X.X.X.X', where each
letter corresponds to a decimal number between 0 and 255.

    IP address for this interface:
    IP address for this interface:
    IP address for this interface:
    IP address for this interface:
    IP address for this interface: 255.255.255.128
% Bad Internet address.
% Enter an Internet address of the form 'X.X.X.X', where each
% letter corresponds to a decimal number between 0 and 255.

    IP address for this interface: 192.168.0.2
    Subnet mask for this interface [255.255.255.0] : 255.255.255.0
    Class C network is 192.168.0.0, 24 subnet bits; mask is /24

The following configuration command script was created:

hostname test
enable secret 5 $1$mHcJ$FWUkT4TuCA.DSBod7NUDM/
enable password 1234
line vty 0 4
password 123
snmp-server community public
!
!
interface Embedded-Service-Engine0/0
shutdown
no ip address
!
interface GigabitEthernet0/0
shutdown
no ip address
!
interface GigabitEthernet0/1
no shutdown
ip address 192.168.0.2 255.255.255.0
no mop enabled
!
end


[0] Go to the IOS command prompt without saving this config.
[1] Return back to the setup without saving this config.
[2] Save this configuration to nvram and exit.

Enter your selection [2]:
The enable password you have chosen is the same as your enable secret.
This is not recommended.  Re-enter the enable password.

Building configuration...
Use the enabled mode 'configure' command to modify this configuration.


Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Aug 25 22:52:37.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Aug 25 22:52:44.719: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Aug 25 22:52:50.343: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Aug 25 22:52:50.343: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
*Aug 25 22:52:51.479: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Aug 25 22:52:51.479: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Aug 25 22:56:01.055: %SYS-5-CONFIG_I: Configured from console by console
*Aug 25 22:56:02.323: %IP-5-WEBINST_KILL: Terminating DNS process
*Aug 25 22:56:03.055: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Aug 25 22:56:03.055: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Aug 25 22:56:04.451: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Aug 25 22:56:08.839: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
*Aug 25 22:56:08.839: %SNMP-5-COLDSTART: SNMP agent on host test is undergoing a cold start
test>enable
Password:
test#erase start
test#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
test#
*Aug 25 22:56:44.659: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram▒
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
    Onboard devices &
         buffer pools      0x01E8F000
-----------------------------------------------
               TOTAL:      0x01E8F000

Rounded IOMEM up to: 32MB.
Using 6 percent iomem. [32MB/512MB]

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

Cisco CISCO1941/K9 (revision 1.0) with 491520K/32768K bytes of memory.
Processor board ID FJC2052L0PP
2 Gigabit Ethernet interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)


         --- System Configuration Dialog ---

Would you like to enter the initial configuration dialog? [yes/no]: no


Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Aug 25 22:59:08.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Aug 25 22:59:15.715: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Aug 25 22:59:21.347: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Aug 25 22:59:21.351: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
*Aug 25 22:59:22.487: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Aug 25 22:59:22.487: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Aug 25 23:00:16.967: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Aug 25 23:00:16.967: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Aug 25 23:00:16.967: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Aug 25 23:00:17.967: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Aug 25 23:00:18.235: %IP-5-WEBINST_KILL: Terminating DNS process
*Aug 25 23:00:22.679: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
Router>enable
Router#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#hostname R1
R1(config)#username cisco privilege 15 password cico
R1(config)#username cisco privilege 15 password cisco
R1(config)#^Z
R1#
*Aug 25 23:05:31.531: %SYS-5-CONFIG_I: Configured from console by console
R1#enable
R1#^Z
R1#exit

































R1 con0 is now available





Press RETURN to get started.





R1>enable cisco
          ^
% Invalid input detected at '^' marker.

R1>enable
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#help
Help may be requested at any point in a command by entering
a question mark '?'.  If nothing matches, the help list will
be empty and you must backup until entering a '?' shows the
available options.
Two styles of help are provided:
1. Full help is available when you are ready to enter a
   command argument (e.g. 'show ?') and describes each possible
   argument.
2. Partial help is provided when an abbreviated argument is entered
   and you want to know what arguments match the input
   (e.g. 'show pr?'.)

R1(config)#cisco
              ^
% Invalid input detected at '^' marker.

R1(config)#line console 0
R1(config-line)#login local
R1(config-line)#^Z
R1#
*Aug 25 23:08:21.515: %SYS-5-CONFIG_I: Configured from console by console
R1#exit

































R1 con0 is now available





Press RETURN to get started.



User Access Verification

Username: cisco
Password:
R1#wr
Building configuration...
[OK]
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#interface g0/0
R1(config-if)#no shut
R1(config-if)#ban
% Incomplete command.

R1(config-if)#
*Aug 25 23:09:45.715: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
R1(config-if)#ban
% Incomplete command.

R1(config-if)#ban
R1(config-if)#bandwidth 1000
R1(config-if)#ip add
R1(config-if)#ip address 192.168.255.1 255.255.255.0
R1(config-if)#ex
R1(config)#ex
% Ambiguous command:  "ex"
R1(config)#ex
% Ambiguous command:  "ex"
R1(config)#exit
R1#
*Aug 25 23:13:18.363: %SYS-5-CONFIG_I: Configured from console by cisco on console
R1#wr
Building configuration...
[OK]
R1#
R1#ex

































R1 con0 is now available





Press RETURN to get started.




▒
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

SETUP: new interface Serial0/0/0 placed in "shutdown" state
SETUP: new interface Serial0/0/1 placed in "shutdown" state


Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Aug 25 23:17:58.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Aug 25 23:18:09.555: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Aug 25 23:18:15.183: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
*Aug 25 23:18:15.183: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to

User Access Verification

Username:  down
*Aug 25 23:18:15.183: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Aug 25 23:18:15.183: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Aug 25 23:18:16.295: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Aug 25 23:18:16.299: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Aug 25 23:18:16.299: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Aug 25 23:18:16.299: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Aug 25 23:18:17.447: %SYS-5-CONFIG_I: Configured from memory by console
*Aug 25 23:18:19.431: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Aug 25 23:18:19.431: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Aug 25 23:18:19.495: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Aug 25 23:18:19.615: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Aug 25 23:18:20.479: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Aug 25 23:18:21.131: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
Username: cisco
Password:
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#interface s0/0/0
R1(config-if)#no shut
R1(config-if)#
*Aug 25 23:20:07.219: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
R1(config-if)#encap ppp
R1(config-if)#ban
R1(config-if)#bandwidth 64
R1(config-if)#ip add
R1(config-if)#ip address 20.0.0.0 255.255.255.252
Bad mask /30 for address 20.0.0.0
R1(config-if)#^Z
R1#w
*Aug 25 23:22:03.491: %SYS-5-CONFIG_I: Configured from console by cisco on consoler
Building configuration...
[OK]
R1#wr
Building configuration...
[OK]
R1#show ip route
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

R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#interface 0/0/1
                     ^
% Invalid input detected at '^' marker.

R1(config)#interface s0/0/1
R1(config-if)#no shut
R1(config-if)#encap ppp
*Aug 25 23:23:27.607: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
R1(config-if)#ban
R1(config-if)#bandwidth 64
R1(config-if)#ip add
R1(config-if)#ip address 10.0.0.2 255.255.255.252
R1(config-if)#^Z
R1#wr
*Aug 25 23:24:07.303: %SYS-5-CONFIG_I: Configured from console by cisco on console
Building configuration...
[OK]
R1#wr
Building configuration...
[OK]
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#line vty 0 4
R1(config-line)#login local
R1(config-line)#transport input telnet
R1(config-line)#^Z
R1#wr
*Aug 25 23:25:12.251: %SYS-5-CONFIG_I: Configured from console by cisco on console
Building configuration...
[OK]
R1#
R1#wr
Building configuration...
[OK]
R1#show ip route
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

R1#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         192.168.255.1   YES NVRAM  down                  down
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                unassigned      YES unset  down                  down
Serial0/0/1                10.0.0.2        YES manual down                  down
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#interface s0/0/0
R1(config-if)#no shut
R1(config-if)#ban
R1(config-if)#encap ppp
R1(config-if)#ban
R1(config-if)#bandwidth 64
R1(config-if)#ip add
R1(config-if)#ip address 20.0.0.0 255.255.255.252
Bad mask /30 for address 20.0.0.0
R1(config-if)#ip address 20.0.0.2 255.255.255.252
R1(config-if)#^Z
R1#
*Aug 25 23:27:37.567: %SYS-5-CONFIG_I: Configured from console by cisco on console
R1#wr
Building configuration...
[OK]
R1#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#interface s0/0/0
R1(config-if)#no shut
R1(config-if)#encap ppp
R1(config-if)#bandwidth 64
R1(config-if)#ip address 20.0.0.1 255.255.255.252
R1(config-if)#^Z
R1#
*Aug 25 23:28:25.315: %SYS-5-CONFIG_I: Configured from console by cisco on console
R1#wr
Building configuration...
[OK]
R1#
R1#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         192.168.255.1   YES NVRAM  down                  down
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                20.0.0.1        YES manual down                  down
Serial0/0/1                10.0.0.2        YES manual down                  down
R1#conf t
*Aug 25 23:34:13.671: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Aug 25 23:34:22.331: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Aug 25 23:35:57.079: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
*Aug 25 23:36:15.535: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up
Enter configuration commands, one per line.  End with CNTL/Z.
R1(config)#ex
% Ambiguous command:  "ex"
R1(config)#exit
R1#show ip interface brief
*Aug 25 23:40:54.383: %SYS-5-CONFIG_I: Configured from cons
R1#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         192.168.255.1   YES NVRAM  down                  down
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                20.0.0.1        YES manual up                    up
Serial0/0/1                10.0.0.2        YES manual down                  down
R1#
*Aug 25 23:42:52.191: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Aug 25 23:42:53.191: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
R1#show ip interface brief
Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      YES NVRAM  administratively down down
GigabitEthernet0/0         192.168.255.1   YES NVRAM  up                    up
GigabitEthernet0/1         unassigned      YES NVRAM  administratively down down
Serial0/0/0                20.0.0.1        YES manual up                    up
Serial0/0/1                10.0.0.2        YES manual down                  down
R1#
