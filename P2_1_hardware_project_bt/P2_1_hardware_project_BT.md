# P2.1 Computer Hardware presentations 

> **Area name:** Storage Devices (HDD / SSD / NVMe)

> **author:** Bryan L. Tarazona R.

## Table of Contents

- [Introduction](#introduction)

- [Main Functions](#main-functions)
   
    - [How It Works](#how-it-works)
        - [HDD](#hdd-hard-disk-drive)
        - [SSD](#ssd-solid-state-drive)
    - [Types](#there-are-3-types)

- [Key Specifications](#key-specifications)

- [Real-World Examples](#real-world-examples)

    - [SATA](#barracuda-35-2tb-sata-3--seagate)
    - [M.2]

- [References](#references)

- [Kahoot Quiz](#kahoot-quiz)


# Introduction

### What is a Storage Devises?

Storage devices are hardware components used to store data, programs, and the operating system on a computer. Their main role is to save information permanently, even when the computer is turned off.

There rol is **storage information** depense of the tipe (HDD/SDD/NVMe) do it the one or the other way, this three devises are the most used. every one know this devises or at least we just heard this names.

# Main functions 

There are three common types of storage technologies: HDD, SSD, and NVMe SSD. 

The three devices have the same objective, storage information store data permanently (operating system, programs, documents, photos, etc.) and you don't have to care if you turn off your computer, that stored data don’t disappear, for example, the RAM when you turn off you PC loss al the informacion than you have there… this calcification have a name→ volatile memory ( RAM ) and non volatile memory (HDD,SDD,NVMe SSD)

## How It Works

There are several types of storage, and each one saves information in a different way:

### HDD (Hard Disk Drive):
stores data on spinning magnetic platters. A read/write head moves over them to read or write data. It is cheap and offers large capacity, but it is slower and more sensitive to shocks because it has moving parts.

### SSD (Solid-State Drive): 
uses NAND flash memory chips with no moving parts. It is much faster, quieter, and more durable. It can connect through SATA.for the fastest models-> 

- NVMe (PCIe): this are two different things working together, ins this case:
- PCIe (PCI Express): is a high-speed connection, between the SSD and the CPU but depends on the motherboard type , using lanes. These lanes send information in both directions and only 1 lane is a group of wires. SSD usually used 4 lanes (write X4) so the download speed is like ~3,500 to 14,000 MB/s.

**Others:** USB drives, SD cards, optical media, and cloud storage, mostly used for backups and data transport.
### There are 3 types:

**B-key:** Supports SATA and PCIe x2.
**M-key:** Supports PCIe x4 (typically NVMe).
**B+M key:** Can support both SATA and PCIe, but is limited by the host slot.

![Types of Keys]["\Bryan\sisi\P2_1_hardware_project_bt\img\Keys.jpg"]

**NVMe (Non-Volatile Memory Express)** is the communication protocol, the “language” the SSD and the system use to talk over that highway. It was designed specifically for flash memory. 

# Key Specifications

## Comparison table

#### Technical Characteristics of Storage Devices

| Characteristic | HDD | SSD (SATA) | NVMe SSD |
|---|---|---|---|
| **Technology** | Magnetic platters | NAND flash | NAND flash |
| **Sequential speed** | ~150-285 MB/s | ~500-560 MB/s | ~3,500-7,000 MB/s (PCIe 3.0/4.0); up to ~14,500 MB/s (PCIe 5.0) |
| **Access latency** | ~5-10 ms | ~0.05-0.1 ms | ~0.01-0.02 ms |
| **Random operations (IOPS)** | ~75-200 | ~50,000-100,000 | ~500,000-1,500,000+ |
| **Typical capacity** | 500 GB - 24 TB | 120 GB - 4 TB | 250 GB - 4 TB |
| **Interface** | SATA III (6 Gb/s) | SATA III (6 Gb/s) | PCIe x4 (NVMe protocol) |
| **Form factor** | 3.5" or 2.5" | 2.5" (also M.2 SATA) | M.2 (also PCIe card, U.2) |
| **Power consumption (active)** | ~6-12 W (3.5"), ~2-3 W (2.5") | ~2-4 W | ~5-10 W (up to ~11.5 W on PCIe 5.0) |
| **Noise** | Audible (spinning, head movement) | Silent | Silent |
| **Shock resistance** | Low (moving parts) | High | High |
| **Compatibility** | Almost any computer | Almost any computer | Needs an M.2/PCIe slot with NVMe support and UEFI boot support |
| **Price per GB** | Lowest | Medium to high* | Medium to high* |

In October 2026, a 1 TB SATA SSD (Samsung 870 EVO, ~299.80 €) cost more than a 1 TB NVMe SSD (Samsung 990 EVO Plus, ~222.20 €) on PcComponentes. (checked 23/10/2026).

# Real-World Examples

###  BarraCuda 3.5" 2TB SATA 3 — Seagate








["C:\Bryan\sisi\P2_1_hardware_project_bt\img\Keys.jpg"]: "\Bryan\sisi\P2_1_hardware_project_bt\img\Keys.jpg" "Keys"