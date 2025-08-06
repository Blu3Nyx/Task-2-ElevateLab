# 💼 CYBER SECURITY INTERNSHIP – TASK 2  
## 🔎 PHISHING EMAIL ANALYSIS

---

### 🏢 INTERNSHIP DETAILS  
- **Task Number:** Task 2  
- **Task Title:** Analyze a Phishing Email Sample  

---

### 🎯 OBJECTIVE  
To analyze a phishing email and identify all the indicators of phishing using proper tools and manual inspection methods. This task helps understand how phishing attacks work and how to detect them.

---

### 🛠️ TOOLS USED

- MXToolbox Email Header Analyzer
  
---

### ✅ STEPS COMPLETED

#### 🔹 STEP 1: SAMPLE COLLECTION  
I created a phishing-style email and sent it to myself. This allowed me to safely analyze a fake email without using any real malicious message.

#### 🔹 STEP 2: CHECKING SENDER EMAIL  
I examined the sender's email ID. It looked suspicious because it was not an official PayPal domain and seemed spoofed.

#### 🔹 STEP 3: EMAIL HEADER ANALYSIS  
I copied the full header from the email in Gmail and analyzed it using **MXToolbox**. The analysis showed:  
- Mismatch in sending IP and domain  
- SPF authentication failed  
- Email was sent from an unknown mail server, not PayPal  

#### 🔹 STEP 4: IDENTIFYING SUSPICIOUS LINKS  
The email included a fake link to "verify the account". By hovering over the link, I saw that the actual URL was not related to PayPal. This is a classic phishing trick.

#### 🔹 STEP 5: CHECKING FOR URGENT LANGUAGE  
The email used strong language like:  
> "Your account will be permanently suspended within 24 hours if not verified."  
This creates panic in the user to take immediate action.

#### 🔹 STEP 6: MISMATCH BETWEEN DISPLAYED AND ACTUAL URL  
The displayed text showed “paypal.com”, but on hovering, it pointed to a different unknown domain. This is a strong sign of phishing.

#### 🔹 STEP 7: GRAMMAR AND SPELLING CHECK  
The grammar was mostly correct, but:  
- The message felt unnatural  
- It used a generic greeting like “Dear Customer” instead of using my name  
- There was no signature from a real person or support contact  

#### 🔹 STEP 8: FINAL SUMMARY OF PHISHING INDICATORS  
- Fake sender email  
- Mismatched URL  
- Urgent and threatening language  
- Generic greeting  
- No personalized information  
- Failed SPF check in header  
- Email sent from a suspicious mail server  

---

### 📚 WHAT I LEARNED  
- How phishing emails are created and why people fall for them  
- How to analyze email headers using MXToolbox  
- How to spot red flags like spoofed domains, suspicious links, and psychological pressure  
- Gained confidence to identify phishing emails in real-world scenarios  

---

### 📌 NOTE  
⚠️ This phishing email was **self-created** for analysis purposes only in a **controlled environment**. No real malicious activity was performed. This is strictly for learning.
