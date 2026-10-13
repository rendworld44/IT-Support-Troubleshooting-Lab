# IT Support Troubleshooting Lab 🛠️

A hands-on IT support project demonstrating practical troubleshooting skills in a Windows 10 virtual environment.

The project covers common technical support scenarios involving system performance, DNS connectivity, and Windows services.

## Tools & Technologies

- Windows 10
- Oracle VirtualBox
- Task Manager
- Command Prompt (CMD)
- Windows Services

---

## Lab 01 — Windows Performance Troubleshooting

### Issue
A Windows computer was experiencing slow system performance and high resource usage.

### Troubleshooting
- Opened Task Manager.
- Checked CPU, Memory, and Disk usage.
- Identified a non-essential application consuming significant system resources.
- Ended the unnecessary application process.
- Monitored system resources after troubleshooting.

### Result
System resource usage decreased after closing the unnecessary application.

---
### Screenshots

**Before — High Resource Usage**

![Lab 01 Before](https://github.com/rendworld44/IT-Support-Troubleshooting-Lab/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202026-10-12%20230813.png?raw=true)

**After — Resource Usage Improved**

![Lab 01 After](https://github.com/rendworld44/IT-Support-Troubleshooting-Lab/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202026-10-12%20231051.png?raw=true)
## Lab 02 — DNS Connectivity Troubleshooting

### Issue
A Windows system was unable to access websites due to a name-resolution problem.

### Troubleshooting
- Tested network connectivity using Windows command-line tools.
- Confirmed that basic network connectivity was working.
- Identified a DNS name-resolution issue.
- Corrected the DNS configuration.
- Verified successful domain-name resolution.

### Result
Network connectivity and domain-name resolution were successfully restored.

> Network configuration details are intentionally excluded from this public repository.

---

## Lab 03 — Print Spooler Troubleshooting

### Issue
A Windows system was unable to process printing tasks.

### Troubleshooting
- Opened Windows Services using `services.msc`.
- Located the Print Spooler service.
- Identified that the service was stopped.
- Started the Print Spooler service.
- Verified that the service status changed to Running.
- Confirmed the Startup Type was set to Automatic.

### Result
The Print Spooler service was successfully restored and configured to start automatically.

---
### Screenshots

**Before — Print Spooler Stopped**

![Lab 03 Before](https://github.com/rendworld44/IT-Support-Troubleshooting-Lab/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202026-10-13%20181236.png?raw=true)

**After — Print Spooler Running**

![Lab 03 After](https://github.com/rendworld44/IT-Support-Troubleshooting-Lab/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202026-10-13%20181503.png?raw=true)

## Skills Demonstrated

- Windows Troubleshooting
- System Performance Analysis
- Network Troubleshooting
- DNS Troubleshooting
- Windows Services Management
- Command-Line Diagnostics
- Technical Problem Solving
