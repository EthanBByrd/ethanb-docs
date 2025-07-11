# Wireshark

This file will be used to document my knowledge, skills, and things I learn along the way in Wireshark.

[Wire Shark Blog Post 008](https://github.com/EthanBByrd/ethanb-docs/blob/main/blogs/008%20Wireshark.md) 

- This is one of my daily blog posts, just documenting some general knowledge of IT and Cybersecurity tech, and I wrote one on wireshark, what it is and how it is used to this day.

## What is Wireshark
At its core, Wireshark serves as a Network protocol analzer. Letting you capture and look at data packets that are traveling across the network in real time.

## First opening Wireshark
When you first open Wireshark you will be met with a list of different network interfaces on your system, such as, Wi-Fi, Ethernet, Loopback, or different adapters. You will notice a 'sparkline' to the side of each, which serves as a real time representation of packet activity on each interface. A flat line or no line means no traffic is being captured this way, but a active heartbeat like line means there is solid traffic actitivty. Just to start off, we will select Wi-Fi.

## Getting Started
After selecting Wi-FI you may get a little overwhelmed, but we will fix that soon. What you are seeing right now is every bit of traffic and communication on that Wi-Fi and if you are looking at your home wifi, apartment wifi or company wifi, there will be a LOT of traffic.

## What Are You Looking At?

Each line you see represents a **packet**—a small chunk of data sent across the network. Each packet will display:

- **No.** – Packet number in the capture sequence
- **Time** – Time elapsed since capture began
- **Source** – Where the packet came from (IP address or hostname)
- **Destination** – Where the packet is going (IP address or hostname)
- **Protocol** – What kind of traffic (e.g., TCP, UDP, DNS, HTTP, TLS, etc.)
- **Length** – Size of the packet in bytes
- **Info** – A summary of what’s inside the packet

You can click on any line to open a detailed view of the packet:
1. The top pane shows the raw packet list (timeline).
2. The middle pane shows the packet details (protocol layers).
3. The bottom pane shows the raw bytes (hex + ASCII).

It's okay if you do not know what any of this means, we will get into it later.

---

## Take some time
Take some time and let this run for a bit, watch it, open some random packets and see if you can make anything out of them. We will get into other filters and what to look for in each packet in later documentation.
