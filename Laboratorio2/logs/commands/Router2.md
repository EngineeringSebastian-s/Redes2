R3#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
R3#
*Sep 22 22:57:08.267: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvramerase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]e
File system erase is not confirmed or Could not be completed
R3#rase startup-config
    ^
% Invalid input detected at '^' marker.

R3#
R3#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
R3#
*Sep 22 22:57:41.987: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram
R3#wr
Building configuration...
[OK]
R3#exit

































R3 con0 is now available





Press RETURN to get started.











*** ATENCION ***
Si te equivocas el profesor te va seguir en tu mente con shorun
--- No puedes escapar ---

R3>en
Password:
Password:
Password:
R3#reload
Proceed with reload? [confirm]c
R3#reload
Proceed with reload? [confirm]

*Sep 22 22:59:06.055: %SYS-5-RELOAD: Reload requested by console. Reload Reason: Reload Command.
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
Processor board ID FJC2052L0PM
2 Gigabit Ethernet interfaces
2 Serial(sync/async) interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)



Press RETURN to get started!


*Jan  2 00:00:02.175: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Sep 22 23:00:58.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Sep 22 23:01:09.539: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Sep 22 23:01:15.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:01:15.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to d
*** ATENCION ***
Si te equivocas el profesor te va seguir en tu mente con shorun
--- No puedes escapar ---

R3>own
*Sep 22 23:01:15.179: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Sep 22 23:01:15.179: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Sep 22 23:01:16.283: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:01:16.283: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Sep 22 23:01:16.283: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Sep 22 23:01:16.283: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Sep 22 23:01:17.471: %SYS-5-CONFIG_I: Configured from memory by console
*Sep 22 23:01:18.419: %LINEPROTO-5-UPDOWN: Line protocol on Interface Loopback0, changed state to up
*Sep 22 23:01:19.455: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Sep 22 23:01:19.455: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Sep 22 23:01:19.455: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Sep 22 23:01:20.179: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
*Sep 22 23:01:20.815: %SYS-6-BOOTTIME: Time taken to reboot after reload =  133 seconds
*Sep 22 23:01:21.431: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
R3>
R3>
R3>exit

































R3 con0 is now available





Press RETURN to get started.


*** ATENCION ***
Si te equivocas el profesor te va seguir en tu mente con shorun
--- No puedes escapar ---

R3>enable R2
          ^
% Invalid input detected at '^' marker.

R3>EN
Password:
R3#hostname R2
    ^
% Invalid input detected at '^' marker.

R3#name R2
        ^
% Invalid input detected at '^' marker.

R3#help
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

R3#exit

































R3 con0 is now available





Press RETURN to get started.











*** ATENCION ***
Si te equivocas el profesor te va seguir en tu mente con shorun
--- No puedes escapar ---

R3>ex

































R3 con0 is now available





Press RETURN to get started.














*** ATENCION ***
Si te equivocas el profesor te va seguir en tu mente con shorun
--- No puedes escapar ---

R3>
R3>
R3>en
Password:
R3#erase star
R3#erase startup-config reload
                        ^
% Invalid input detected at '^' marker.

R3#erase startup-config help
                        ^
% Invalid input detected at '^' marker.

R3#erase startup-config a
R3#erase startup-config b
R3#erase startup-config
R3#erase startup-config c
R3#erase startup-config d
R3#erase startup-config
R3#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
R3#
R3#real
*Sep 22 23:03:41.927: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of n
R3#reaload
Translating "reaload"...domain server (255.255.255.255)

% Bad IP address or host name
Translating "reaload"...domain server (255.255.255.255)
 (255.255.255.255)
Translating "reaload"...domain server (255.255.255.255)

% Unknown command or computer name, or unable to find computer address
R3#
R3#
R3#
R3#reload
Proceed with reload? [confirm]c
R3#reload
Proceed with reload? [confirm]

