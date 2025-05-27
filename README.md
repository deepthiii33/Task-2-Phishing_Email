# 🛡️ Cyber Security Internship – Task 2

## 📌 Objective

Analyze phishing emails using both content-based techniques and email header analysis to identify common threats and improve phishing awareness.

---

## 📂 Files in This Repository:

- [`Sample-Phishing_analysis`](phishing-analysis-microsoft.md)   :  Analysis of a phishing email pretending to be from Microsoft, showing visual and contextual phishing traits.
- [`Spam-email-analysis`](personal-phishing-analysis.md)  : Header analysis of a real spam email received in Gmail, evaluating SPF, DKIM, and DMARC.                        

  
---

## 🔍 Task Breakdown

### 1. **Phishing Email Sample Analysis**

* Investigated a phishing email impersonating Microsoft.
* Identified traits like spoofed sender, fake links, urgent tone, and poor formatting.

### 2. **Email Header Analysis**

* Used Gmail’s **Show Original** option to extract full email headers from a spam message.
* Analyzed SPF, DKIM, and DMARC results using online tools.
* Found **DMARC failure**, a red flag that suggests the sender's domain wasn't properly authorized — often used in spoofing.

---

## 🧠 Key Takeaways

* Not all technically "authenticated" emails are safe—behavioral clues also matter.
* Email header analysis will reveals whether domains and sources are aligned.
* Phishing emails often use urgency, fear, and lookalike branding to manipulate users.

---


> 💡 Tip: Always inspect unknown emails carefully — especially ones asking for urgent actions, personal info, or payments.
