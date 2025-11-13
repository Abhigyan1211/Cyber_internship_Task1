# Cyber_internship_Task1
nmap scanning task
**Name:** RAI ABHIGYAN 
**Task:** Scan local network for open ports using Nmap  
**Date:** 13-11-2025

# Tools used
- Nmap

# Steps performed
1. Determined local IP range: ` 192.168.0.101`.
2. Ran Nmap TCP SYN scan:
   `nmap -sS  192.168.0.101 -oN result.txt`
3. Saved results in `result.txt`.
4. Captured screenshots .
5. Uploaded files to this repository.

# Files in this repo
- `result.txt` — Nmap text output
- `Screenshot 2025-11-13` — screenshots of terminal
- `README.md` — this file

# Observations
- ` 192.168.0.101` — `135/tcp open msrpc` (Microsoft RPC)
- ` 192.168.0.101` — `139/tcp open netbios-ssn` (NetBIOS Session Service)
- ` 192.168.0.101` — `445/tcp open microsoft-ds` (Microsoft-DS)

