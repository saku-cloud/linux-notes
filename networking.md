# Basic Linux Networking

## 1. ping
Used to check connectivity between systems.

Example:
```bash
ping google.com
```

Purpose:
- Checks internet connection
- Verifies whether a host is reachable

---

## 2. ip a
Displays IP address and network interface information.

Example:
```bash
ip a
```

Purpose:
- Shows system IP address
- Displays network interfaces

---

## 3. hostname
Displays the system hostname.

Example:
```bash
hostname
```

---

## 4. ssh
Used to securely connect to remote Linux systems.

Example:
```bash
ssh user@192.168.1.10
```

Purpose:
- Remote server login
- Secure administration

---

## 5. netstat
Displays network connections and listening ports.

Example:
```bash
netstat -tulnp
```

Purpose:
- Check running services
- Identify open ports

---

## 6. curl
Used to transfer data from servers.

Example:
```bash
curl https://example.com
```

Purpose:
- Test websites and APIs
- Troubleshooting connectivity

---

## 7. wget
Downloads files from the internet.

Example:
```bash
wget https://example.com/file.zip
```

---

# Common Ports

| Port | Service |
|------|----------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 3306 | MySQL |

---

# Basic Networking Troubleshooting

## Check Internet
```bash
ping google.com
```

## Check IP Address
```bash
ip a
```

## Check Open Ports
```bash
netstat -tulnp
```

## Test Website
```bash
curl https://google.com
```