*Sep 22 23:04:41.543: %SYS-5-RELOAD: Reload requested by console. Reload Reason: Reload Command.
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
Processor board ID FJC2052L0PM
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
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
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

  Enter host name [Router]: R2

  The enable secret is a password used to protect access to
  privileged EXEC and configuration modes. This password, after
  entered, becomes encrypted in the configuration.
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret:
% No defaulting allowed
  Enter enable secret: ex

  The enable password is used when you do not specify an
  enable secret password, with some older software versions, and
  some boot images.
  Enter enable password: cisco2025

  The virtual terminal password is used to protect
  access to the router over a network interface.
  Enter virtual terminal password: cisco2025
  Configure SNMP Network Management? [yes]: yes
    Community string [public]:

Current interface summary


Any interface listed with OK? value "NO" does not have a valid configuration

Interface                  IP-Address      OK? Method Status                Protocol
Embedded-Service-Engine0/0 unassigned      NO  unset  initializing          down
GigabitEthernet0/0         unassigned      NO  unset  up                    up
GigabitEthernet0/1         unassigned      NO  unset  down                  down
Serial0/0/0                unassigned      NO  unset  down                  down
Serial0/0/1                unassigned      NO  unset  down                  down

Enter interface name used to connect to the
management network from the above interface summary:
% No defaulting allowed

Enter interface name used to connect to the
management network from the above interface summary:
Invalid interface


Configuration aborted, no changes made.



Press RETURN to get started!

own
*Sep 22 23:06:48.147: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Sep 22 23:06:48.147: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Sep 22 23:06:49.251: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:06:49.251: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Sep 22 23:06:49.251: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Sep 22 23:06:49.251: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Sep 22 23:08:12.895: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Sep 22 23:08:12.895: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Sep 22 23:08:12.895: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Sep 22 23:08:12.895: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Sep 22 23:08:12.895: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Sep 22 23:08:13.895: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Sep 22 23:08:13.895: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Sep 22 23:08:15.143: %IP-5-WEBINST_KILL: Terminating DNS process
*Sep 22 23:08:18.779: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
*Sep 22 23:08:19.411: %SYS-6-BOOTTIME: Time taken to reboot after reload =  219 seconds
Router>en
Router#erase star
Router#erase startup-config
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
[OK]
Erase of nvram: complete
Router#
*Sep 22 23:08:48.719: %SYS-7-NV_BLOCK_INIT: Initialized the geometry of nvram▒
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
Processor board ID FJC2052L0PM
2 Gigabit Ethernet interfaces
2 Serial(sync/async) interfaces
1 terminal line
DRAM configuration is 64 bits wide with parity disabled.
255K bytes of non-volatile configuration memory.
245448K bytes of ATA System CompactFlash 0 (Read/Write)


         --- System Configuration Dialog ---

Would you like to enter the initial configuration dialog? [yes/no]:
% Please answer 'yes' or 'no'.
Would you like to enter the initial configuration dialog? [yes/no]: no

Would you like to terminate autoinstall? [yes]: yes


Press RETURN to get started!


