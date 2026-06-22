# Lab 03 - DNS Analysis

## Objective

Use Wireshark to identify and analyze DNS queries and responses generated during web browsing.

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

Opened Wireshark and started a packet capture on the active Wi-Fi adapter.

### Step 2 - Generate DNS Traffic

Visited websites including:

- google.com
- github.com
- tryhackme.com

### Step 3 - Stop Packet Capture

Stopped the capture after sufficient traffic was collected.

### Step 4 - Apply DNS Filter

Used the following display filter:

dns

### Step 5 - Examine DNS Packets

Reviewed DNS queries and responses generated during website access.

---

## Skills Practiced

- DNS Analysis
- Packet Filtering
- Protocol Identification
- Network Traffic Investigation
- Wireshark Navigation

---

## Key Concepts

### What is DNS?

DNS (Domain Name System) translates human-readable domain names into IP addresses.

Example:

google.com
↓
142.250.x.x

Without DNS, users would need to remember IP addresses instead of website names.

---

## Observations

Observed DNS traffic containing:

- DNS Queries
- DNS Responses
- Domain Name Lookups
- IPv4 and/or IPv6 Address Resolution

Example Activities:

- Browser requests domain information.
- DNS server responds with the appropriate IP address.
- Browser connects to the destination server.

---

## What I Learned

DNS acts as the Internet's directory service.

Every time a user visits a website, DNS is typically used to locate the destination server.

Wireshark allows analysts to observe these requests and responses in real time.

---

## Cybersecurity Relevance

DNS analysis is commonly used to:

- Investigate suspicious domains
- Detect malware communications
- Troubleshoot connectivity problems
- Perform incident response investigations
- Support digital forensic analysis

---

## Safety Considerations

- Only analyze traffic captured from systems and networks you own or are authorized to investigate.
- Follow privacy and organizational policies.

---

## Result

Successfully identified and analyzed DNS traffic using Wireshark.

Observed how domain names are translated into IP addresses through DNS queries and responses.

Status: Completed ✅
## Example DNS Query Observed

Domain:

google.com

Protocol:

DNS

Activity:

Standard DNS Query and Response

Purpose:

Resolve a domain name into an IP address for network communication.
