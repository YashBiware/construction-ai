# 🏗️ Multimodal Construction Intelligence Platform

**Skill Wallet Capstone Project 1** | Platform ID: `6ac4c98d1dcde6d7857c1642`

A production-ready **Generative AI** decision-support system for the construction and real estate industry, built with Python + Streamlit + Google Gemini.

---

## 🚀 Features

| Tab | Module | Standards |
|-----|--------|-----------|
| 🦺 **PPE Safety Audit** | Multimodal image analysis for worker PPE compliance | OSHA 1926, IS 456 |
| 🔬 **Crack Diagnostics** | Defect classification with severity scoring and repair guidance | IS 13311, ACI 224R |
| 💰 **Valuation & Planning** | INR cost estimation, capex tracking, 3D rendering | IS 456, Market Rates |
| 🌤️ **Site Assistant** | Weather-aware protocols + AI engineering chatbot | All IS/OSHA |

---

## 🛠️ Tech Stack

- **AI**: Google Gemini 1.5 Flash (multimodal)
- **Frontend**: Streamlit + Custom CSS (dark glassmorphism theme)
- **Rendering**: Pollinations AI / Flux (architectural 3D)
- **Image Analysis**: Pillow
- **Standards**: OSHA 1926 · IS 456:2000 · IS 13311 · ACI 224R

---

## ⚡ Quick Start

### 1. Clone & Install

```bash
git clone <repo>
cd "genAI Project 1"
pip install -r requirements.txt
```

### 2. Run Locally

```bash
streamlit run app.py
```

### 3. Configure API Key

In the sidebar, paste your **Google Gemini API Key** from [Google AI Studio](https://aistudio.google.com/app/apikey).

> **Demo Mode**: Works without an API key using pre-built demonstration payloads.

---

## 📁 Project Structure

```
genAI Project 1/
├── app.py                     # Main Streamlit entry point
├── requirements.txt           # Python dependencies
├── .streamlit/
│   └── config.toml            # Theme & server config
└── modules/
    ├── __init__.py
    ├── styles.py              # Global CSS injection
    ├── gemini_client.py       # Gemini API wrapper + demo fallbacks
    ├── tab_ppe.py             # Tab 1: PPE Safety Audit
    ├── tab_crack.py           # Tab 2: Crack Diagnostics
    ├── tab_valuation.py       # Tab 3: Valuation & Planning
    └── tab_assistant.py       # Tab 4: Weather Advisory + Chatbot
```

---

## ☁️ Deploy to Streamlit Community Cloud

1. Push to a public GitHub repository
2. Visit [share.streamlit.io](https://share.streamlit.io)
3. Connect repo → set `app.py` as entry point
4. Add `GEMINI_API_KEY` in **Secrets** (optional — demo mode works without it)

---

## 📋 Kanban Epics

| Epic | Coverage |
|------|---------|
| Pre-requisites | Python 3.9+, Streamlit, modular structure |
| Epic 1 | Requirements & Environment setup |
| Epic 2 | PPE Safety Vision + Crack Diagnostics |
| Epic 3 | Project Planning + Real Estate Valuation |
| Epic 4 | Multimodal AI + JSON Data Contracts |
| Epic 5 | Site Chatbot + Weather Advisory |
| Epic 6 | Interface, Testing, Cloud Deployment |

---

## 🔑 API Key Security

- API key is entered via password field in sidebar (not stored)
- No external database dependencies
- Falls back to demonstration mode gracefully if no key provided

---

*Built with ❤️ as Skill Wallet Capstone Project 1*
