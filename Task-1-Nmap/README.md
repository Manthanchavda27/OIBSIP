# Task 1 - Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap to identify open ports and running services on a target machine.

---

## Tool Used
- Nmap
- Kali Linux

---

## Command Used

```bash
nmap -sV 192.168.1.5
```

---

## Explanation of Command

| Option | Meaning |
|---|---|
| nmap | Network scanning tool |
| -sV | Detect service versions |
| 192.168.1.5 | Target IP address |

---

## Scan Results

The scan identified the following open ports and services:

| Port | Service | Description |
|---|---|---|
| 22 | SSH | Secure remote login |
| 80 | HTTP | Web server |
| 443 | HTTPS | Secure web traffic |

---

## Significance of Open Ports

- Port 22 (SSH) allows remote system administration.
- Port 80 is used for web traffic.
- Port 443 handles encrypted HTTPS communication.

---

## Screenshots

Screenshots of the scan output are included in the screenshots folder.

---

## Conclusion

This task demonstrated how Nmap can be used to identify open ports and services running on a machine. Understanding open ports helps security analysts identify possible attack surfaces and improve network security.
