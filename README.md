# Python Network Sniffer

This is a simple Python network sniffer that captures and analyzes network packets using raw sockets. The program displays the source and destination IP addresses of each captured packet, along with the IP version and header length.

## Features

- Captures all incoming and outgoing packets on the network interface.
- Displays packet information, including:
  - IP version
  - Internet Header Length (IHL)
  - Source IP address
  - Destination IP address

## Requirements

- Python 3.x
- Operating system: Linux (may require modifications for other OS)
- Elevated privileges to capture packets

## Installation

1. Ensure you have Python installed on your machine. You can check by running:
   ```bash
   python3 --version
## Usage
   sudo python3 sniffer.py
   
## Important Notes

- **This program requires root or administrative privileges to run due to the use of raw sockets.**
- **Ensure that you have permission to capture network traffic on the network you are monitoring, as unauthorized packet sniffing may be illegal.**


  
