# CrediCheck

CrediCheck is a simple web-based tool that helps students evaluate the credibility of internship listings.

It analyzes internship descriptions and links to generate a **credibility score**, along with reasons explaining why an opportunity may be safe, risky, or require caution.

---

## 🚀 Features

- 📊 Generates a **credibility score (0–100)**
- ⚠️ Detects common **red flags**:
  - Payment / registration fees
  - Urgency tactics
  - WhatsApp-only communication
- ✅ Identifies **positive signals**:
  - Trusted platforms (LinkedIn, Internshala, Indeed)
  - Company name matching URL
- 🧠 Provides **clear explanations** (reasons list)
- 🏷️ Labels results as:
  - Safe
  - Caution
  - Risky

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (Vanilla JS)

---

## 📸 How it Works

1. Enter:
   - Internship title
   - Company name
   - Description
   - URL

2. Click **"Check Credibility"**

3. Get:
   - Score
   - Label
   - Reasons

---

## 🧠 Scoring Logic (MVP)

- Starts at **base score = 50**
- Subtracts points for red flags
- Adds points for positive signals
- Clamps score between **0 and 100**

### Example Signals

**Negative**
- "pay", "fee", "registration"
- "urgent", "apply now"
- "whatsapp"

**Positive**
- Trusted job platforms
- URL-company consistency

---

## 🎯 Purpose

Many students fall for fake or misleading internships that:
- ask for money
- misuse brand names
- create false urgency

CrediCheck aims to provide a **quick, explainable way** to assess such opportunities.

---

## ⚠️ Disclaimer

CrediCheck is a heuristic-based tool.

- It does **not guarantee** whether an internship is legitimate
- It provides a **guideline**, not a final verdict

Always verify opportunities independently.

---

## 📌 Future Improvements

- Smarter scoring (cluster-based detection)
- Domain verification
- Better UI/UX
- Mobile responsiveness
- Backend integration
- Real-time validation

---

## 🌐 Live Demo

https://incomparable-empanada-6e2376.netlify.app/

---

##Images of working of the website

<img width="1490" height="778" alt="initial screen" src="https://github.com/user-attachments/assets/f08e5e08-9d34-496b-9a87-521e8e6ddb6d" />

<img width="1745" height="982" alt="output" src="https://github.com/user-attachments/assets/98105bf1-a41d-418f-a582-c6ef6ac29ed6" />


## Author

Built by Ash
