# Nmap Network Scanning Assignment

## Student Information

- Name: Andrew
- Course: Cybersecurity
- Tool Used: Nmap
- Operating System: Kali Linux

---

## Task 1: Local Network Discovery

### Command Used

```bash
nmap -sn 192.168.38.0/24 > scan_results.txt
```

### Summary

The local subnet 192.168.38.0/24 was scanned using Nmap host discovery. The scan identified 4 active hosts on the network.

Active Hosts:

- 192.168.38.1
- 192.168.38.2
- 192.168.38.129
- 192.168.38.254

---

## Task 2: Reconnaissance Phase

Instagram is a widely used social media application that allows users to share photos, videos, and messages. During the reconnaissance phase, a penetration tester may gather publicly available information such as domains, subdomains, APIs, login pages, technology stack, and third-party integrations. The tester may also identify publicly exposed user information and application endpoints to better understand the application's attack surface. This information helps security professionals understand how the application is structured before performing authorized security assessments.

---

## Task 3: Port Scan

### Command Used

```bash
nmap -sS instagram.com
```

### Open Ports Found

| Port | State | Service |
|------|--------|---------|
| 80/tcp | Open | HTTP |
| 443/tcp | Open | HTTPS |

---

## Task 4: Network Assessment Report

A network discovery scan was conducted on the subnet 192.168.38.0/24 using Nmap. The scan identified four active hosts on the network. A port scan was also performed to identify exposed services on the target system. The scan revealed open ports 80 (HTTP) and 443 (HTTPS), indicating that web services are accessible. Exposed services may increase the attack surface if not properly secured and monitored. Regular patching, service reviews, and access control measures are recommended to reduce potential security risks.

---

## Conclusion

The assignment demonstrated the use of Nmap for host discovery and basic port scanning. Four active hosts were discovered on the local network, and two open web service ports were identified on the target system. This exercise provided practical experience in network reconnaissance and information gathering.
