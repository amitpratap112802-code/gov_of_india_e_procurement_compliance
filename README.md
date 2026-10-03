# 🇮🇳 GeM-Comply | Gov of India E-Procurement Compliance

> **Tagline: NO MORE FAKE, ONLY VERIFIED**
> **Team: Funt4stic Devs | SIH / Hackathon Project 2026**

An AI + Blockchain powered solution to stop fake documents (PAN, GSTIN, Turnover) on Government e-Marketplace (GeM) - Saving 1000+ Crore fraud.

🔗 **Live Demo:** https://amitpratap112802-code.github.io/gov_of_india_e_procurement_compliance/
🔗 **GitHub:** https://github.com/amitpratap112802-code/gov_of_india_e_procurement_compliance

### 🚨 The Problem
GeM does 4 Lakh Crore transaction yearly. 30%+ cases have fake PAN like `ABCDE1234F`, fake GST, photoshopped turnover.
- Manual verification takes 7-10 days
- No AI tool for officers
- No tamper-proof proof
- Portal is English-only, rural vendors can't use

### 💡 Our Solution - 3-Layer Security

**Layer 1: AI OCR (Client-Side)**
- Uses Tesseract.js - 100% browser based, no data goes to server
- Extracts text from PDF and validates PAN format `ABCDE1234F` with Regex

**Layer 2: Fraud Detection Engine**
- Custom logic: PAN vs GSTIN name match, Turnover growth anomaly (>500% = fraud), Expiry check
- Generates Fraud Score: 12% Low Risk / 85% High Risk

**Layer 3: Blockchain Security**
- SHA-256 Cryptographic Block: Block ID `GCB-...`, Full Hash, IPFS CID `Qm...`, Timestamp, Previous Hash
- Tamper-proof - if 1 letter changes, hash fails. Admissible in Court.

**WOW Factor: Hindi Voice Assistance**
- Final Report Voice: Speaks full verification result in Hindi
- Guide Voice: 🎙️ Button explains 5-step working in Hindi for rural vendors

### ✨ Key Features
- ✅ 90% Faster: 7 days -> 2 minutes
- ✅ 100% Secure: Client-side processing, zero data leak
- ✅ Blockchain Proof: IPFS + SHA-256
- ✅ Inclusive: Hindi Voice for 60% rural vendors
- ✅ Offline Capable

### 🛠️ Tech Stack
- Frontend: HTML5, CSS3, JavaScript
- AI: Tesseract.js OCR, Regex, Custom Fraud Logic
- Blockchain: SHA-256, IPFS
- Voice: Web Speech API

### 🚀 How to Run
1. Clone repo
2. Open `index.html` in browser
3. Upload Sample PDF `GeM_Demo_PAN_GST_SAMPLE.pdf`
4. Click Generate Block & Play Voice

### 👥 Team Funt4stic Devs
- Afifa Nusrat - Research & Problem Validation
- Amit Pratap Singh - AI & Tech Architect (Team Lead)
- Antra Gupta - UI/UX & Demo Lead
- Ansh Vishwakarma - Blockchain & Pitch Lead

### 📈 Future Roadmap
- GeM Official API Integration
- 12 Indian Languages Voice
- Smart Contract Auto-Blacklist if Score > 80%

**Made with ❤️ for Corruption-Free India**
