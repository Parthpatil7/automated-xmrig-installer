# XMRig Setup Script

A bash script to automate the installation, build, and configuration of the XMRig cryptocurrency miner on Ubuntu. This script simplifies the setup process, ensuring you can start mining Monero quickly and efficiently.

---

## Features

- Installs all required dependencies for XMRig.
- Clones the official XMRig repository from GitHub.
- Builds and compiles XMRig with optimized settings.
- Configures XMRig to run automatically at system startup using `systemd`(using root permissions).
- Enables background execution for continuous mining.

---

## Prerequisites

- An Ubuntu-based operating system (tested on Ubuntu 20.04 and later).
- Root/sudo privileges.
- Internet connection to download dependencies and the XMRig source code.

---

## Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Parthpatil7/automated-xmrig-installer.git
   cd automated-xmrig-installer

2. **Make the script executable**
   ```bash
   chmod +x setup_xmr.sh

3. **Execute the script**
   ```bash
   ./script.sh

4. **Verify startup configuration**
   ```bash
   sudo systemctl status xmrig.service

