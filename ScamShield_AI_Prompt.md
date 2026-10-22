# ScamShield AI — Project Prompt

Build a complete, modern, AI-powered cybersecurity web application called ScamShield AI — Intelligent Multilingual Scam Detection System.

## Objective

Develop a web application that detects potentially fraudulent SMS messages, phishing URLs, fake banking alerts, and online scams. The application should help users protect themselves from cybercrime and support both Tamil and English.

## Core Features

1. **AI Scam Detection:** Users can paste SMS, WhatsApp messages, emails, or suspicious banking alerts to analyze them.
2. **Phishing URL Scanner:** Analyze URLs for suspicious domains, misleading subdomains, URL shorteners, and other warning signs without opening the website.
3. **Risk Score:** Display a risk score from 0–100 and classify the result as Low, Medium, or High Risk.
4. **AI Explanation:** Explain why a message or URL appears suspicious in simple language.
5. **Tamil + English Support:** Allow users to analyze messages and receive results in Tamil or English.
6. **Safety Recommendations:** Provide practical steps to avoid scams and protect personal information.
7. **Analysis Dashboard:** Display the risk classification, warning signs, explanations, and optional analysis history.
8. **Cybersecurity Education:** Include phishing awareness, online payment safety tips, and scam prevention guidance.
9. **Responsive Design:** Make the application work smoothly on mobile phones, tablets, and computers.
10. **Privacy Protection:** Do not request OTPs, PINs, passwords, or banking credentials. Store analysis history only with user consent.

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript, and Bootstrap 5.
- **Backend:** Python Flask.
- **Machine Learning:** Scikit-learn, TF-IDF, and Logistic Regression.
- **Database:** SQLite.
- **Visualization:** Chart.js.

## UI/UX Design

Create a professional cybersecurity dashboard with a dark navy background, blue and teal accents, glowing shield graphics, smooth animations, modern cards, and accessible controls.

The homepage should contain:

- ScamShield AI logo.
- Headline: "Detect Scams Before They Detect You."
- Message analysis input box.
- URL scanner input box.
- Analyze buttons.
- Risk assessment dashboard.
- Warning signs and safety recommendations.
- Tamil/English language selector.
- Cybersecurity awareness section.

## AI Detection Requirements

- Train a machine learning model using an appropriate, labeled dataset.
- Combine machine learning predictions with transparent, rule-based warning indicators.
- Detect suspicious urgency, impersonation, requests for sensitive information, and potentially misleading URLs.
- Provide explanations for the indicators found.
- Display a clearly labeled rule-based fallback if the trained model is unavailable.
- Never fabricate AI predictions or claim perfect detection accuracy.

## Security Requirements

- Validate user inputs.
- Never automatically visit suspicious URLs.
- Protect API keys with environment variables.
- Escape user input before displaying it.
- Avoid storing sensitive messages unnecessarily.
- Clearly explain that a low-risk result does not guarantee safety.

## Deliverables

Generate a complete, runnable project with all necessary source code, including:

- `app.py`
- `requirements.txt`
- `templates/index.html`
- `static/css/style.css`
- `static/js/script.js`
- `ml_model.py`
- `train_model.py`
- A sample dataset for testing.
- `README.md` with setup and execution instructions.
- Unit tests for the detection functions.

## Demonstration

Include sample phishing messages in Tamil and English, suspicious URLs, and ordinary messages. Show how the application identifies warning signs and recommends safe actions.

## Final Instruction

Build a functional application rather than a static mockup. Generate the project files, implement the backend and frontend, configure the detection pipeline, test the application, and explain how to run it locally. Prioritize accuracy, security, accessibility, and a polished hackathon-ready presentation.