*Jan  2 00:00:02.171: %IOS_LICENSE_IMAGE_APPLICATION-6-LICENSE_LEVEL: Module name = c1900 Next reboot level = ipbasek9 and License = ipbasek9
*Sep 22 23:11:16.619: c3600_scp_set_dstaddr2_idb(184)add = 80 name is Embedded-Service-Engine0/0
*Sep 22 23:11:27.535: %CTS-6-ENV_DATA_START_STATE: Environment Data Download in start state
*Sep 22 23:11:33.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:11:33.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/1, changed state to down
*Sep 22 23:11:33.175: %LINK-3-UPDOWN: Interface Serial0/0/0, changed state to down
*Sep 22 23:11:33.175: %LINK-3-UPDOWN: Interface Serial0/0/1, changed state to down
*Sep 22 23:11:34.279: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:11:34.279: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/1, changed state to down
*Sep 22 23:11:34.279: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to down
*Sep 22 23:11:34.279: %LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/1, changed state to down
*Sep 22 23:12:30.067: %LINK-5-CHANGED: Interface Serial0/0/0, changed state to administratively down
*Sep 22 23:12:30.067: %LINK-5-CHANGED: Interface Embedded-Service-Engine0/0, changed state to administratively down
*Sep 22 23:12:30.067: %LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to administratively down
*Sep 22 23:12:30.067: %LINK-5-CHANGED: Interface GigabitEthernet0/1, changed state to administratively down
*Sep 22 23:12:30.067: %LINK-5-CHANGED: Interface Serial0/0/1, changed state to administratively down
*Sep 22 23:12:30.083: %IP-5-WEBINST_KILL: Terminating DNS process
*Sep 22 23:12:31.067: %LINEPROTO-5-UPDOWN: Line protocol on Interface Embedded-Service-Engine0/0, changed state to down
*Sep 22 23:12:31.067: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to down
*Sep 22 23:12:33.723: %SYS-5-RESTART: System restarted --
Cisco IOS Software, C1900 Software (C1900-UNIVERSALK9-M), Version 15.4(3)M3, RELEASE SOFTWARE (fc2)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2015 by Cisco Systems, Inc.
Compiled Fri 05-Jun-15 12:31 by prod_rel_team
Router>en
Router#hostname R2
        ^
% Invalid input detected at '^' marker.

Router#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#hostname R2
R2(config)#exit
R2#wr
Building configuration...

*Sep 22 23:13:53.963: %SYS-5-CONFIG_I: Configured from console by console[OK]
R2#
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#interface g0/0
R2(config-if)#no shutdown
R2(config-if)#exit
R2(config)#
*Sep 22 23:14:58.831: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to down
R2(config)#
*Sep 22 23:15:03.175: %LINK-3-UPDOWN: Interface GigabitEthernet0/0, changed state to up
*Sep 22 23:15:04.175: %LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
R2(config)#show ipv6 route
             ^
% Invalid input detected at '^' marker.

R2(config)#exit
R2#show ipv6 route
R2#
*Sep 22 23:16:48.011: %SYS-5-CONFIG_I: Configured from console by console
R2#no service time
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#no service timestamps log datetime msec
R2(config)#no service timestamps deubg datetime msec
                                   ^
% Invalid input detected at '^' marker.

R2(config)#no service timestamps debug datetime msec
R2(config)#no service password-encryption
R2(config)#no ip domain-lookup
R2(config)#ip cef
R2(config)#ipv6 unicast-routing
R2(config)#ipv6 cef
R2(config)#ipv6 dhcp pool LAN2
R2(config-dhcpv6)#addre
R2(config-dhcpv6)#address prefix ABCD:1:1:3::/64
R2(config-dhcpv6)#dns
R2(config-dhcpv6)#dns-server ABCD:3::F0
R2(config-dhcpv6)#doma
R2(config-dhcpv6)#domain-name redes2.elpoli.edu.co
R2(config-dhcpv6)#exit
R2(config)#exit
R2#wr
Building configuration...

%SYS-5-CONFIG_I: Configured from console by console[OK]
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#username cisco privilege 15 password 0 cisco
R2(config)#ipv6 host R1 ABCD:1:1:1::1
R2(config)#ipv6 host R2 ABCD:1:1:3::1
R2(config)#ipv6 host R3 ABCD:1:1:5::1
R2(config)#ipv6 host R4 ABCD:1:1:6::1
R2(config)#span
R2(config)#spanning-tree mode pvst
                         ^
% Invalid input detected at '^' marker.

R2(config)#spanning-tree m
R2(config)#spanning-tree mB?
% Unrecognized command
R2(config)#spanning-tree mBB?
% Unrecognized command
R2(config)#spanning-tree
% Incomplete command.

