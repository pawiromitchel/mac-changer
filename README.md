# py-mac-changer

This project was made while doing a course in Python for Ethical Hacking.

## Requirements
- Kali Linux 2019
- Python2.7

NOTE: Not tested on other linux flavors or higher python versions

## Usage
The script needs 2 arguments
```
  -i INTERFACE, --interface=INTERFACE
                        Interface to change the MAC Address
  -m NEW_MAC, --mac=NEW_MAC
                        New MAC Address
```

Example
```
python mac_changer.py --interface eth0 --mac 08:00:27:a9:bc:78
```

Output
```
[i] Current MAC: 08:00:27:a9:bc:75
[+] MAC address was succesfully changed to 08:00:27:a9:bc:78
```
