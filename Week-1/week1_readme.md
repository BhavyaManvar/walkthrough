# 📅 Week 1 — CTF & Pentesting Learning Journal

## 📘 Summary of This Week
A quick overview of what I focused on this week:
- Type of labs (HackTheBox Academy)
- Main topics covered
- General learning direction

---

## 🔍 Concepts Practiced
This week, I worked on strengthening the following areas:

- Example:
  - XSS (Reflected, DOM, Stored)
  - SQL Injection (Union-Based, Error-Based)
  - CSRF
  - Authentication & Session Flaws
  - Directory Enumeration
  - SSRF basics
  - Linux/Windows privilege escalation

---

## 🧰 Tools & Commands Used

- Burp Suite (manual testing, repeater, intruder)
- Nmap advanced scans
- SQLMap custom payloads
- FFUF/Gobuster
- Custom Python scripts  
- Recon tools

---

### **Case Study 1 — Parameter-Based XSS Discovery**
This week I worked on multiple labs involving user-controlled parameters.
One scenario taught me to test not just visible inputs, but also:
hidden parameters
unused fields
debug endpoints
This improved my enumeration approach and taught me the importance of exploring all input channels, not only the obvious ones.

### **Case Study 2 — Authentication Logic Issue**
One lab strengthened my understanding of how login pages handle validation.
By experimenting with edge-case values and analyzing request flow, I discovered how inconsistent backend checks can expose bypass opportunities.
This taught me to pay attention to response differences and error messages, which helps in real bug bounty hunting.

### **Case Study 3 — Server-Side Misconfiguration Insight**
A challenge introduced me to misconfigured endpoints that revealed metadata unintentionally.
This reinforced the importance of checking:
/backup/ directories
/debug/ endpoints
outdated files
This matches real-world scenarios I might find on live targets.
---

## 🧠 Mistakes & Improvements

- I learned to enumerate parameters more systematically  
- I improved my payload crafting  
- I stopped skipping recon  
- I took better notes for each lab  
- I automated repetitive steps  

---

## 🎯 Goals for Next Week
- Complete 3–5 new labs  
- Start practicing SSRF and file upload attacks  
- Work on red-team privilege escalation  
- Add 2 new features to PortStorm or AutoVulnScanner  
- Prepare LinkedIn weekly post  

---

