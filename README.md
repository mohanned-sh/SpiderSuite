<p align="center">
  <img src="img/spidersuite-banner.png" alt="SpiderSuite" width="100%">
</p>

# SpiderSuite

SpiderSuite is an all-in-one wireless networking toolkit designed for Kali Linux.

It combines multiple wireless security utilities into a single interactive terminal application, allowing users to manage common wireless operations from one clean and user-friendly interface.

Whether you need to change your MAC address, scan nearby Wi-Fi networks, perform wireless reconnaissance, or restore your wireless adapter, SpiderSuite provides a simple and organized workflow.

---

# Features

- Interactive terminal interface.
- Animated SpiderSuite banner.
- Wireless interface detection.
- MAC Address Changer.
- Wi-Fi Network Scanner.
- Automatic Monitor Mode support.
- CSV scan report generation.
- Wi-Fi adapter reset utility.
- Automatic NetworkManager recovery.
- Clean and easy-to-use interface.
- Designed specifically for Kali Linux.

---

# Included Tools

## 1. MAC Address Changer

- Detect available interfaces.
- Change MAC address manually.
- Validate MAC address format.
- Restart networking automatically.

---

## 2. Network Scanner

- Enable Monitor Mode automatically.
- Scan nearby wireless networks.
- Save scan results as CSV.
- Compatible with Aircrack-ng Suite.

---

## 3. Deauth Tool

- Select wireless interface.
- Configure target MAC.
- Select wireless channel.
- Choose packet count.
- Launch deauthentication packets.

---

## 4. WiFi Reset

- Reset selected interface.
- Reset all interfaces.
- Restore Managed Mode.
- Restart NetworkManager.

---

# Requirements

Before using SpiderSuite, install the required packages.

```bash
sudo apt update
sudo apt install git python3 aircrack-ng net-tools wireless-tools python3-colorama -y
```

---

# Installation

## Step 1 – Clone Repository

```bash
git clone https://github.com/USERNAME/SpiderSuite.git
```

---

## Step 2 – Enter Project Folder

```bash
cd SpiderSuite
```

---

## Step 3 – Make Script Executable

```bash
chmod +x spider_wifi.py
```

---

## Step 4 – Run

```bash
sudo python3 spider_wifi.py
```

---

# Main Menu

SpiderSuite provides four integrated tools:

```text
1. Change MAC Address
2. Network Scan
3. Deauth Tool
4. Reset WiFi
5. Exit
```

---

# Output

Network scan results are automatically saved inside:

```text
spider_scans/
└── spider_scan_YYYYMMDD_HHMMSS-01.csv
```

---

# Screenshots

<p align="center">
  <img src="img/menu.png" width="90%">
</p>

<p align="center">
  <img src="img/network-scan.png" width="90%">
</p>

<p align="center">
  <img src="img/mac-changer.png" width="90%">
</p>

<p align="center">
  <img src="img/reset-wifi.png" width="90%">
</p>

---

# Notes

- Requires root (sudo) privileges.
- Requires a wireless adapter that supports Monitor Mode.
- Designed and tested on Kali Linux.
- Some features require the Aircrack-ng Suite.
- Scan results are automatically saved for later review.

---

# Disclaimer

This project is intended for educational purposes, cybersecurity training, and authorized security assessments only.

Use this software only on systems and wireless networks that you own or for which you have obtained explicit permission.

Unauthorized use of this tool against third-party networks or devices may violate applicable laws and regulations.

The developer assumes no responsibility for any misuse, illegal activity, or damages resulting from the use of this software.

---

# License

MIT License
