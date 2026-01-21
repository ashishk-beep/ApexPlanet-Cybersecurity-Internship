# Networking Basics

Networking fundamentals are essential in cybersecurity because most
attacks and defenses occur over networks. Understanding how data moves
between systems helps in identifying vulnerabilities, analyzing traffic,
and securing communication channels.

---

## OSI Model

The OSI (Open Systems Interconnection) model explains how data is
transmitted from one system to another in a layered approach. Each layer
has a specific function.

### OSI Layers
- **Physical** – Transmission of raw data through hardware
- **Data Link** – MAC addressing and error detection
- **Network** – Logical addressing and routing (IP)
- **Transport** – End-to-end communication (TCP/UDP)
- **Session** – Session management between systems
- **Presentation** – Data formatting, compression, encryption
- **Application** – User-facing services (HTTP, FTP, DNS)

The OSI model helps in troubleshooting and understanding where network
issues or attacks occur.

---

## TCP/IP Model

The TCP/IP model is the practical networking model used on the internet.
It is simpler than the OSI model and focuses on real-world
communication.

### TCP/IP Layers
- **Application** – HTTP, HTTPS, FTP, DNS
- **Transport** – TCP and UDP
- **Internet** – IP addressing and routing
- **Network Access** – Physical network communication

---

## TCP vs UDP

- **TCP (Transmission Control Protocol)**
  - Connection-oriented
  - Reliable and ordered data delivery
  - Used for HTTP, HTTPS, FTP

- **UDP (User Datagram Protocol)**
  - Connectionless
  - Faster but less reliable
  - Used for DNS, streaming, VoIP

---

## DNS (Domain Name System)

DNS translates human-readable domain names into IP addresses so that
systems can locate each other on a network.

Example:
- `google.com` → IP address

DNS is critical for internet communication and is often targeted in
attacks such as DNS spoofing and poisoning.

---

## HTTP and HTTPS

HTTP and HTTPS are protocols used for web communication.

- **HTTP**
  - Transfers data in plain text
  - Vulnerable to interception

- **HTTPS**
  - Uses SSL/TLS encryption
  - Protects data confidentiality and integrity

HTTPS is essential for secure web applications and user data protection.

---

## IP Addressing

IP addresses uniquely identify devices on a network.

### IPv4 Address Example
- `192.168.1.10`

### Private IP Ranges
- `10.0.0.0 – 10.255.255.255`
- `172.16.0.0 – 172.31.255.255`
- `192.168.0.0 – 192.168.255.255`

---

## NAT (Network Address Translation)

NAT allows multiple devices on a private network to share a single
public IP address.

### Purpose of NAT
- Conserves public IP addresses
- Adds a basic layer of security
- Enables internal devices to access the internet

---

## Importance of Networking in Cybersecurity

- Helps analyze network traffic
- Assists in identifying open ports and services
- Enables detection of malicious activity
- Supports secure network design and defense

---

## Summary

Understanding networking basics such as OSI and TCP/IP models, DNS,
HTTP/HTTPS, IP addressing, and NAT provides a strong foundation for
network analysis, security testing, and defensive cybersecurity
operations.
