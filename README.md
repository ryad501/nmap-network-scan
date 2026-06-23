# Network Scanning with Nmap

A basic lab project from my cybersecurity diploma where I practiced
network scanning and host discovery using Nmap on a virtual machine.

## Goal

Learn how to discover devices on a network, find open ports, and
identify which services are running on them.

## Tools

- Nmap
- Kali Linux (VirtualBox)

## What I did

I set up a target machine inside a virtual lab and ran a few Nmap
scans against it to see what information I could collect.

```bash
# Check if the host is up
nmap 192.168.1.10

# Scan all ports
nmap -p- 192.168.1.10

# Detect service versions
nmap -sV 192.168.1.10
```

## What I learned

- How to read which ports are open or closed.
- The difference between a basic scan and a full port scan.
- That open ports and running services can show possible entry points
  that need to be secured.

## Notes

This was done in an isolated lab environment for learning purposes only.
