# Windows Firewall Configuration – Task 4

## Objective
The objective of this task was to configure a firewall on Windows to control inbound network traffic by allowing or blocking specific ports, and to verify that the configuration works as expected.

---

## Overview
This task demonstrates the use of Windows Defender Firewall to secure a system by controlling access to network services. A specific port (Port 23, commonly used by Telnet) was blocked to prevent insecure connections, and the functionality of the firewall rule was verified. After testing, the system was restored to its original state.

---

## Tools Used
- Windows Defender Firewall (built-in)
- Command Prompt / Telnet Client

---

## Task Summary
- The firewall configuration tool was opened to review current inbound rules.  
- A new firewall rule was created to block inbound traffic on **Port 23**.  
- The functionality of the rule was tested by attempting to connect to the blocked port; the connection failed, confirming that the firewall rule was effective.  
- After testing, the firewall rule was removed to restore the system to its original configuration.  

---

## Outcome
- The firewall successfully blocked inbound traffic on the targeted port.  
- The system remained secure while other services continued to operate normally.  
- The task reinforced understanding of firewall management, traffic filtering, and basic network security controls.  

---

## Final Output
*Screenshot of the Telnet test showing blocked port 23 goes here.*
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da1d66a7-b8e7-4cb7-919c-d0d4600b580c" />

