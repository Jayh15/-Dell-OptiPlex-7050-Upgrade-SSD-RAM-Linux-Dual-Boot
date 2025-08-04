# Dell-OptiPlex-7050-Upgrade-SSD-RAM-Linux-Dual-Boot
This project documents the hardware upgrades and dual-boot OS installation I performed on my Dell OptiPlex 7050 Midsize Tower to enhance its performance for general use and cybersecurity tasks.


🛠️ Hardware Specs (Before)
Component	Details
CPU	Intel Core i5-7500
RAM	8GB DDR4 2666 MHz (1 stick)
Storage	100GB HDD
OS	Windows 11 Pro (single boot)

🔧 Upgrades Performed
✅ RAM Upgrade
New RAM Installed:
2×8GB Timetec DDR4 2666 MHz, for a total of 24GB.

Steps Taken:

Opened the case and grounded myself.

Verified 4 RAM slots (2 black, 2 white).

Left existing 8GB stick in place (black slot).

Installed new sticks in the remaining white slots to ensure dual-channel pairing.

Verified seating and locking tabs snapped in.

Booted into BIOS to verify total RAM: ✅ 24GB detected.

✅ SSD + Dual Boot Setup
New Storage Added:
512GB SATA SSD.

Purpose:
Install Linux Mint alongside existing Windows 11 on the HDD for dual booting.

Steps Taken:

Installed SSD in available SATA bay using SATA + power cables.

Booted from a Ventoy USB with Linux Mint ISO.

Chose "Install alongside Windows Boot Manager."

Allocated full SSD to Mint; Windows remains on HDD.

Rebooted and verified GRUB menu shows both OS options.

💻 Final Setup
Component	Details
CPU	Intel Core i5-7500
RAM	24GB DDR4 2666 MHz
Storage	512GB SSD (Linux Mint), 100GB HDD (Win 11)
OS	Dual Boot: Linux Mint + Windows 11

🧪 Use Case: Cybersecurity
This setup is now perfect for:

Running VMs in VirtualBox or QEMU

Pen-testing with BlackArch or Kali in a VM

Using Linux Mint as a stable daily driver

Running Windows-only apps without needing WINE
