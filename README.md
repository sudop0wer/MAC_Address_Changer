# MAC_Address_Changer

A simple Python script to change the MAC address of a specified network interface on Linux systems. This tool is useful for enhancing privacy, testing, and bypassing network restrictions.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Acknowledgements](#acknowledgements)

---

## Overview

This Python script enables users to change the MAC (Media Access Control) address of a network interface on Linux systems. MAC addresses are unique identifiers assigned to network interfaces for communications at the data link layer. Changing your MAC address can help improve privacy, test networks, or bypass certain restrictions.

---

## Features

- **Easy to Use**: Change your MAC address with just a few commands.
- **Privacy Enhancement**: Prevent tracking by regularly changing your MAC address.
- **Network Testing**: Useful for testing network configurations.
- **Bypass Restrictions**: Circumvent MAC address filtering on certain networks.

---

## Requirements

- **Python 3.x**: Make sure Python 3.x is installed on your system.
- **Root Privileges**: The script requires root permissions to execute commands that change the MAC address.

---

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/mac-address-changer.git
    cd mac-address-changer
    ```

2. **Make the Script Executable (Optional):**

    ```bash
    chmod +x mac_address_changer.py
    ```
---

## Usage

To run the script, specify the network interface and the new MAC address you want to set:

```bash
sudo python3 mac_address_changer.py -i <interface> -m <new_mac_address>
```
---

## Options

The script provides the following options for customizing its behavior:

- `-i` or `--interface`: Specify the network interface for which you want to change the MAC address. Examples include `eth0`, `wlan0`, etc.
- `-m` or `--mac`: Define the new MAC address that you want to set. The address should be in the format `00:11:22:33:44:55`.

---

## Example

To use these options, you would run the script with the desired parameters:

    sudo python3 mac_address_changer.py -i eth0 -m 00:11:22:33:44:55

# Acknowledgements

Inspiration for this script came from Zaid Al-Quraishi (Z-Security), who has an amazing Udemy course on Python & Ethical Hacking.
