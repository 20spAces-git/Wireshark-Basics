# Lab 04 - ARP Analysis

## Objective

Use Wireshark to identify and analyze ARP traffic and understand how devices locate each other on a local network.

---

## Lab Environment

### Operating System

- Windows 11

### Tools Used

- Wireshark 4.6.6
- Npcap 1.88

### Network Interface

- Wi-Fi Adapter

---

## Procedure

### Step 1 - Start Packet Capture

Opened Wireshark and began capturing traffic on the active network interface.

### Step 2 - Generate ARP Traffic

Generated local network activity while the packet capture was running.

### Step 3 - Stop Packet Capture

Stopped the capture after collecting sufficient network traffic.

### Step 4 - Apply ARP Filter

Used the following display filter:

arp

### Step 5 - Analyze ARP Packets

Reviewed ARP requests and responses observed during the capture.

---

## Skills Practiced

- ARP Analysis
- Protocol Filtering
- Packet Inspection
- Network Troubleshooting
- Wireshark Navigation

---

## Key Concepts

### What is ARP?

ARP (Address Resolution Protocol) is used to map an IP address to a MAC address on a local network.

Example:

IP Address:
192.168.1.10

↓

MAC Address:
00:11:22:33:44:55

ARP allows devices to discover the physical hardware address of other devices on the same network.

---

## Observations

ARP traffic typically includes:

- ARP Requests
- ARP Replies

Example:

Who has 192.168.1.1?

Tell 192.168.1.100

Followed by:

192.168.1.1 is at 00:11:22:33:44:55

---

## What I Learned

ARP enables communication between devices on a local network by associating IP addresses with MAC addresses.

Without ARP, devices would not know where to send data on a local network.

Wireshark allows analysts to observe these requests and responses in real time.

---

## Cybersecurity Relevance

ARP analysis can help:

- Troubleshoot network connectivity issues
- Identify network devices
- Detect ARP spoofing attacks
- Investigate suspicious network activity
- Support digital forensic investigations

---

## Safety Considerations

- Only capture and analyze traffic on networks you own or are authorized to investigate.
- Follow privacy and security policies when performing packet analysis.

---

## Result

Successfully identified and analyzed ARP traffic using Wireshark.

Observed how devices use ARP to discover MAC addresses and communicate on a local network.

Status: Completed ✅
