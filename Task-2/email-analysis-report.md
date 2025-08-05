# 🛡️ Cybersecurity Task 2 – Phishing Email Analysis

## 📧 Sample Email Subject:
"has a document for your review"

---

## 🚩 Phishing Indicators Found:

| Indicator                          | Evidence / Example                                         |
|-----------------------------------|-------------------------------------------------------------|
| **Suspicious Sender Email**       | `goog...@protected-download.com` – not a real Google domain |
| **Fake Branding**                 | Uses Google Drive layout and logo to look trustworthy       |
| **Deceptive Link**                | "Click Here" redirects to unknown PDF – possible malware    |
| **Generic Context**               | No file name, no message, no personalization                |
| **Urgent/Action Prompt**          | “has shared the following PDF” with no other context        |
| **Masking Real Intent**           | “Click Here” hides the real destination URL                 |

---

## 🔍 Email Header Analysis:
Since the header was not available, standard spoof detection methods would apply:
- Check SPF/DKIM records of the sending domain.
- Verify IP origin in headers.
- Check if the email originated from an allowed mail server.

---

## 📷 Screenshot:
File: `screenshot.png` (attached in this repo)

---

## 💡 What I Learned:
- How to recognize fake file-sharing links in phishing emails.
- Visual spoofing using logos and familiar UI to gain trust.
- Importance of verifying sender domain and checking URLs.
- Social engineering tactics used to get users to click dangerous links.

---

## ✅ Submission
GitHub Repo: `https://github.com/your-username/Cybersecurity-Task2`  
*(Replace with your actual repo link)*

Form Link: [Click here to submit](https://forms.gle/8Gm83s53KbyXs3Ne9)