R2(config)#spanning-tree help
                         ^
% Invalid input detected at '^' marker.

R2(config)#spanning-tree a
R2(config)#spanning-tree m
R2(config)#spanning-tree b
R2(config)#interface g0/0
R2(config-if)#no shutdown
R2(config-if)#no ip ad
R2(config-if)#no ip address
R2(config-if)#duplex auto
R2(config-if)#speed auto
R2(config-if)#ipv6 a
R2(config-if)#ipv6 add
R2(config-if)#ipv6 address ABCD:1:1:3::1/64
R2(config-if)#ipv6 eigrp 32000
R2(config-if)#ipv6 enable
R2(config-if)#ipv6 nd ma
R2(config-if)#ipv6 nd managed-config-flag
R2(config-if)#ipv6 dhcp server LAN2
R2(config-if)#exit
R2(config)#exit
R2#wr
Building configuration...

%SYS-5-CONFIG_I: Configured from console by console[OK]
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#inteface s0/0/0
               ^
% Invalid input detected at '^' marker.

R2(config)#interface s0/0/0
R2(config-if)#no shutdown
R2(config-if)#n
%LINK-3-UPDOWN: Interface Serial0/0/0, changed state to dow
R2(config-if)#no ip a
R2(config-if)#no ip ad
R2(config-if)#no ip address
R2(config-if)#duplex auto
               ^
% Invalid input detected at '^' marker.

R2(config-if)#sp
%LINK-3-UPDOWN: Interface Serial0/0/0, changed state to up
%LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to
R2(config-if)#bandwith 65
                    ^
% Invalid input detected at '^' marker.

R2(config-if)#bandwith 64
                    ^
% Invalid input detected at '^' marker.

R2(config-if)#nad
%LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to d
R2(config-if)#ex
R2(config)#interface s0/0/0
R2(config-if)#no shutdown
R2(config-if)#ban
R2(config-if)#bandwidth 64
R2(config-if)#no ip add
R2(config-if)#no ip address
R2(config-if)#enca
R2(config-if)#encapsulation PPP
R2(config-if)#ipv6
%LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state
R2(config-if)#ipv6 add
R2(config-if)#ipv6 address ABCD:1:1:2:2/64
% Incomplete command.

R2(config-if)#ipv6 address ABCD:1:1:2::2/64
R2(config-if)#ipv6 ei
R2(config-if)#ipv6 eigrp 32000
R2(config-if)#ipv6 enable
R2(config-if)#exit
R2(config)#exit
R2#wr
Building configuration...
[OK]
%SYS-5-CONFIG_I: Configured from console by console
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#interface s0/0/1
R2(config-if)#no ip add
R2(config-if)#no ip address
R2(config-if)#clok rate 200000
                 ^
% Invalid input detected at '^' marker.

R2(config-if)#clock rate 200000
clock rate 200000 is not supported

R2(config-if)#shutdown
R2(config-if)#ex
R2(config)#ex
% Ambiguous command:  "ex"
R2(config)#exit
R2#ex
%SYS-5-CONFIG_I: Configured from console by conso
R2#wr
Building configuration...
[OK]
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#interface vlan1
                      ^
% Invalid input detected at '^' marker.

R2(config)#interface Vlan1
                      ^
% Invalid input detected at '^' marker.

R2(config)#ipv6 router e
R2(config)#ipv6 router eigrp 32000
R2(config-rtr)#eig
R2(config-rtr)#eigrp router
R2(config-rtr)#eigrp router-id 2.2.2.2
R2(config-rtr)#no shutdown
R2(config-rtr)#exit
R2(config)#exit
R2#wr
Building configuration...

%SYS-5-CONFIG_I: Configured from console by console[OK]
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#line con 0
R2(config-line)#exit
R2(config)#line aux 0
R2(config-line)#exit
R2(config)#line vty 0 4
R2(config-line)#login local
R2(config-line)#exit
R2(config)#exit
R2#wr
Building configuration...

