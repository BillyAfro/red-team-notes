# 🎣 Phishing Fundamentals

## 🧠 What is phishing
Phishing is a social engineering attack used to trick users into revealing sensitive information such as credentials or gaining unauthorized access.

---

## ⚙️ How phishing works (flow)

1. Reconnaissance (OSINT)
2. Crafting the message (email, Teams, etc.)
3. Victim clicks malicious link
4. Fake website or proxy
5. Credential harvesting or session capture

---

## 🔐 Credential Harvesting

- Fake login page is created
- Victim enters credentials
- Data is sent via HTTP POST to attacker

Example:

POST /login
username=bob
password=1234


---

## 🍪 Session Hijacking (Modern Phishing)

- Uses reverse proxy (AiTM – Adversary-in-the-Middle)
- Victim logs into real website
- Session cookie is captured
- Attacker bypasses MFA using stolen session

---

## 📧 Email Techniques

- Email spoofing (limited in real world)
- Use of trusted platforms (Google Docs, Microsoft 365)
- Compromised accounts
- Typosquatting domains (e.g. go0gle.com)

---

## 🧠 Social Engineering Principles

- Urgency
- Authority
- Fear
- Curiosity
- Trust
- Scarcity

---

## 🌍 Real-World vs Lab

### Lab (TryHackMe / SET)
- Simple phishing page
- No MFA
- Controlled environment

### Real World
- Reverse proxy phishing (Evilginx)
- Session hijacking instead of password theft
- AI-generated emails
- Use of legitimate services
- Highly targeted attacks

---

## ⚠️ Key Takeaways

- Phishing targets humans, not systems
- MFA does not fully prevent attacks
- Session cookies are critical
- Context and trust increase success rate

---

## 🧠 My Understanding

Phishing is not about hacking systems but manipulating people into giving access.  
Modern attacks focus on session hijacking instead of passwords, making them harder to detect and prevent.

<img width="670" height="94" alt="Opera Snapshot_2026-04-15_171432_tryhackme com" src="https://github.com/user-attachments/assets/03492782-270a-417c-85e0-5d2c4b1a3f32" />
