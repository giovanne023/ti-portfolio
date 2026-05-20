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
