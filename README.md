# 💸 CapitaClarity

## 🤖 Because Sometimes Your Wallet Needs the Truth. — Now with Voice, Story, and Accessibility

**CapitaClarity** is the ultimate Gen Z fintech playground:  
A sleek, interactive **expense tracker**, **AI‑powered forecasting engine**, **automated goal allocator**, and **on‑demand chatbot advisor**—now enhanced with powerful accessibility and storytelling features for hackathons and real-world impact.

---

## 📌 LIVE DEMO + VIDEO

> 🚀 Live Site: [Live link](https://xypherself.vercel.app)  
> 🚀 Hackathon Slides: [Google Slides](https://drive.google.com/file/d/1zLezCC6uf3Wx7bcEaMzmv_n4QDz4FJzb/view?usp=sharing)

### ⚠️ **IMPORTANT NOTE: Run only in Google Chrome!**
Voice navigation and text-to-speech features **only work in Chrome** due to browser support for the Web Speech API.

---

### ❗ FIRST-TIME SETUP INSTRUCTIONS (Required for Chatbot + ML Forecast to Work)

Because our AWS server isn’t SSL-certified, Chrome blocks requests to it.  
👉 Please visit the following link below manually, click **Advanced → Proceed anyway**, then you can close the tabs:

1. `https://51.20.53.130`  

---

## 📸 Screenshots

| Landing Page (Light) | Landing Page (Dark) | Landing Page (Colorblind) |
|----------------------|---------------------|----------------------------|
| ![Light Mode](./screenshots/light.png) | ![Dark Mode](./screenshots/dark.png) | ![Colorblind Mode](./screenshots/colorblind.png) |

| Dashboard | Chatbot |
|-----------|---------|
| ![Dashboard](./screenshots/dashboard.png) | ![Chatbot](./screenshots/chatbot.png) |

---

## 🌟 Core Features

- ✅ **Secure Onboarding**  
  Signup/login via JWT, then setup your balance & limit in one go.

- ✅ **Instant Transactions**  
  Real-time “Add Income” / “Add Expense” logging — no page reload.

- ✅ **Daily Budget Tracker**  
  Visual progress bar shows remaining daily limit. Friendly nudges included!

- ✅ **Smart Goal Allocation**  
  Drag-and-drop goals. ML splits your projected surplus automatically.

- ✅ **AI Forecasting Engine**  
  TensorFlow-based LSTM model predicts month-end balance. Wrapped with LangChain & FastAPI.

- ✅ **Category Analytics**  
  Beautiful pie charts categorize your spending.

- ✅ **Integrated AI Chatbot**  
  LLM-powered advisor answers context-aware financial queries.

- ✅ **Responsive, Polished UI**  
  React + TailwindCSS + Framer Motion. Works beautifully across screen sizes.

---

## 🔑 Demo Account

You can explore the full site without signing up:

> **Email:** `nemollytest@team.com`  
> **Password:** `Nemolly#123`

---

## 🛠️ Tech Stack

| Frontend | Backend | AI / ML |
|:--------:|:-------:|:-------:|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)  <br> ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E) <br>  ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)  <br> ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) <br>  ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) <br>  ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=Canva&logoColor=white) <br>  ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) <br>  ![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white) |  <br> ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) <br>  ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) <br>  ![FastAPI](https://img.shields.io/badge/FastAPI-109989?style=for-the-badge&logo=fastapi&logoColor=white) <br>  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)  <br> ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)  <br> ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)  <br> ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white) <br>  ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) | <br>  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) <br>  ![Keras](https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white)  <br> ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) <br>  ![HuggingFace](https://img.shields.io/badge/HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black) <br>  ![AWS](https://img.shields.io/badge/Amazon_Web_Services-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) <br>  ![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) <br>  ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)  <br> ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white) |

---

## 📌 TODOs / Roadmap

- **Bank Integrations**: Add Plaid or TrueLayer for automatic transaction imports.  
- **Mobile Apps**: Develop native iOS and Android versions with push notifications.  
- **Pro Forecasting**: Implement “what-if” scenario planning and proactive alerts.  
- **Social Features**: Build savings challenges and group goals for community engagement.  
- **Premium Tier**: Finalize subscription flow for advanced analytics and AI coaching.  
- **Security Audits**: Conduct third-party penetration testing and GDPR compliance review.

---

## 🧑‍💻 Team Jalebi Fafda

- **Neeraj** — AI/ML + Backend Developer [@artyish](https://github.com/artyish)  
- **Harshita** — Frontend Developer [@idkdolly](https://github.com/idkdolly)  
---

## ⚡ Special Thanks

- OpenAI (ChatGPT + Whisper)  
- AWS EC2 + HuggingFace  
- FastAPI, LangChain  
- Hackathon mentors & judges 🙏  

---

# Made with ❤️ by Team Nemolly  
