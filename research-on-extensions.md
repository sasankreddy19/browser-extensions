# 🔍 Research on Malicious Browser Extensions

This document summarizes the risks of malicious browser extensions and how they can harm users.

---

## ⚠️ Risks of Malicious Extensions

### 🛑 Data Theft
Extensions can steal sensitive information such as:
- Login credentials
- Cookies and session tokens
- Browsing history
- Personal data (e.g., credit card details)

**Example:**  
In **December 2024**, 35 Chrome extensions (including Cyberhaven’s) were compromised to steal Facebook authentication tokens, impacting over **2.6 million users**.

---

### 🐛 Malware Distribution
Malicious extensions may act as a delivery mechanism for malware like spyware or ransomware.

**Example:**  
In **2022**, the “FB Stealer” extension mimicked Google Translate to steal Facebook credentials, distributed via cracked software using the **NullMixer Trojan**.

---

### 📢 Adware and Malvertising
Some extensions inject ads, hijack search results, or redirect users to phishing sites.

**Example:**  
In **2023**, **32 Chrome extensions** with a total of **75 million downloads** were removed for search hijacking and ad injection.

---

### 🔓 Account Takeover
Using stolen credentials or session tokens, attackers can hijack user accounts.

**Example:**  
The **2024 Cyberhaven attack** targeted Facebook Ads accounts by collecting user IDs and session cookies.

---

### 🐢 Performance Degradation
Extensions with hidden tracking or malicious scripts can slow down browser performance.

**Example:**  
**The Great Suspender**, a once-popular tab manager, was hijacked in **2021** and began injecting tracking scripts, causing memory issues.

---

### 🚫 Unauthorized Actions
Malicious extensions can:
- Redirect searches
- Modify web page content
- Disable browser security mechanisms like **Content Security Policy (CSP)**

**Example:**  
A **2024 campaign** used injected JavaScript to **disable CSP**, allowing unauthorized code execution.

---

### 🔒 Persistence Mechanisms
Some extensions use **enterprise policies** or registry modifications to prevent uninstallation.

**Example:**  
Manual removal may require tools like `RKill` or editing system-level settings.

---

## 📰 Recent Examples

| Case | Description |
|------|-------------|
| **2024 Cyberhaven Attack** | 35 extensions compromised via phishing; 400,000 users affected in 31 hours. |
| **2023 PDF Toolbox** | Loaded remote code from `serasearchtop[.]com`; enabled ad injection and search redirection. |
| **2023 Dormant Colors Campaign** | 30 extensions modified post-installation to steal data and inject affiliate links. |
| **2025 GitLab Discovery** | 16 extensions exfiltrated DOM content and disabled CSP; removed by Google in Jan 2025. |

---

## 📚 Sources

- [Securelist – Threat in Your Browser](https://securelist.com/threats-in-browser/)
- [GitLab Security Tech Notes, 2025](https://about.gitlab.com/security/)
- [Seraphic Blog – Growing Threat](https://seraphic.io/blog/)
- [BleepingComputer, 2023](https://bleepingcomputer.com/)
- [Tom’s Guide – Chrome Extension Threat](https://tomsguide.com/)

---

## 🛡️ Prevention Tips

- ✅ Install only from **trusted sources** (e.g., Chrome Web Store, Mozilla Add-ons).
- ✅ Check permissions and avoid those asking for **“read and change all your data on all websites.”**
- ✅ Regularly **audit and remove** unused or suspicious extensions.
- ✅ Use **antivirus or endpoint protection** tools for real-time threat detection.
- ✅ Keep **browser and extensions updated** to reduce vulnerability.
- ✅ Consider solutions like **LayerX** or **Field Effect MDR** for enterprise-level monitoring.

---

