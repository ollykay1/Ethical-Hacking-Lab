# Scan Summary — portal.kwasu.edu.ng (208.109.188.35)

**Date:** 2025-10-23  
**Target:** portal.kwasu.edu.ng → 208.109.188.35  
**Tools:** ping, netdiscover, nmap (`nmap -sS -sV`)

---

## Ping
- 4 packets transmitted, 4 received — **0% packet loss**  
- RTT min/avg/max = **282.251 / 405.262 / 541.113 ms**

---

## Netdiscover (local)
- Active host found: **172.22.16.1** — **00:15:5d:5b:40:8c** (Microsoft Corporation)

---

## Nmap — Port States (concise)

| Port | State    | Service (detected) |
|------|----------|--------------------|
| 22   | open     | ssh                |
| 25   | open     | smtp-proxy         |
| 53   | open     | domain             |
| 80   | open     | http               |
| 81   | open     | http               |
| 110  | open     | pop3               |
| 143  | open     | imap               |
| 443  | open     | https              |
| 444  | open     | unknown            |
| 465  | open     | smtps              |
| 587  | open     | smtp               |
| 631  | filtered | ipp                |
| 993  | open     | imaps              |
| 995  | open     | pop3s              |
| 3306 | open     | mysql              |

---

## Port Summary
Most of the scanned ports are **open**, indicating active services running on the target host.  
Only **one port (631)** is **filtered**, meaning the packets are being blocked or dropped by a firewall.  
All other ports not shown in the scan output were **closed**, which means they are not currently accepting connections.

---

## Conclusion
The host is reachable and has several open ports for web, mail, SSH, and database services.  
A few ports are filtered for protection, while most closed ports show that the system blocks unauthorized access.  
Regular audits and access restrictions are recommended to maintain a secure configuration.
