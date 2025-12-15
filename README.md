# 🔥 Task 4: Setup and Use a Firewall on Windows

## **Objective**
Configure and test basic firewall rules to allow or block traffic on a Windows system.

---

## **Tools Used**
- Windows Defender Firewall (built-in)
- Command Prompt / Telnet Client

---

## **Steps Performed**

### **1. Open Firewall Configuration Tool**
- Press **Win + R**, type `wf.msc`, and press **Enter**  
- Windows Defender Firewall with Advanced Security opens

### **2. List Current Firewall Rules**
- Click **Inbound Rules**  
- Scroll through the rules to see existing configurations  

### **3. Add a Rule to Block Inbound Traffic (Port 23 – Telnet)**
1. Click **Inbound Rules → New Rule → Port → TCP → Specific local ports → 23 → Block the connection → Apply to Domain/Private/Public → Name the rule: "Block Telnet Port 23" → Finish**  
2. Confirm the rule is **Enabled**

**## 4.Task Outcome**
- Blocked inbound traffic on **port 23 (Telnet)** successfully.  
- Verified using `telnet localhost 23` → connection failed, proving the rule worked.  
- Restored the firewall to its original state by removing the test rule.

### **5. Test the Rule**
1. Open **Command Prompt**  
2. Run:
```cmd
telnet localhost 23

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/75b0abc0-b039-4c25-817e-a7c85a586345" />


