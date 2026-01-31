# 🔎 Reconnaissance & Footprinting Lab Report  
**Name:** Mukhtar Aliyu  
**Course:** Cisco NetAcad Cybersecurity  
**Lab:** Reconnaissance and Footprinting  

---

## 🎯 Objective

The goal of this lab was to perform reconnaissance (information gathering) on a target using open-source intelligence (OSINT) and basic network discovery techniques without directly attacking systems.

---

## 🧠 What is Reconnaissance?

Reconnaissance is the first stage of ethical hacking where publicly available information about a target is collected to understand its network, systems, and potential exposure.

---

## 🖥 Lab Environment

| Component | Description |
|----------|-------------|
| System Used | Kali Linux Virtual Machine |
| Tools Used | WHOIS, nslookup, Nmap, Web search tools |
| Target | Authorized lab target environment |

---

## ⚙️ Steps Performed

### 1️⃣ WHOIS Lookup
- Performed WHOIS queries to gather domain registration information.
- Identified registrar, registration dates, and domain ownership data.

### 2️⃣ DNS Information Gathering
- Used `nslookup` to identify IP addresses related to the domain.
- Checked mail servers and name servers.

### 3️⃣ Network Scanning (Basic)
- Used Nmap to discover live hosts and open ports within the authorized lab scope.

Example command:
nmap -sV 
Copy code

### 4️⃣ Open-Source Intelligence (OSINT)
- Used search engines to gather publicly available information.
- Identified exposed services or publicly shared data.

---

## 🛠 Tools Used

| Tool | Purpose |
|------|---------|
| WHOIS | Domain ownership info |
| nslookup | DNS queries |
| Nmap | Network discovery and port scanning |
| Search Engines | Public information gathering |

---

## 🧠 Skills Learned

- Understanding reconnaissance as a non-intrusive activity  
- Collecting domain and DNS information  
- Identifying exposed services  
- Using OSINT techniques responsibly  

---

## ⚠️ Challenges Faced

| Issue | Solution |
|------|----------|
| Incomplete WHOIS info | Used multiple lookup services |
| DNS resolution delay | Retried queries and verified domain |

---

## 🔐 Ethical Considerations

All reconnaissance was performed on an authorized lab target. No intrusive attacks were conducted, and all actions followed ethical guidelines.

---

## ✅ Outcome

Successfully gathered relevant information about the target environment using passive and active reconnaissance methods within the allowed scope.

---

## 📌 Conclusion

This lab demonstrated how attackers and security professionals gather intelligence before testing systems. It reinforced the importance of reconnaissance in cybersecurity assessments.

---

**Lab Status:** Completed
