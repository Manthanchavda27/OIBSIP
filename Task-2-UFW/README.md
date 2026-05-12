# Task 2 - Basic Firewall Configuration Using UFW

## Objective
The objective of this task is to configure a basic firewall using UFW (Uncomplicated Firewall) on Kali Linux. The firewall is configured to allow SSH traffic and deny HTTP traffic.

---

## Tool Used
- UFW (Uncomplicated Firewall)
- Kali Linux

---

## Steps Performed

### 1. Checked UFW Status

```bash
sudo ufw status verbose
```

---

### 2. Allowed SSH Traffic

```bash
sudo ufw allow ssh
```

OR

```bash
sudo ufw allow 22
```

SSH traffic was allowed so remote administration can work properly.

---

### 3. Denied HTTP Traffic

```bash
sudo ufw deny 80
```

HTTP traffic was blocked to prevent unsecured web access.

---

### 4. Enabled UFW Firewall

```bash
sudo ufw enable
```

This activated the firewall and applied all configured rules.

---

### 5. Verified Firewall Rules

```bash
sudo ufw status numbered
```

The output confirmed:
- SSH traffic is allowed
- HTTP traffic is denied

---

## Configuration Script

The firewall configuration commands are stored inside:

```text
ufw_configuration.sh
```

---

## Screenshots

Screenshots of the firewall status and configured rules are included inside the screenshots folder.

---

## Conclusion

This task demonstrated how to configure a basic firewall using UFW in Kali Linux. Proper firewall configuration helps improve system security by controlling incoming and outgoing network traffic.
