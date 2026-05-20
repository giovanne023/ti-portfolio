# 🛠️ IT Troubleshooting Guide

## 📌 Description

This project contains common IT support troubleshooting scenarios and step-by-step solutions used for diagnosing and resolving technical issues.

The goal is to demonstrate practical troubleshooting skills commonly used in IT support and help desk environments.

---

# 🌐 Problem 1: No Internet Connection

## Symptoms

- Connected to the network but no internet access
- Websites do not load
- Connectivity issues detected

## Troubleshooting Steps

1. Check network cables or Wi-Fi connection
2. Verify IP configuration

Run:

```cmd
ipconfig
```

3. Test external connectivity:

```cmd
ping 8.8.8.8
```

4. Renew IP configuration:

```cmd
ipconfig /release
ipconfig /renew
```

---

# 🌍 Problem 2: DNS Issues

## Symptoms

- Websites cannot be reached by name
- Internet works with IP addresses only
- Slow or failed name resolution

## Troubleshooting Commands

```cmd
ping google.com
nslookup google.com
ipconfig /flushdns
```

---

# 🖨️ Problem 3: Printer Issues

## Checklist

- Check printer queue
- Restart Print Spooler service
- Verify cable or network connection
- Confirm printer status

---

# 🖥️ Problem 4: Slow Computer Performance

## Checklist

- Open Task Manager
- Check startup programs
- Analyze disk usage
- Run antivirus scan
- Check system resource usage

---

# 🌐 Problem 5: Invalid IP / DHCP Recovery

## Symptoms

- Connection lost
- Invalid IP assigned
- Network unavailable

## Diagnostic Steps

### Initial IP Configuration

![Initial IP](screenshots/Captura%20de%20tela%202026-05-20%20131239.png)

### DHCP Release

After running:

```cmd
ipconfig /release
```

Windows assigned an APIPA address:

```text
169.254.x.x
```

![Released IP](screenshots/Captura%20de%20tela%202026-05-20%20131337.png)

### DHCP Renew

After running:

```cmd
ipconfig /renew
```

The system received a valid IP address again.

![Renewed IP](screenshots/Captura%20de%20tela%202026-05-20%20131520.png)

---

## Resolution

✅ DHCP lease renewed successfully

✅ Network connectivity restored

✅ Valid IP address assigned again

✅ Internet access successfully recovered

---

# 📸 Screenshots

## Network Diagnostic Test

IP configuration and connectivity tests using Command Prompt.

![IP Configuration](screenshots/Captura%20de%20tela%202026-05-20%20123757.png)

![Ping Test](screenshots/Captura%20de%20tela%202026-05-20%20123805.png)

---

# 💡 Skills Demonstrated

- IT troubleshooting
- Network diagnostics
- DHCP troubleshooting
- DNS troubleshooting
- Connectivity testing
- Windows Command Prompt
- Technical documentation
- Help Desk procedures

---

# 👨‍💻 Author

Giovanne Zequi

Technology in Computer Networks Student

GitHub:
https://github.com/giovanne023
