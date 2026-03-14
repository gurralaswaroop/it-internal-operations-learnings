# BIOS / UEFI in Laptops

## Introduction

BIOS (Basic Input Output System) or UEFI (Unified Extensible Firmware Interface) is firmware stored on the motherboard. It initializes hardware components when the laptop powers on and loads the operating system.

Modern laptops mostly use **UEFI**, which replaces the traditional BIOS.

---

## Responsibilities of BIOS / UEFI

- Initializes CPU, RAM, and chipset during startup
- Detects storage devices such as SSD and HDD
- Loads the bootloader to start the operating system
- Controls hardware-level settings
- Performs hardware diagnostics during POST

---

## POST (Power On Self Test)

POST is the first process executed when the laptop powers on.

It checks:

- RAM functionality
- CPU availability
- Storage device detection
- Keyboard and input devices
- Display initialization

If a failure occurs, the system may produce **beep codes or LED indicators**.

---

## Accessing BIOS / UEFI

Common keys used during boot:
<imgae https://i.dell.com/sites/csimages/App-Merchandizing_esupport_flatcontent_Images/all/bios-system-information-optiplex-7050.png" />

| Manufacturer | Key |
|---------------|------|
| Dell | F2 |
| HP | F10 |
| Lenovo | F1 / F2 |

---

## Common BIOS Settings

### Boot Order
Controls which device loads the operating system.

Example boot sequence:

1. SSD
2. USB Drive
3. Network Boot

---

### Secure Boot

Security feature that prevents unauthorized operating systems from booting.

---

### Virtualization

Enables CPU virtualization technology for running virtual machines.

Examples:

- Intel VT-x
- AMD-V

---

### Hardware Monitoring

Displays system hardware status such as:

- CPU temperature
- Fan speed
- Battery health
- Voltage levels

---

## BIOS Update (Firmware Update)

Updating BIOS can fix:

- hardware compatibility issues
- system stability problems
- security vulnerabilities

⚠️ Important precautions:

- Ensure laptop battery is charged
- Do not interrupt the update
- Download BIOS only from the manufacturer website

---

## Troubleshooting BIOS Issues

### Laptop Not Booting

Possible causes:

- corrupted BIOS firmware
- incorrect boot order
- hardware failure

---

### BIOS Reset

Reset BIOS using:

- BIOS reset option
- removing CMOS battery
- motherboard reset jumper

---

## Conclusion

BIOS / UEFI is critical firmware responsible for hardware initialization and system startup. Understanding BIOS settings helps hardware engineers troubleshoot boot failures and configure hardware correctly.
