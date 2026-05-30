# Nmap Service Discovery Lab

## Objective
Identify open ports and running services on a local Ubuntu system.

## Tools Used
- Nmap
- Ubuntu Linux VM

## Command Used

```bash
nmap -sV -p- localhost
```

## Results

### Open Ports

| Port | Protocol | Service | Version |
|--------|--------|--------|--------|
| 631 | TCP | IPP | CUPS 2.4 |

## Analysis

The scan identified port 631 as open.

The service running on this port was IPP (Internet Printing Protocol) using CUPS version 2.4.

This service is responsible for printer management and network printing functionality on Linux systems.

## Skills Learned

- Port scanning
- Service enumeration
- Version detection
- Interpreting Nmap results

## Key Takeaway

Open ports expose services. Nmap can identify those services and versions, helping security professionals understand a system's attack surface.
