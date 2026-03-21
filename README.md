# Proxmox Homelab — Hardware Recovery & Server Build

## Overview
This project started with a dead, liquid-damaged PC (Intel Pentium Gold G2020 - 2GB of ddr3 ram) 
and ended with a fully functional production homelab. No off-the-shelf server — 
everything was diagnosed, repaired, and fabricated by hand.

## Hardware
- Intel Pentium Gold G2020
- Diagnosed and repaired liquid damage
- Destroyed power system fully rewired
- Kill switch added to power circuit
- Custom control panel fabricated — indicator LEDs and switches mounted on drilled chassis

## Software Stack
- Proxmox VE — Type 1 hypervisor
- pfSense VM — firewall and router with QoS bandwidth control per device using qband
- TrueNAS — containerized NAS with ZFS storage
- Administered entirely via SSH

## What I learned
- Hardware fault diagnosis on water-damaged boards
- Power circuit design and rewiring
- Proxmox VE setup and VM/container management
- pfSense firewall rules and QoS configuration
- TrueNAS ZFS pool setup and management
-  Linux server administration

## Documentation
- Build photos
- Wiring diagrams
- Control panel fabrication
- Software configuration notes
