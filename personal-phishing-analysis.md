# ✉️ Personal Insight: Analyzing a Real Spam Email I Received

## 📥 What I Got in My Inbox

I received a spam email that immediately raised a few red flags. It claimed to be from a “Director” at a job board domain and had a very dramatic subject line: **“Urgent Attention Required.”**

At first glance, it looked like a job opportunity or a reply to a previous application. But once I looked closely, things didn’t add up.

![](https://github.com/deepthiii33/Task-2-Phishing_Email/blob/main/screenshots/spam_email_content.png)

---

## 🔍 What Made It Suspicious

### 1. **It Was Trying to Make Me Panic**
The subject line used urgent language — classic phishing behavior. These types of messages often try to trick you into acting fast without thinking clearly.

### 2. **Vague and Generic Identity**
The sender was just listed as "Director" without any name or recognizable person. It seemed like they were trying to sound important but stayed deliberately vague.

The email also referenced **Internshala**, as if trying to reassure me that everything was legitimate — but that just made it more suspicious. Real employers don’t usually send emails explaining why they’re not fake.

### 3. **Strange Domain**
The sender used `@jobs.ndfmbusinessworld.com`, which isn’t a well-known company domain. I couldn’t find any professional presence online that made this domain feel trustworthy.

---

## 🔎 Technical Analysis (Email Header)

To confirm my doubts, I used Gmail’s **“Show Original”** feature and checked the email header.

Here’s what I found:

![](https://github.com/deepthiii33/Task-2-Phishing_Email/blob/main/screenshots/spam_email_header.png)

- **SPF:** ✅ Passed  
- **DKIM:** ✅ Passed  
- **DMARC:** ❌ **Failed**

> Even though SPF and DKIM passed, the DMARC failure was the real red flag. It means the domain didn’t properly authenticate this email — which suggests the sender might be spoofing the domain or is unauthorized.

---


## ✏️ Language & Grammar Red Flags

Aside from technical issues, the email had quite a few grammar and spelling mistakes that made it feel unprofessional:

- It said **“Internshala have talked to us”**, but it should be **“Internshala has talked to us”** — a clear subject-verb agreement issue.
- The name **“Internshala”** was written in lowercase multiple times, which is unusual for a proper noun.
- Phrases like **“clarification of authenticity”** or **“doubt basis”** were awkward and nonstandard — more natural wording would be **“clarification regarding the authenticity”** or **“on the basis of doubt.”**
- There was a typo in **“Minsitry of Corporate Affairs”** — it should be **“Ministry.”**
- It ended with **“Thanks and Regards,”** which felt a bit off for formal communication — something like **“Best regards”** would sound more professional.

These language issues, though small, gave the message a suspicious and rushed tone — another common trait in phishing emails.


---

## ✅ Conclusion

By looking at both the content of the email and the technical details in the header, I was able to clearly identify this as a phishing attempt. The DMARC failure, unusual sender address, grammar mistakes, and urgent language were all signs that something wasn’t right.

This task helped me understand how phishing emails work — not just from a technical point of view, but also how they try to trick people using fear and confusion. It reminded me to always stay alert and to double-check before clicking anything suspicious.

