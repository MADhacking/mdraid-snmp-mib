mdraid-snmp-mib
===============

There is no standard IETF or IEEE maintained SNMP MIB formalising the structure of MD-RAID array state data. Unfortunately, neither the net-analyzer/net-snmp or sys-fs/mdadm packages provide such a MIB file either.

The snmp-mibs/mdraid-snmp-mib package aims to rectify this by providing the Hacking Networked Solutions MD-RAID-MIB. This MIB file describes a standard format for MD-RAID array state data allowing remote monitoring of array health using SNMP. Information included in the entry for each array includes Array Path, Metadata Version, Array UUID, RAID Level, RAID Layout, and Chunk Size. Boolean indicators allowing the monitoring of Health State, Has Failed Components and Has Available Spares are also included. Finally, gauges representing Total Components, Active Components, Failed Components and Spare Components are provided. 

More information may be found at:

http://www.mad-hacking.net/software/agnostic/snmp-mib/mdraid-snmp-mib/index.xml
