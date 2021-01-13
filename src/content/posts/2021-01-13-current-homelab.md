---
template: blog-post
title: Current Homelab
slug: /homelab
date: 2021-01-13 11:37
description: homelab supermicro
---
## Main Rig

Dell Precision T5610 Workstation

OS: 

Windows 10 Pro 64 Bit

CPU: 

2x [Intel Xeon CPU E5-2648L v2 ](https://www.cpu-world.com/CPUs/Xeon/Intel-Xeon%20E5-2648L%20v2.html)

RAM: 

44 GB DDR3 ECC

HDD: 

3x 3 TB SAS HDD

1x  120 GB SATA SSD

1x 240 GB SATA SSD

HBA / RAID card:

LSI SAS9217-8i - Flashed to IT mode

\-------------------------------------

## Server Rack Setup

A Supermicro heavy build in my DELL server rack.

The 2U Unraid server is connected to the 4U JBOD with 45 3.5" HDD bays via external SAS

\-----------

Supermicro 2U Server

OS:

UNRAID Pro

Chassis: 

SuperChassis 829BTQ-R920WB

CPU:

2x [Intel Xeon CPU E5-2648L v2 ](https://www.cpu-world.com/CPUs/Xeon/Intel-Xeon%20E5-2648L%20v2.html)

RAM:

100+ GB DDR3 ECC

HDD:

4x 2 TB SAS HDD

4x 120 GB SATA SSD (cache / unassigned devices)

GPU:

Quadro M2000 4 GB

HBA / RAID card:

LSI SAS9217-8i - Flashed to IT mode

LSI SAS9200-16e - For connecting to 4U JBOD

FANS:

3x Arctic Cooling P8 PWM PST 80mm (from Value Pack)

PSU:

1x PWS-920P-SQ

\------------------

SuperMicro 4U JBOD

Chassis:

SuperChassis 847E26-RJBOD1 (45 3.5" bays)

Motherboard:

Supermicro Power Board for JBOD : JBPWR2 Rev 1.0

HBA / RAID card:

Built-in 4-port External IPASS to Interal IPASS SAS cable

FANS:

5x Arctic Cooling P8 PWM PST 80mm (from Value Pack)

PSU:

1x PWS-920P-SQ

HDD:

30x 2 TB SAS HDD

\-------------------------------------

Networking:

LUXUL AGS-1024 24-Port Unmanaged Gigabit Switch

LUXUL XMS-1024 24-Port Gigabit Ethernet Managed Smart Switch (not used)

\-------------------------------------

## Decommissioned / Not Used

Supermicro 4U Server

Notes: Was a power hungry beast. The amount of bays were nice; but the CPUs ran hot and performance was lack luster.

Chassis: 

CSE-847 - 36 3.5" Bays

Motherboard: 

H8DGU-F 

CPU: 

2x [Opteron 6366 HE](https://www.cpu-world.com/CPUs/Bulldozer/AMD-Opteron%206366%20HE%20-%20OS6366VATGGHK.html) 

RAM: 

16 GB DDR3 ECC

\------------------

Supermicro 2U Server

Notes: The E5-2651 v2 has more cores but consumes more power and a significant more amount of heat.

Chassis: 

SuperChassis 829BTQ-R920WB

CPU:

2x [Intel Xeon E5-2651 v2](https://www.cpu-world.com/CPUs/Xeon/Intel-Xeon%20E5-2651%20v2%20-%20CM8063501521101.html) 

RAM:

16 GB DDR3 ECC