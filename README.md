```text
███████╗███████╗██████╗  ██████╗ ██╗ ██████╗
██╔════╝██╔════╝██╔══██╗██╔════╝ ██║██╔═══██╗
███████╗█████╗  ██████╔╝██║  ███╗██║██║   ██║
╚════██║██╔══╝  ██╔══██╗██║   ██║██║██║   ██║
███████║███████╗██║  ██║╚██████╔╝██║╚██████╔╝
╚══════╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═╝ ╚═════╝
███╗   ███╗██╗   ██╗██████╗ ██╗██╗     ██╗      ██████╗
████╗ ████║██║   ██║██╔══██╗██║██║     ██║     ██╔═══██╗
██╔████╔██║██║   ██║██████╔╝██║██║     ██║     ██║   ██║
██║╚██╔╝██║██║   ██║██╔══██╗██║██║     ██║     ██║   ██║
██║ ╚═╝ ██║╚██████╔╝██║  ██║██║███████╗███████╗╚██████╔╝
╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝╚══════╝╚══════╝ ╚═════╝

 ▁▂▃▅▆▇█▇▆▅▃▂▁ ▁▂▄▆█▆▄▂▁ ▁▂▃▅▇█▇▅▃▂▁ ▁▂▄▆█▆▄▂▁ ▁▂▃▅▆▇█▇▆▅▃▂▁

 > AI Solutions Architect · Voice AI · Integrations
 > voice_agents.status()   ● 4 live   ● 650+ real conversations
```

<p align="center">
I turn real operational problems into AI solutions that run in production:<br>
voice agents connected to business systems, automation pipelines and SaaS products.
</p>

<p align="center">
  <a href="https://cv.sergiomurillo.com.ar/"><img src="https://img.shields.io/badge/Portfolio-Talk%20to%20my%20live%20agents-6de8ff?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/sergio-murillo-ai/"><img src="https://img.shields.io/badge/LinkedIn-sergio--murillo--ai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://inteliautomake.com"><img src="https://img.shields.io/badge/Inteliautomake-Founder-473BCE?style=for-the-badge" alt="Inteliautomake"></a>
</p>

---

### ⚡ In numbers

| 20+ years | 15+ MVPs | 30+ automations | 650+ conversations |
|:---:|:---:|:---:|:---:|
| building technology solutions | and 2 startups | running in production | handled by my voice agent Greicy |

---

### 🎙️ Voice agents you can try live

Real-time conversations built on **ElevenLabs Agents** + **WebRTC**. A backend issues short-lived session tokens, so the private API key never reaches the browser.

| Agent | What it does | Status |
|---|---|---|
| **Greicy** · Parque de la Paz | Customer-service agent connected to a database of 30,000+ customers. Explains each account in the conversation, emails the details, logs internal tickets and sends WhatsApp messages. 650+ real conversations since 2025. | 🟢 In production · [Try it](https://inteliautomake.com/parquedelapaz/QR/index.html) |
| **My AI agent** · Portfolio | Answers questions about my experience and projects, by voice or text | 🟢 Live · [Try it](https://cv.sergiomurillo.com.ar/) |
| **Custom Voice Agent UI** | My own widget on the `@elevenlabs/client` SDK: avatar, voice + text chat, agent profile loaded from my backend | 🟢 Live · [Try it](https://inteliautomake.com/agente4/public4/index.html) |
| **Botcats** | A feline assistant with a custom cat voice and personality (yes, it says "miauuu") that teaches owners how to prevent diabetes in cats | 🟢 Live · [See project](https://inteliautomake.com/OLLD/proyecto-botcats/index.html) |

**How Greicy works**

```mermaid
flowchart LR
    U[Customer] -->|voice| W[Web / web app]
    W -.->|requests session token| B[Backend]
    B -.->|short-lived token| W
    W -->|WebRTC| E[ElevenLabs Agent]
    E -->|custom webhook tools| N[n8n workflows]
    N --> DB[(Customer DB<br/>30,000+ accounts)]
    N --> M[Email]
    N --> WA[WhatsApp]
    N --> T[Internal tickets]
    E -->|spoken answer| U
```

---

### 🚀 Products I've built

**[Studio Media Labs](https://studiomedialabs.com/)** — Generative AI media production SaaS
Creator, architect and full-stack developer. Serverless, modular platform with an in-app AI agent, integrating the **ElevenLabs API for voice generation and music**.
🏅 Selected for pre-incubation at the Atlantis Technology Incubator, Universidad Nacional de Mar del Plata (July 2026) — one of 7 projects admitted in the technology category.
`ElevenLabs API` `Python` `TypeScript` `React` `React Flow` `Node.js` `Supabase` `Docker` `Cloudflare` `Railway`

**[AIQR]()** — AI agents behind QR codes
Puts conversational agents on products, signage, equipment and spaces: answers questions, qualifies leads and logs interactions.
`Next.js` `PostgreSQL` `Supabase`

---

### 🧰 Tech stack

**Voice AI & agents**
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-Agents%20%2B%20API-000000?style=flat-square&logo=elevenlabs&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Telnyx](https://img.shields.io/badge/Telnyx-00C08B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-555555?style=flat-square)
![RAG](https://img.shields.io/badge/RAG%20%2F%20CAG-555555?style=flat-square)

**Languages & frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Automation & integrations**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=flat-square&logo=zapier&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs%20%26%20Webhooks-555555?style=flat-square)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)

**Data, cloud & infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**AI models**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Replicate](https://img.shields.io/badge/Replicate-000000?style=flat-square&logo=replicate&logoColor=white)

---

### 🏗️ What I do

- **Design** voice and chat agents connected to the systems a business already runs: customer databases, email, WhatsApp, ticketing, telephony.
- **Demo** solutions to business and technical stakeholders, translating between both.
- **Deploy** from architecture to production: integrations, security, monitoring and iteration.
- **Enable** teams through training: speaker at Universidad Atlántida Argentina's technology conference (2025), trainer at the AIStars Foundation, and corporate workshops on AI agents.

Today I'm **Founder** of [Inteliautomake](https://inteliautomake.com), **CTO** at Parque de la Paz, and Head of the Technical Division for IT & Telecommunications at Universidad Nacional de Mar del Plata.

---

### 📜 Recent certifications

`AI Fluency for Educators — Anthropic (2026)` · `MCP: Automation in Production — Hugging Face (2026)` · `Fundamentals of MCP — Hugging Face (2025)` · `Long-Term Agentic Memory with LangGraph — DeepLearning.AI (2025)` · `Building Agentic RAG with LlamaIndex — DeepLearning.AI` · `Generative AI Bootcamp — AWS (2023)`

---

<p align="center">
📍 Mar del Plata, Argentina · 🌎 Remote with teams across LATAM and Europe · ✈️ Available to travel<br><br>
<a href="https://cv.sergiomurillo.com.ar/"><b>→ Talk to my AI agent on my portfolio</b></a>
</p>