%SYS-5-CONFIG_I: Configured from console by console[OK]
R2#
R2#show run
Building configuration...

Current configuration : 1658 bytes
!
! Last configuration change at 23:38:22 UTC Mon Sep 22 2025
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input none
!
scheduler allocate 20000 1000
!
end

R2#show run
Building configuration...

Current configuration : 1658 bytes
!
! Last configuration change at 23:38:22 UTC Mon Sep 22 2025
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input none
!
scheduler allocate 20000 1000
!
end

R2#show ipv6 route
IPv6 Routing Table - default - 5 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
L   FF00::/8 [0/0]
     via Null0, receive
R2#show ipv6 dhcp pool,
                      ^
% Invalid input detected at '^' marker.

R2#show ipv6 dhcp pool
DHCPv6 pool: LAN2
  Address allocation prefix: ABCD:1:1:3::/64 valid 172800 preferred 86400 (1 in use, 0 conflicts)
  DNS server: ABCD:3::F0
  Domain name: redes2.elpoli.edu.co
  Active clients: 1
R2#wr
Building configuration...
[OK]
R2#show run
Building configuration...

Current configuration : 1658 bytes
!
! Last configuration change at 23:38:22 UTC Mon Sep 22 2025
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input none
!
scheduler allocate 20000 1000
!
end

R2#
R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#ipv6 router e
R2(config)#ipv6 router eigrp 32000
R2(config-rtr)#no shutdown
R2(config-rtr)#ex
R2(config)#ex
% Ambiguous command:  "ex"
R2(config)#exit
R2#wr
Building configuration...

%SYS-5-CONFIG_I: Configured from console by console[OK]
R2#
R2#show run
Building configuration...

Current configuration : 1658 bytes
!
! Last configuration change at 23:48:25 UTC Mon Sep 22 2025
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input none
!
scheduler allocate 20000 1000
!
end

R2#
%DUAL-5-NBRCHANGE: EIGRP-IPv6 32000: Neighbor FE80::2A2:EEFF:FE2B:D6C0 (Serial0/0/0) is up: new adjacency
R2#show run
Building configuration...

Current configuration : 1658 bytes
!
! Last configuration change at 23:48:25 UTC Mon Sep 22 2025
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input none
!
scheduler allocate 20000 1000
!
end

R2#conf t
Enter configuration commands, one per line.  End with CNTL/Z.
R2(config)#line vty 0 4
R2(config-line)#login local
R2(config-line)#transport input telnet
R2(config-line)#ex
% Ambiguous command:  "ex"
R2(config-line)#exit
R2(config)#exit
R2#
%SYS-5-CONFIG_I: Configured from console by consolewr
Building configuration...
[OK]
R2#wr
Building configuration...
[OK]
R2#
R2#
%SYS-5-CONFIG_I: Configured from console by cisco on vty0 (ABCD:1:1:3:C986:21B6:F059:BE61)
R2#show ipv6 eigrp neighbor
EIGRP-IPv6 Neighbors for AS(32000)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   Link-local address:     Se0/0/0                  13 00:11:01    1  2370  0  3
    FE80::2A2:EEFF:FE2B:D6C0
R2#show ipv6 eigrp neighbor
EIGRP-IPv6 Neighbors for AS(32000)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   Link-local address:     Se0/0/0                  13 00:11:10    1  2370  0  3
    FE80::2A2:EEFF:FE2B:D6C0
R2#show vlan brief
% Ambiguous command:  "show vlan brief"
R2#show ipv6 eigrp neighbor
EIGRP-IPv6 Neighbors for AS(32000)
H   Address                 Interface              Hold Uptime   SRTT   RTO  Q  Seq
                                                   (sec)         (ms)       Cnt Num
0   Link-local address:     Se0/0/0                  14 00:19:58    1  2370  0  8
    FE80::2A2:EEFF:FE2B:D6C0
