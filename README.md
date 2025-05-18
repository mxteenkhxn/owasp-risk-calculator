🔐 OWASP Risk Calculator

📌 Project Summary

The OWASP Risk Calculator is a sleek and interactive web tool that implements the OWASP Risk Rating Methodology to help developers, security professionals, and organizations assess security risks based on various technical and business factors.

This project simplifies complex risk analysis through a clean, modern UI and live calculation of risk scores. It's fully client-side, lightweight, and fast.
✨ Key Features

✅ Interactive UI — Easily select and change factors to see real-time results
✅ Live Risk Calculation — Instant feedback on Likelihood, Impact, and Risk Rating
✅ OWASP-Aligned — Follows official OWASP guidelines for risk scoring
✅ Responsive Design — Mobile-friendly and accessible
✅ Zero Dependencies — Built from scratch with pure HTML, CSS, and JavaScript
🧠 Why This Project?

Security is critical in today’s digital world, and understanding risk is the foundation of effective cybersecurity.

🔸 Manual risk calculation is time-consuming
🔸 Existing tools are often too complex or locked behind accounts
🔸 This tool empowers everyone to make quick, informed security decisions

Whether you're a student, developer, pentester, or CISO — this tool is built to make risk assessment fast, simple, and actionable.
🛠️ Tech Stack
Technology	Purpose
🧱 HTML5	Structuring the web interface
🎨 CSS3	Styling and layout (responsive & clean)
⚙️ JavaScript	Dynamic interactions and risk calculations
🚀 GitHub Pages	Deployment and hosting
⚙️ How It Works

The app is divided into four major categories of input:
Threat Agent Factors (Skill Level, Motive, Opportunity, Size)
Vulnerability Factors (Ease of Discovery, Exploit, Awareness, Detection)
Technical Impact (Confidentiality, Integrity, Availability, Accountability)
Business Impact (Financial, Reputation, Legal, Privacy)

Each input has a score from 0–9. The app:
Averages values in each category
Calculates:
Likelihood Score = Avg of Threat Agent & Vulnerability
Impact Score = Avg of Technical & Business Impact
Risk Rating based on a matrix of both

➡️ The result is shown in real time — no need to click submit!

📁 Project Structure

📂 owasp-risk-calculator/
├── index.html        # Web structure
├── styles.css        # Custom styling and layout
├── script.js         # Logic for calculation and dynamic updates
└── README.md         # This beautiful documentation 😉

🔍 Use Cases
🛡️ Security Professionals – Prioritize vulnerabilities during assessments
🧪 Students/Learners – Understand risk scoring with OWASP methods
📊 Managers & CISOs – Make data-driven security decisions
👨‍💻 Developers – Integrate risk awareness into the dev process
