# EcoSaarthi 🌱

EcoSaarthi is an **offline-first eco and cultural tourism safety application** designed for rural, forest, and eco-tourism regions where internet connectivity is weak or unavailable.

This repository represents the **Minimum Viable Product (MVP / Prototype)** of the EcoSaarthi concept, built to demonstrate the core idea, system architecture, and safety-focused features.

---

## 🚩 Important Notice (Prototype)
⚠️ **This is an MVP / Prototype build, not a complete production application.**  
Some features are demonstrated in simulated or conceptual form for hackathon evaluation purposes.

---

## 🧩 Problem Statement

Travelers visiting rural, forest, and eco-tourism regions often face serious safety challenges due to poor or no internet connectivity. Existing travel applications depend heavily on live internet services such as GPS, maps, and real-time APIs, which fail completely in offline environments.

This leaves travelers without:
- Safety guidance  
- Local rules & cultural awareness  
- Emergency assistance  
- Directional support  

---

## 💡 Solution Overview

EcoSaarthi provides a **dual-mode travel safety companion** that works both **online and offline**.

### 🌐 Online Mode (Concept Demo)
- Uses **Google Maps API** for live location detection
- Uses **Google Gemini API** for AI-generated summaries:
  - General information
  - Activities
  - Accommodation
  - Transportation
  - Safety rules & skills
  - Emergency guidance

> ⚠️ Online mode is currently shown as a **concept demo** in this MVP.

---

### 📵 Offline Mode (Core MVP Feature)
Offline Mode works **without GPS or internet** using a:

**Rule-Based Location Inference System**

Users answer simple observation-based questions such as:
- Terrain type  
- Climate  
- Direction  
- Surroundings  

These inputs are matched against a **preloaded regional knowledge base (JSON)** to provide:
- Approximate regional guidance
- Local safety instructions
- Cultural awareness tips
- Emergency information

All offline results are **clearly labeled as approximate**.

---

## 🛡️ Safety-Focused MVP Features

- 🧭 **Offline Compass (Simulated)** using directional inference  
- 🚨 **SOS Emergency Button** (Prototype popup demonstration)  
- 🌍 **Offline-first design philosophy**  
- 🧠 **Rule-based logic instead of internet dependency**  

---

## 🧪 MVP Status

This project is an **MVP / Prototype**, built to validate:
- Offline-first logic
- Safety-centric UX
- Dual-mode architecture
- Feasibility of AI + offline rule-based systems

Several features are **intentionally simplified or simulated** for demonstration.

---

## 🛠️ Technologies Used

### Google Technologies
- Google Maps API  
- Google Gemini API  
- Google Docs / Slides (documentation & pitch)  

### Development Framework & Tools
- **Flutter (Web MVP)**
- Android SDK
- JSON (offline data storage)

### AI & Assistance Tools
- Google Gemini API (core AI)
- ChatGPT (development & documentation assistance)
- GitHub Copilot (coding assistance)

> **Note:** ChatGPT and GitHub Copilot were used strictly as development support tools.  
> Core AI functionality is powered by **Google Gemini API**.

---

## 🌐 Live Web Demo (MVP)

🔗 **Live Demo:**  
https://d-adityaa.github.io/EcoSaarthi/

> The web version showcases the **MVP UI, offline logic simulation, SOS demo, and compass concept**.

---

## 🏁 Hackathon Compliance

- Developed entirely during the hackathon timeline  
- No pre-existing coursework or projects used  
- Original idea and implementation  
- Built strictly for MVP demonstration and evaluation  

---

## 🎯 Conclusion

EcoSaarthi combines **Google’s AI ecosystem** with **offline intelligence** to provide a safety-first travel companion for regions where connectivity cannot be trusted.

This MVP demonstrates how **responsible, inclusive, and resilient travel technology** can be built for real-world constraints.

---

**Status:** MVP / Prototype 🚀  
**Future Scope:** Full offline AI models, real SOS integration, multilingual expansion, sensor-based navigation