R2#show ipv6 dhcp pool
DHCPv6 pool: LAN2
  Address allocation prefix: ABCD:1:1:3::/64 valid 172800 preferred 86400 (2 in use, 0 conflicts)
  DNS server: ABCD:3::F0
  Domain name: redes2.elpoli.edu.co
  Active clients: 2
R2#show ip run
            ^
% Invalid input detected at '^' marker.

R2#show run
Building configuration...

Current configuration : 1669 bytes
!
! Last configuration change at 00:00:43 UTC Tue Sep 23 2025 by cisco
!
version 15.4
no service timestamps debug uptime
no service timestamps log uptime
no service password-encryption
!
hostname R2
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
no ip domain lookup
ip host R1 ABCD:1:1:1::1
ip host R2 ABCD:1:1:3::1
ip host R3 ABCD:1:1:5::1
ip host R4 ABCD:1:1:6::1
ip cef
ipv6 unicast-routing
ipv6 dhcp pool LAN2
 address prefix ABCD:1:1:3::/64
 dns-server ABCD:3::F0
 domain-name redes2.elpoli.edu.co
!
ipv6 cef
multilink bundle-name authenticated
!
cts logging verbose
!
!
license udi pid CISCO1941/K9 sn FJC2052L0PM
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
 no ip address
 duplex auto
 speed auto
 ipv6 address ABCD:1:1:3::1/64
 ipv6 enable
 ipv6 nd managed-config-flag
 ipv6 eigrp 32000
 ipv6 dhcp server LAN2
!
interface GigabitEthernet0/1
 no ip address
 shutdown
 duplex auto
 speed auto
!
interface Serial0/0/0
 bandwidth 64
 no ip address
 encapsulation ppp
 ipv6 address ABCD:1:1:2::2/64
 ipv6 enable
 ipv6 eigrp 32000
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
ipv6 router eigrp 32000
 eigrp router-id 2.2.2.2
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
 login local
 transport input telnet
!
scheduler allocate 20000 1000
!
end

R2# show ipv6 route
IPv6 Routing Table - default - 8 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 8 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 11 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:5::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:6::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:40::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 11 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:5::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:6::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:40::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 11 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:5::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:6::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:40::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 11 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:5::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:6::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:40::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2# show ipv6 route
IPv6 Routing Table - default - 10 entries
Codes: C - Connected, L - Local, S - Static, U - Per-user Static route
       B - BGP, R - RIP, I1 - ISIS L1, I2 - ISIS L2
       IA - ISIS interarea, IS - ISIS summary, D - EIGRP, EX - EIGRP external
       ND - ND Default, NDp - ND Prefix, DCE - Destination, NDr - Redirect
       O - OSPF Intra, OI - OSPF Inter, OE1 - OSPF ext 1, OE2 - OSPF ext 2
       ON1 - OSPF NSSA ext 1, ON2 - OSPF NSSA ext 2, a - Application
D   2001:DB8:13::/64 [90/41026560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:1::/64 [90/40514560]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
C   ABCD:1:1:2::/64 [0/0]
     via Serial0/0/0, directly connected
L   ABCD:1:1:2::2/128 [0/0]
     via Serial0/0/0, receive
C   ABCD:1:1:3::/64 [0/0]
     via GigabitEthernet0/0, directly connected
L   ABCD:1:1:3::1/128 [0/0]
     via GigabitEthernet0/0, receive
D   ABCD:1:1:4::/64 [90/41024000]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:5::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
D   ABCD:1:1:6::/64 [90/41029120]
     via FE80::2A2:EEFF:FE2B:D6C0, Serial0/0/0
L   FF00::/8 [0/0]
     via Null0, receive
R2#
%SYS-5-CONFIG_I: Configured from console by cisco on vty0 (ABCD:1:1:3:1D8D:2E78:9F61:BBAC)
