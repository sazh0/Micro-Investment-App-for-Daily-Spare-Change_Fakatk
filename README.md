<div align="center">

# Micro-Investment App for Daily Spare Change 💰

<p>
  <img src="https://img.shields.io/badge/🏆_3rd_Place_Winner-d4a017?style=flat-square" alt="3rd Place"/>
  &nbsp;
  <img src="https://img.shields.io/badge/📱_Mobile_App-0969da?style=flat-square" alt="Mobile App"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🤖_ML_Recommendation-7c3aed?style=flat-square" alt="ML"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🇸🇦_Vision_2030-16a34a?style=flat-square" alt="Vision 2030"/>
  &nbsp;
</p>

A micro-investment app that turns your **everyday spare change** into a driver for Aseer's local economy. Every halala counts — round up your purchases, invest locally, and watch your community grow.

**🏆 Third Place Winner — Investment Track, Aseer Innovates Hackathon 2025**
<br/>
<sub>Out of +2,500 participants · Issued by Aseer Development Authority</sub>

</div>

---

<div align="center">
  <img src="images/AppPortfolio.gif" alt="Fakatk App Demo" width="97%"/>
</div>

<div align="center">
  <img src="images/Fakatkphones.png" alt="Fakatk Phone Mockups" width="97%"/>
</div>

---

## 📌 About The Project

In Saudi Arabia, over **890,000** POS transactions across just 27 days produced more than **400,000** unused halalas — spare change that vanishes unnoticed. Meanwhile, Aseer's investment community remains small, and awareness around venture investing is low.

**Fakatk** (فكّتك) flips that problem into opportunity. The app collects the leftover halalas from every purchase a user makes, rounding up flexibly to the nearest 1, 5, or 10 SAR. Once a threshold is reached, those micro-amounts are automatically pulled by licensed investment partners and distributed across local investment opportunities — startups, small businesses, and community ventures.

The result? A **larger, more diverse investment community** where anyone can participate, returns flow back to users, and the local economy gets a direct boost.

### ✨ Key Features

| Feature | Description |
|:--|:--|
| **Smart Round-Up Collection** | Flexibly rounds up purchases (1, 5, or 10 SAR) and accumulates spare change in a digital wallet |
| **Licensed Investment Distribution** | Funds are automatically invested through certified partners into local opportunities |
| **ML Recommendation Engine** | Weekly AI-powered suggestions to adjust investment type and risk level based on user activity |
| **Rule-Based Recommendations** | Structured logic layer for consistent, transparent investment guidance |
| **Open Banking Integration** | Securely accesses transaction history to calculate spare change with precision |
| **Returns to Users** | Investment returns flow directly back into user accounts |

---

## 🏆 Results & Impact

| Metric | Value |
|:--|:--|
| Hackathon Result | **🥉 3rd Place** — Investment Track, Aseer Innovates 2025 |
| Participants Competing | **+2,500** |
| POS Transactions Analyzed (27 days) | **+890,000** |
| Unused Halalas Identified | **+400,000** |
| Projected Monthly Collection (10K users) | **+100,000 SAR** |
| Local Sectors Supported | **+5 sectors** |

> With just **10,000 users** each contributing **0.5 SAR** per 20 monthly purchases, Fakatk can channel over **100,000 SAR/month** directly into local investments that strengthen Aseer's economy.

---

## 🛠️ Built With

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Open_Banking-0a6847?style=for-the-badge" alt="Open Banking"/>
  <img src="https://img.shields.io/badge/ML_Recommendation-7c3aed?style=for-the-badge" alt="ML"/>
  <img src="https://img.shields.io/badge/OAuth2_&_HTTPS-e05d44?style=for-the-badge" alt="Security"/>
</p>

| Layer | Technology | Role |
|:--|:--|:--|
| **Mobile App** | React Native, JavaScript | Cross-platform UI, user interaction, wallet management |
| **Backend & Database** | Firebase | Cloud storage, real-time sync, user balances & data |
| **Financial Integration** | Open Banking API | Secure access to user transaction history & spend tracking |
| **AI / ML** | ML Recommendation Model | Weekly personalized investment type & risk suggestions |
| **Logic Layer** | Rule-Based Recommendation System | Structured investment guidance based on user thresholds |
| **Security** | HTTPS, OAuth2 | Encrypted data transfer & secure authentication |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│          Mobile App (React Native)              │
│    Round-Up Wallet · Portfolio · Investments     │
└──────────────────────┬──────────────────────────┘
                       │
          ┌────────────▼────────────┐
          │     Open Banking API    │
          │  Transaction History &  │
          │   Spare Change Calc     │
          └────────────┬────────────┘
                       │
              ┌────────▼────────┐
              │  AI / ML Layer  │
              │ ┌─────────────┐ │
              │ │ML Recommend.│ │
              │ └─────────────┘ │
              │ ┌─────────────┐ │
              │ │ Rule-Based  │ │
              │ │   Engine    │ │
              │ └─────────────┘ │
              └────────┬────────┘
                       │
         ┌─────────────▼─────────────┐
         │   Firebase Cloud Backend   │
         │ Users · Wallets · Partners │
         └───────────────────────────┘
                       │
         ┌─────────────▼─────────────┐
         │  Licensed Investment      │
         │       Partners            │
         │  Local Startups & SMEs    │
         └───────────────────────────┘
```

---

<div align="center">

<img src="https://img.shields.io/badge/+1-Language-E8912D?style=flat-square&labelColor=1a1a2e" alt="Languages"/>
&nbsp;
<img src="https://img.shields.io/badge/+1-Framework-61DAFB?style=flat-square&labelColor=1a1a2e" alt="Framework"/>
&nbsp;
<img src="https://img.shields.io/badge/+2-AI/ML_Models-7c3aed?style=flat-square&labelColor=1a1a2e" alt="AI/ML"/>
&nbsp;
<img src="https://img.shields.io/badge/+1-Cloud_Database-FFCA28?style=flat-square&labelColor=1a1a2e" alt="Database"/>
&nbsp;
<img src="https://img.shields.io/badge/+1-Financial_API-0a6847?style=flat-square&labelColor=1a1a2e" alt="Open Banking"/>
&nbsp;
<img src="https://img.shields.io/badge/+2-Security_Protocols-e05d44?style=flat-square&labelColor=1a1a2e" alt="Security"/>
&nbsp;
<img src="https://img.shields.io/badge/+8-Technologies_Total-1a1a2e?style=flat-square&labelColor=e05d44" alt="Total"/>

</div>