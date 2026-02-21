# 🌐 Fundamental Network Knowledge for Cybersecurity
*A Practical Networking Foundation for Security Professionals*

---

# 🎯 Why Networking Matters in Cybersecurity

You cannot secure what you don’t understand.

Every attack:
- Moves through a network
- Exploits a protocol
- Targets a service
- Manipulates traffic flow

Strong network fundamentals = Strong security intuition.

---

# 📜 Do You Need Network+ or CCNA?

Certifications like:

- CompTIA Network+
- Cisco CCNA

Provide structure, but:

❗ They often go deeper than necessary for entry-level cybersecurity.

Focus first on:
✔ Core concepts  
✔ Traffic flow  
✔ Protocol behavior  
✔ Security impact  

---

# 🧠 1️⃣ OSI Model & Data Flow

Understand:

- 7 OSI layers
- How data moves through layers
- Where attacks occur

| Layer | Example Concern |
|-------|-----------------|
| Application | Web attacks |
| Transport | Port scanning |
| Network | IP spoofing |
| Data Link | ARP poisoning |

If you understand layers, you understand where to defend.

---

# 🌍 2️⃣ Core Network Protocols

## 📦 IP (Internet Protocol)
- Provides addressing
- Handles routing between networks

## 🚦 TCP (Transmission Control Protocol)
- Reliable communication
- Three-way handshake
- Used in HTTPS, SSH, etc.

## 📡 UDP (User Datagram Protocol)
- Faster, connectionless
- Used in DNS, streaming

## 🔔 ICMP
- Error reporting
- Used by `ping`
- Important for troubleshooting

Understanding protocol behavior helps detect anomalies.

---

# 🔢 3️⃣ Important Ports & Services

Know common ports:

| Port | Service |
|------|---------|
| 22 | SSH |
| 23 | Telnet |
| 80 | HTTP |
| 443 | HTTPS |
| 389 | LDAP |
| 161 | SNMP |
| 445 | SMB |
| 3389 | RDP |

Open ports = Potential attack surface.

---

# 🛣 4️⃣ Routing & Switching Basics

Understand:

- How packets move
- What routers do
- What switches do
- MAC addresses
- ARP
- VLANs
- Access Control Lists (ACLs)

## Router
- Connects networks

## Switch
- Connects devices inside a network

## VLAN
- Segments network logically

Segmentation = Reduced attack impact.

---

# 🌎 5️⃣ Public vs Private IP

## Private IP Ranges
- 10.0.0.0/8
- 172.16.0.0/12
- 192.168.0.0/16

Used inside local networks.

## Public IP
- Internet-facing
- Globally routable

Understanding this helps in:
✔ Firewall configuration  
✔ NAT setup  
✔ Exposure analysis  

---

# 🧮 6️⃣ Subnets & DHCP

## Subnetting
- Divides networks
- Controls traffic scope
- Improves security segmentation

## Default Gateway
- Route out of local network

## DHCP
- Automatically assigns IP addresses

Misconfigured DHCP can create vulnerabilities.

---

# 🛡 7️⃣ Network Devices

Know what each does:

| Device | Purpose |
|--------|----------|
| Router | Routes traffic |
| Switch | Internal traffic switching |
| Firewall | Traffic filtering |
| Access Point | Wireless connectivity |

Security professionals must know:
- Where to enforce policy
- Where to monitor traffic
- Where attackers may pivot

---

# 🔐 8️⃣ Secure Communication Protocols

Understand:

- SSL/TLS (Encryption)
- VPN (Encrypted tunnels)
- Proxy servers
- Remote management protocols (SSH, RDP)
- LDAP (Authentication directory)

Encryption protects:
✔ Confidentiality  
✔ Integrity  

---

# 🔑 9️⃣ Authentication Protocols

Examples:

- LDAP
- Kerberos
- Active Directory authentication

Identity is the new perimeter.

---

# 🚨 🔟 Common Network Attacks

Know how these work:

## DDoS
Overwhelms system with traffic.

## ARP Poisoning
Manipulates MAC-IP mapping.

## Man-in-the-Middle (MITM)
Intercepts communication.

## Spoofing
Fakes identity (IP, MAC, DNS).

Understanding attacks helps you detect anomalies.

---

# 🧰 1️⃣1️⃣ Basic Networking Commands

Practice using:

```
ipconfig
ifconfig
ping
tracert / traceroute
netstat
route
```

These help you:

✔ Inspect IP info  
✔ Test connectivity  
✔ Analyze routing  
✔ View open connections  

Hands-on practice builds intuition.

---

# 🧠 What You REALLY Need for Cybersecurity

Not deep CCNA routing configs.

But:

✔ Understand how packets move  
✔ Know how services communicate  
✔ Recognize abnormal behavior  
✔ Understand attack vectors  
✔ Know what "normal" looks like  

Security = Detecting abnormal patterns.

---

# 🏆 Final Advice

Focus on:

- Practical understanding
- Protocol behavior
- Traffic analysis
- Attack surface awareness

Networking is not optional in cybersecurity.

It is foundational.

---

# 🔑 Key Takeaways

✔ Learn OSI model  
✔ Understand TCP/IP  
✔ Memorize common ports  
✔ Know routing & VLAN basics  
✔ Understand private vs public IP  
✔ Learn common attacks  
✔ Practice networking commands  

Master networking → Everything else becomes easier.

---

**✍️ Notes By Abhishek (Ez Abyss)**
