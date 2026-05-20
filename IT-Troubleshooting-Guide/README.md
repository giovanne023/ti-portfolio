# 🛠️ IT Troubleshooting Guide

## 📌 Description

This project contains common IT support troubleshooting scenarios and step-by-step solutions.

---

## 🌐 Problem 1: No Internet Connection

### Symptoms

- Connected to network but no internet
- Websites do not load

### Steps

1. Check cables or Wi-Fi connection
2. Verify IP configuration
3. Run:

```cmd
ipconfig
```

4. Test connectivity:

```cmd
ping 8.8.8.8
```

5. Renew IP:

```cmd
ipconfig /release
ipconfig /renew
```

---

## 🌍 Problem 2: DNS Issues

Commands:

```cmd
ping google.com
nslookup google.com
ipconfig /flushdns
```

---

## 🖨️ Problem 3: Printer Issues

Checklist:

- Check printer queue
- Restart Print Spooler
- Verify connection

---

## 🖥️ Problem 4: Slow Computer

Checklist:

- Task Manager
- Startup programs
- Disk usage
- Antivirus scan

---

## 👨‍💻 Author

Giovanne Zequi

---

## 📸 Screenshots

### Network Diagnostic Test

IP configuration and connectivity tests using Command Prompt.

![IP Configuration](screenshots/Captura%20de%20tela%202026-05-20%20123757.png)

![Ping Test](screenshots/Captura%20de%20tela%202026-05-20%20123805.png)

---

## Results

✔ Network connection active

✔ DNS working correctly

✔ External connectivity verified

✔ Packet loss: 0%

---

# 🌐 Problem 2: Invalid IP / DHCP Recovery

## Symptoms

- Connection lost
- Invalid IP assigned
- Network unavailable

## Diagnostic Steps

### Initial IP

![Initial IP](capturas%20de%20tela/Captura%20de%20tela%202026-05-20%20131239.png)

### DHCP Released

After running:

```cmd
ipconfig /release
```

Windows assigned an APIPA address:

169.254.x.x

![Released IP](capturas%20de%20tela/Captura%20de%20tela%202026-05-20%20131337.png)

### DHCP Renew

After running:

```cmd
ipconfig /renew
```

The valid address returned.

![Renewed IP](capturas%20de%20tela/Captura%20de%20tela%202026-05-20%20131520.png)

## Resolution

✔ DHCP lease renewed successfully  
✔ Network connectivity restored  
✔ Valid IP address assigned again
