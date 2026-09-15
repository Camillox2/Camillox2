<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111111,50:1f2937,100:374151&height=220&section=header&text=VITOR%20HENRIQUE%20CAMILLO&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Tech%20Lead%20%7C%20Full%20Stack%20%7C%20AI%20%26%20LLMs&descAlignY=60&descColor=d1d5db&descSize=16" width="100%"/>

### Software Engineer building production systems, enterprise integrations and applied AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vitor%20Camillo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vitor-henrique-camillo)
[![GitHub](https://img.shields.io/badge/GitHub-Camillox2-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Camillox2)
[![Email](https://img.shields.io/badge/Email-vitorcamilloh%40gmail.com-444444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vitorcamilloh@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-DC%20Foundry%20Digital-222222?style=for-the-badge&logo=vercel&logoColor=white)](https://dcfoundrydigital.com)

<img src="https://komarev.com/ghpvc/?username=Camillox2&label=PROFILE%20VIEWS&color=555555&style=flat-square" alt="Profile views"/>

</div>

---

## About me

I am a **Software Engineer** graduated from **Universidade Positivo (2026)** and currently work as a **Tech Lead & Full Stack Developer at Vital Scheffer**.

My day-to-day work combines **technical leadership, architecture, backend, frontend, integrations, automation and applied AI**. I currently lead **2 development interns**, organize the team's work with **Scrum, dailies and weeklies**, review code and use **Gemini-assisted Pull Request reviews** to speed up engineering work while keeping human technical validation before merge.

I enjoy building systems that solve operational problems end to end — from database and APIs to interfaces, integrations, deployment and production support.

```ts
const vitor = {
  role: "Software Engineer | Tech Lead | Full Stack Developer",
  location: "Curitiba, Brazil",
  education: "B.Sc. in Software Engineering — Universidade Positivo",
  mainStack: [
    "TypeScript / JavaScript",
    "React / Next.js",
    "Node.js",
    "Java / Spring Boot",
    "Python / PyTorch",
    "PostgreSQL / MySQL / Redis",
    "Docker / AWS"
  ],
  focus: [
    "Enterprise Software",
    "Backend & Integrations",
    "Full Stack Development",
    "AI / LLM Engineering",
    "Technical Leadership"
  ]
};
```

---

## What I am working on now

### Vital Scheffer — Tech Lead & Full Stack Developer

I lead and develop internal platforms connecting **commercial, manufacturing, logistics, finance and e-commerce operations**.

**MKI Hub**
- Integration between **ERP OMIE** and marketplaces such as **Shopee, Amazon, Mercado Livre and TikTok Shop**
- Inventory synchronization
- SKU cross-checking to identify inconsistent listings
- Competitor monitoring
- ABC inventory / sales analysis

**NextStep CRM**
- Corporate CRM with **ANA AI powered by Gemini** for customer service and lead qualification
- Management KPIs and dashboards
- PCP and public tender modules
- Internal chat with calls and screen sharing using **WebSockets**
- Freight quotation and logistics dashboard
- Contract and checklist workflows integrated with **D4Sign**
- Payment reconciliation and OMIE receivable settlement workflows

**VitalOps**
- Factory-oriented operational tools
- Legacy-to-new product code conversion flows
- Automated OMIE stock movements for requested products
- 3D product visualization
- Approval workflows for customized product projects

**Engineering leadership**
- Directly support and manage **2 development interns**
- Technical prioritization, code review and delivery follow-up
- **Scrum, dailies and weeklies**
- Gemini-assisted PR review and code analysis

I also develop and maintain institutional websites and landing pages for the company, including **vitalscheffer.com.br**.

---

## Previous professional experience

### DIXI Soluções — Full Stack Developer
**Nov 2025 — Dec 2025**

- Took ownership of the main time-tracking platform and its production evolution
- Fixed critical issues across **Java** backend and **Flutter** applications
- Built a new inventory application integrated with **ERP OMIE** using React, Java and MySQL
- Planned and executed production migrations while preserving data integrity and availability

### Tecnoponto — Full Stack Developer
**Jun 2025 — Nov 2025**

- Owned the time-tracking ecosystem end to end
- Built an iOS/Android app in **React Native** with geolocation, offline-first validation and background synchronization
- Managed the complete publication process for **Apple App Store and Google Play**
- Built high-availability **Java REST APIs** for auditable time records
- Reworked web modules in **Flutter/Dart**, including management reports and auditing flows

### EVO Sistemas Inteligentes — Development Intern
**Jan 2025 — Jun 2025**

- Designed and implemented the **IPM time-tracking ecosystem** using distributed services in **Node.js and Java**
- The system managed employee time records for **8 municipalities / city governments**
- Integrated facial-recognition hardware with real-time data synchronization via MySQL
- Built a React Native app for time registration, timesheets and justifications
- Reduced technical debt in legacy Java and Flutter systems

> EVO Sistemas Inteligentes, Tecnoponto and DIXI Soluções are part of the same business group.

---

## AI / LLM project

### [Keilinks — PT-BR LLM from scratch](https://github.com/Camillox2/Keilinks)

Keilinks is my hands-on research project in **training a language model from scratch on consumer hardware**.

The current **Keilinks Core 380M** is not a fine-tune of Qwen, Llama or another ready-made LLM. Its main Transformer architecture is implemented inside the project and its weights are initialized and trained by the Keilinks pipeline.

**Current model profile**
- ~**380M parameters**
- **32,000-token vocabulary**
- **24 Transformer layers**
- Hidden size **1152**
- **18 attention heads / 6 KV heads**
- Grouped Query Attention
- RMSNorm
- SwiGLU
- RoPE
- QK-Norm
- KV cache
- **8,192-token context**
- PyTorch pre-training + conversational SFT
- Local RAG and grounding experiments

The model is trained locally on an **RTX 5050 Laptop GPU with 8 GB VRAM**, using optimizations such as **BF16/TF32, AdamW 8-bit, gradient checkpointing and `torch.compile`**.

External models can optionally work only as **teacher / critic** for part of the synthetic dataset; they do not replace the Keilinks Core weights.

---

## Selected projects

### [Grupo YR Hospitalar — Institutional Website + CRM](https://github.com/Camillox2/grupoyr)
Production project for a healthcare equipment company.

- Institutional website and catalog built with **React + Vite**
- SEO/prerender and structured data with JSON-LD
- Blog and admin workflows
- Serverless database with **Neon**
- Deployment with **Vercel / Cloudflare**
- Gemini backend integration
- Commercial CRM for customer relationship and sales operations

Production site: **https://site.grupoyrhospitalar.com.br**

### Entre Fases — Women's Health App
Mobile application built with **React Native**, **Java Spring Boot** and **Gemini AI**, covering menstrual cycle, pregnancy and menopause experiences.

### [Dr. Adriano Camillo — Institutional Website](https://dradrianocamillo.com)
Responsive React.js institutional website delivered as a freelance project and running in production.

### [CNHora — Product Landing Page](https://cnhora.com.br)
Conversion-oriented responsive landing page built with HTML, CSS and JavaScript.

### Sapphire Days — Visual Novel
Published visual novel built with **Ren'Py**, including branching routes, player choices, original soundtrack and releases for Windows, macOS and Linux.

---

## Technology stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,java,dart,kotlin,swift,cs,html,css&perline=10" alt="Languages"/>
</p>

### Frontend & Mobile

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,angular,tailwind,flutter&perline=8" alt="Frontend and Mobile"/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
</p>

### Backend & Integrations

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,spring&perline=8" alt="Backend"/>
</p>

- REST APIs
- WebSockets
- ERP OMIE
- D4Sign
- Marketplace integrations
- Amazon, Mercado Livre, Shopee and TikTok Shop workflows

### Data, Cloud & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,prisma,aws,docker,git,github,vercel,cloudflare,linux&perline=8" alt="Data Cloud and DevOps"/>
</p>

### AI / Machine Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=111111" alt="Transformers"/>
  <img src="https://img.shields.io/badge/Gemini_AI-222222?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini AI"/>
  <img src="https://img.shields.io/badge/Ollama-222222?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/>
</p>

- Transformer architectures
- LLM pre-training
- Supervised fine-tuning (SFT)
- RAG
- Local inference
- AI agents and workflow automation
- AI-assisted code review

---

## Education

### Bachelor of Science in Software Engineering
**Universidade Positivo — Curitiba, Brazil**  
Completed in **July 2026**

---

## Certifications & professional development

**OpenAI**
- Agents and Workflows — 2026

**Anthropic**
- AI Fluency for Builders — 2026
- AI Fluency for Small Businesses — 2026
- Introduction to Subagents — 2026
- AI Capabilities and Limitations — 2026
- AI Fluency Framework & Foundations — 2026

**Google**
- Generative AI Agents: Transform Your Organization — 2026
- Generative AI Apps: Transform Your Work — 2026
- Generative AI: Understand the Current Landscape — 2026
- Generative AI: Beyond the Chatbot — 2026
- Generative AI: Fundamentals — 2026

**NVIDIA**
- Getting Started with AI on Jetson Nano — 2026

**AWS preparation — Alura**
- AWS Cloud Practitioner: Domains 1 & 2 — 2026
- AWS Cloud Practitioner: Domains 3 & 4 — 2026

**Cisco**
- English for IT 1 — **B2 technical level**
- Endpoint Security

**Other highlights**
- ExxonMobil Data & Analytics Day — Universidade Positivo
- Leadership & Communication Workshop — Universidade Positivo
- Speaker at VIASOFT Connect
- TCS CodeVita Season 12 Master Class

---

## GitHub analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Camillox2&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=111827&text_color=374151&icon_color=6b7280&bg_color=ffffff" alt="Vitor's GitHub statistics"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Camillox2&layout=compact&hide_border=true&langs_count=8&title_color=111827&text_color=374151&bg_color=ffffff" alt="Most used languages"/>

</div>

> GitHub language statistics reflect public repositories and do not represent the full scope of my work in private and corporate codebases.

---

## Open to opportunities

I am interested in opportunities involving:

- **Full Stack Development**
- **Backend Engineering**
- **React / Next.js / Node.js**
- **Java / Spring Boot**
- **Python / AI / LLM Engineering**
- **Software Engineering**
- **Technical Leadership**, when aligned with the role's expected experience level

I am open to **CLT, contractor/PJ and freelance opportunities**, including remote and international teams.

<div align="center">

### Build useful software. Automate real problems. Apply AI where it creates measurable value.

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vitor-henrique-camillo)
[![Email](https://img.shields.io/badge/Contact%20Me-Email-333333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vitorcamilloh@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:374151,50:1f2937,100:111111&height=110&section=footer" width="100%"/>

</div>
