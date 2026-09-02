---
# Lab: Inside a Computer System
---

## Inside a Computer System:
### 1-Motherboard:
It connects and allows communication between all components.

### 2-CPU (Central Processing Unit): 
* Executes instructions and platform calculation, often called the processor, is comparable to a part of our brain.
* The CPU connects to the motherboard via the CPU socket.

### 3-RAM (Random Access Memory):
* Stores data temporarily while the computer is running.
* It holds data that the CPU needs quick access to.
* The RAM connects to the motherboard through DIMM (Dual In-Line Memory Module), called slots (RAM slots).
* Modern RAM modules use technologies like DDR5 (Double Data Rate GEN-5) or DDR6 (Double Data Rate GEN-6) for increased speed and performance.
* How does the CPU access RAM?

### CPU "I Need this data" -> Memory Controller -> Memory Channel -> Motherboard traces -> DIMM slots -> RAM "Here is the data"

### 4-Storage (SSD/HDD):
* SSD -> Solid State Drive.
* HDD -> Hard Desk Drive.
* To save data permanently even when powered off.
* HDD -> uses spanning magnetic platters, with limiting performance, low speed, and cost.
* SSD -> uses flash memory with no moving parts, allowing much faster speeds than HDD.
* Storage connects via SATA cables or PCI Express slots.
* The HDD connects to the motherboard via the SATA (Serial Advanced technology Attachment) cables.
* The SATA SSD connects to the motherboard via the SATA (Serial Advanced technology Attachment) cables.
* The NVMe Protocol(Non-Volatile Memory Express)SSD connects to the motherboard through the PCIe(Peripheral Component Interconnect Express).

### 5-Network Adapter: 
* Communicate with other computers and networks.
* Network adapters come in wireless and wired variants.
* Network cards typically connect to the motherboard via PCI Express ports.

### 6-Power Supply (PSU):
* To supply electrical power to all components.
* If components need more power than the PSU can provide.
* The PSU takes electrical power from an outlet, then distributes power to the computer's components through various power connectors, such as Molex connectors.

### 7-Graphics Card GPU (Graphics Processing Unit): 
* Processing and outputting visual information to display.
* The graphics card receives information from the operating system and programs, then outputs processed visual data to a monitor.
* Graphics cards connect to PCI Express slots on the motherboard.

### 8-Input/Output (I/O):
* To send data to and receive data from the computer.
* Input devices include keyboards, microphones, and scanners.
* Output devices include monitors, printers, and speakers.
* Connectors for these peripherals include USB, HDMI, and DisplayPort.

<img width="800" height="600" alt="Screenshot 2026-09-02 at 11 47 54 PM" src="https://github.com/user-attachments/assets/64d82815-2553-4fb7-97ac-b93d6d25f93e" />

<img width="800" height="600" alt="Screenshot 2026-09-02 at 11 47 24 PM" src="https://github.com/user-attachments/assets/1f82267d-7124-4698-94ec-dc9cee2ba30c" />

---

## What Happens when you Press The Start Button?

### Step 1: Press the Power Button
* A signal is sent to the PSU to allow power to flow.

### Step 2: Firmware starts
* A computer system contains firmware that allows all its components to start up.
* The central system that manages this is called the Unified Extensible Firmware Interface (UEFI).
* Note: We will often see the term BIOS mentioned instead of UEFI. BIOS does the same as UEFI, but has mainly been replaced by UEFI.
* The Basic Input/Output System (BIOS) is a boot firmware that provides runtime services for the operating system (OS).

### Step 3: Power-On Self Test (POST)
* it is time to test if everything is functioning as it should. If something isn't, there will be some alarm signals. 

### Step 4: Select Boot Device
* In our computer system the UEFI holds an ordered list which prioritizes on which device to look first for the boot up routine for the Operating System.

### Step 5: Initiate Bootloader
* This bootloader transfers the Operating System from the selected boot device to the Random Access Memory.
* Once the OS is transferred, the UEFI gives control over the different components to the OS.
* Bootloader: Loads the  operating system into RAM. 

---



