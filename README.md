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

## Skills Demonstrated

- Windows Troubleshooting
- System Performance Analysis
- Network Troubleshooting
- DNS Troubleshooting
- Windows Services Management
- Command-Line Diagnostics
- Technical Problem Solving
