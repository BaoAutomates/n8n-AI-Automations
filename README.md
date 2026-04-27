# n8n AI Automations Portfolio

<img src="https://img.shields.io/badge/n8n-Workflows-green?style=flat" alt="n8n">
<img src="https://img.shields.io/badge/AI%20Automation-OpenAI-blue?style=flat" alt="AI">
<img src="https://img.shields.io/badge/Location-Hanoi,%20Vietnam-red?style=flat" alt="Vietnam">

**Hi, I'm Bao** — a 17-year-old aspiring **AI automation specialist** from Hanoi, Vietnam 🇻🇳.

This repository showcases **practical n8n workflows** I’ve built while learning AI automation.  
My focus is on solving real business problems for Vietnamese SMEs and international clients — increasing overall revenue, saving time, reducing manual work, and using AI intelligently.

Currently includes **4 documented workflows** with clear understanding of JSON data flow, triggers, error handling, and API connections.

## Featured Workflows

### 1. AI Receptionist for Plumbing Business
**What it does:** Automatically answers calls and book meetings with customers outside of working hours or when nobody is available using AI.  
**Business value:** Helps international plumbing businesses never misses potential revenue, keeping in touch with clients 24/7.  
**Tech stack:** n8n, RetellAI, Cal.com, Twilio.  
**Status:** ✅ Built & Documented  
**What I learned:** How to build a basic book/check calendar AI Voice Agent along with the custom cancel booking function I built in n8n

**Demo Video:**

[![Watch Demo](https://img.youtube.com/vi/-Q8ZZbt11R8/maxresdefault.jpg)](https://youtu.be/-Q8ZZbt11R8)

**N8n cancellation function**: <img width="1917" height="896" alt="n8n cancellation system" src="https://github.com/user-attachments/assets/32446718-e1f9-4f7e-9caa-8884ef7a446d" />




### 2. AI Fuel Intake Data Extractor & Google Sheets Auto-Filler
**What it does:** When a new fuel entry is added (often messy text), the AI extracts structured data (date, quantity in liters, vehicle code, customer, notes, etc.) and automatically creates a clean row in Google Sheets.

**Business value:** Saves 2hours/day => 60hours/month, saving hours of manual data cleaning for fuel/logistics businesses in Vietnam, reduces errors, and keeps records accurate and searchable.  
**Tech stack:** Activepieces, Google Sheets, Google Form, n8n, Javascript codes
**Status:** ✅ Built & Documented  
**What I learned:** Compared the strengths of n8n and Activepieces for AI-powered data extraction workflows. Activepieces was faster for structured output, while n8n gave more flexibility with custom code.
**Activepieces workflow**: <img width="1920" height="917" alt="AI Fuel Intake" src="https://github.com/user-attachments/assets/c3f5e852-58aa-4ca8-b621-d70182485bf7" />
**N8n Workflow**: <img width="1920" height="927" alt="AI Fuel Intake2" src="https://github.com/user-attachments/assets/234dd126-b4d5-4c74-baeb-fc73a6271390" />



### 3. AI Google Review Auto-Responder for Dental Clinic
**What it does:** When a new patient record is added to Google Sheets, the workflow automatically sends a thank-you email via Gmail, then follows up with a polite Telegram message asking the patient to leave a Google review.
**Business value:** Helps dental clinics in Vietnam automatically collect more Google reviews with minimal manual effort, improving online reputation and attracting new patients.
**Tech stack:** Activepieces, Google Sheets, Gmail, Google Form
**Status:** ✅ Built & Documented  
**What I learned:** Using delay nodes to create natural timing between messages so it doesn't feel too automated.
**Activepieces Workflow**: <img width="1920" height="919" alt="Activepieces Workflow" src="https://github.com/user-attachments/assets/530e5139-81be-4ede-aa8b-3a769dcd0135" />


### 4. Veterinary Data Entry Supported Workflow
**What it does:** Automatically returns clean rows updated into Google Sheets from messy datas
**Business value:** Saves veterinary clinics 2 hours everyday, leading to more time for customer services and pet treatments 
**Tech stack:** n8n, Google Sheets, Google Form
**Status:** ✅ Built & Documented  
**What I learned:** The AI should be able to read data and extract correctly, if unsure it should leave that category blank

**Demo Video**
[![Watch Demo](https://www.loom.com/share/600382d2d39d4be882f0f7921fe509f3)

**N8n Workflow** <img width="1920" height="922" alt="Vet" src="https://github.com/user-attachments/assets/c244667d-9bfe-41c8-a091-2a8289a687ad" />


## Skills Demonstrated
- Visual workflow building in n8n
- AI integration & prompt engineering with OpenAI
- JSON data flow and n8n expressions
- Multiple triggers (email, webhook, schedule, manual)
- Error handling and conditional logic (IF nodes)
- API connections and credential management
- Debugging using Table and JSON views

## Repository Structure
- `/workflows/` — Ready-to-import `.json` files  
- `/screenshots/` — Workflow canvas + input/output examples  
- `/docs/` — (future) Detailed notes and case studies

## How to Use
1. Open n8n (Cloud or Desktop)
2. Click the **⋯** (three dots) menu → **Import from File**
3. Upload the `.json` file from the `workflows/` folder
4. Set up your credentials (OpenAI API key, Google account, etc.)
5. Test and customize the workflow

## Learning Roadmap (April–May 2026)
- **Week 1**: GitHub repo + document all 4 existing workflows ✅
- **Week 2**: Build & document a new AI Email Summarizer
- **Week 3**: Build a Vietnam-relevant workflow (e.g. Zalo/Facebook lead qualification + notification)
- **Week 4**: Add PostgreSQL database + basic Python Code node
- **Ongoing**: Improve JSON understanding and make workflows client-ready

## Contact & Collaboration
- n8n Vietnam Community on Facebook (highly recommended for local support)
- GitHub: [@Mai Gia Bảo(Edward)](https://github.com/EdwardPlumbVoiceAI)
- Open to feedback, suggestions, or freelance opportunities!

Made with ❤️ in Hanoi, Vietnam  
Last updated: April 25, 2026
