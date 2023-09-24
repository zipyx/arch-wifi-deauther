# Arch-Linux Wi-Fi Deauthenticator

This is a fork of the `wifi-deauther` repo for `arch-linux` installations. For those who don't know. This is simply a
Wi-Fi killer.

### Installation (Arch-OS)

Use the installation script `INSTALL` or download the relevant packages manually.

- **One-liner installation**

```bash
git clone https://github.com/zipyx/arch-wifi-deauther && cd arch-wifi-deauther && chmod +x INSTALL && sudo ./INSTALL
```

- **Manual Install**

Install the sys packages manually.

```bash
aircrack-ng
mdk4
```

Install python packages manually.

```bash
pip install scapy
```

### Instructions

Execute the program manually or if you installed the script using the `INSTALL`, just run `sudo wfk`

```bash
# using python script
sudo python W-Killer.py
```

Using `INSTALLER`, must be run using `sudo`

```bash
sudo wfk
```

### Note

Your wireless card must have **monitor mode** available in order for the script to be used.
The use of two wireless cards is **highly recommended** to avoid errors and complications.
