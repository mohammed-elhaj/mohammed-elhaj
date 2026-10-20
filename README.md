<p align="center">
  <img src="assets/banner.svg" alt="Mohammed Elhaj — AI Engineer, real-time Arabic voice AI" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=640&lines=I+build+voice+agents+that+speak+Arabic;Real-time+STT+%E2%86%92+LLM+%E2%86%92+TTS+over+SIP;RAG+%2B+evals+for+Arabic+retrieval;From+first+prototype+to+production" alt="Typing tagline"/></a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/mohammedelhaj"><img src="https://img.shields.io/badge/LinkedIn-mohammedelhaj-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mohamedelhaj2000@gmail.com"><img src="https://img.shields.io/badge/Email-say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-KSA%20%C2%B7%20Remote-22C55E?style=for-the-badge" alt="Open to KSA and remote"/>
</p>

---

### 🎙️ About me

```python
class MohammedElhaj:
    role       = "AI Engineer"
    focus      = ["real-time Arabic voice agents", "LLM agents", "RAG", "evaluation"]
    based_in   = "Omdurman, Sudan 🇸🇩"
    languages  = {"Arabic": "native", "English": "fluent"}
    education  = "BSc Electrical & Electronic Eng., University of Khartoum — First Class Honours (2026)"

    def now(self):
        return "AI Engineer (contract) at a US healthcare-AI startup"

    def before(self):
        return {
            "Sofof Tech  (2025–26)": "led the real-time voice platform — SIP telephony, multi-provider STT/LLM/TTS failover",
            "Fatoorah.ai (2025)":    "led a multi-tenant voice-agent SaaS — tools framework, observability",
        }
```

### ⚡ Highlights

- 📞 **Production Arabic voice agents that act** — inbound & outbound calls over SIP, tool calls into customers' APIs, config-driven multi-tenant design, speech-to-speech; we measured p50 latency falling from ~2.05 s to ~1.2 s in testing
- 🚀 **Shipped, not just prototyped** — voice platforms, a [procurement-law assistant](https://muan.sa/) and document-AI systems running in production
- 🧪 **Evals first** — post-call analytics passing 8/8 pre-set targets on a 25-scenario Arabic benchmark
- 🧾 **Document AI** — vision-LLM invoice extraction: **0.82 F1 vs 0.60** for Google Document AI on 42 human-labelled invoices
- 🔎 **Research** — Arabic RAG query enhancement: **+54.5% nDCG@10 over BM25** on MIRACL-Arabic (2.06M passages); paper in preparation with [@Osmanoor](https://github.com/Osmanoor)
- 👥 Mentored 5 junior AI engineers · taught a 3-session Arabic workshop on voice agents · IndabaX Sudan speakers team

---

### 🛠️ Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🎤 <a href="https://github.com/mohammed-elhaj/eeexplore-voice-ai-workshop">Real-Time Voice AI Workshop</a></h4>
      Open-source Arabic course: build a voice agent that listens, thinks and speaks, then give it tools, RAG and web search. Free-tier stack so any student can follow.<br/><br/>
      <img src="https://img.shields.io/badge/LiveKit-Agents-1F2937?style=flat-square" alt="LiveKit"/> <img src="https://img.shields.io/badge/ElevenLabs-TTS-1F2937?style=flat-square" alt="ElevenLabs"/> <img src="https://img.shields.io/badge/Gemini-LLM-1F2937?style=flat-square" alt="Gemini"/>
    </td>
    <td width="50%" valign="top">
      <h4>📚 <a href="https://github.com/Osmanoor/arabic-rag-query-enhancement">Arabic RAG Query Enhancement</a></h4>
      BSc thesis: sparse and dense retrievers react oppositely to LLM query expansion, so we route them asymmetrically. 10 open LLMs (2B–8B) benchmarked.<br/><br/>
      <img src="https://img.shields.io/badge/BM25-+%20Dense-1F2937?style=flat-square" alt="BM25"/> <img src="https://img.shields.io/badge/MIRACL-Arabic-1F2937?style=flat-square" alt="MIRACL"/> <img src="https://img.shields.io/badge/nDCG@10-0.714-1F2937?style=flat-square" alt="nDCG@10"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚖️ <a href="https://muan.sa/">Saudi Procurement-Law Assistant</a></h4>
      Bilingual RAG assistant for Saudi procurement law, live in production: answers with article-level citations, document search and a WhatsApp channel.<br/><br/>
      <img src="https://img.shields.io/badge/RAG-citations-1F2937?style=flat-square" alt="RAG"/> <img src="https://img.shields.io/badge/ChromaDB-1F2937?style=flat-square" alt="ChromaDB"/> <img src="https://img.shields.io/badge/Cloud%20Run-1F2937?style=flat-square" alt="Cloud Run"/>
    </td>
    <td width="50%" valign="top">
      <h4>🖼️ <a href="https://github.com/mohammed-elhaj/multimodal-RAG">Multimodal RAG Agent</a></h4>
      A vision LLM turns PDF pages into a structured knowledge base; answers come with the source page image as a citation.<br/><br/>
      <img src="https://img.shields.io/badge/Gemini%202.5%20Pro-vision-1F2937?style=flat-square" alt="Gemini 2.5 Pro"/> <img src="https://img.shields.io/badge/GPT--4o-1F2937?style=flat-square" alt="GPT-4o"/> <img src="https://img.shields.io/badge/Streamlit-1F2937?style=flat-square" alt="Streamlit"/>
    </td>
  </tr>
</table>

---

### 📞 What I build: voice agents that take action

```mermaid
flowchart LR
    C(["📱 Caller"]) <-->|inbound / outbound SIP| A["🎙️ Real-time voice agent<br/>STT → LLM → TTS<br/>with provider failover"]
    A -->|tool calls| T["🔧 Customer systems<br/>APIs · CRMs · bookings"]
    T -->|results| A
    A --> O["📊 Recordings · transcripts<br/>latency & post-call analytics"]
```

---

### 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,fastapi,flask,pytorch,docker,kubernetes,gcp,aws,nginx,postgres,react,nextjs,vercel&theme=dark" alt="Tech stack"/>
</p>

<table>
  <tr>
    <td width="22%"><b>📞 Voice &amp; telephony</b></td>
    <td><img src="https://img.shields.io/badge/LiveKit%20Agents-1F2937?style=flat-square&logo=livekit&logoColor=white" alt="LiveKit Agents"/> <img src="https://img.shields.io/badge/SIP%20inbound%20/%20outbound-1F2937?style=flat-square" alt="SIP inbound / outbound"/> <img src="https://img.shields.io/badge/Speech--to--speech-1F2937?style=flat-square" alt="Speech-to-speech"/> <img src="https://img.shields.io/badge/Speechmatics-1F2937?style=flat-square" alt="Speechmatics"/> <img src="https://img.shields.io/badge/ElevenLabs-1F2937?style=flat-square&logo=elevenlabs&logoColor=white" alt="ElevenLabs"/> <img src="https://img.shields.io/badge/Gemini%20Live-1F2937?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini Live"/> <img src="https://img.shields.io/badge/Silero%20VAD-1F2937?style=flat-square" alt="Silero VAD"/> <img src="https://img.shields.io/badge/WebSockets%20streaming-1F2937?style=flat-square" alt="WebSockets streaming"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🤖 Agents that act</b></td>
    <td><img src="https://img.shields.io/badge/Tool%20calling-1F2937?style=flat-square" alt="Tool calling"/> <img src="https://img.shields.io/badge/Customer%20APIs%20%26%20webhooks-1F2937?style=flat-square" alt="Customer APIs & webhooks"/> <img src="https://img.shields.io/badge/Multi--tenant%20config--driven%20agents-1F2937?style=flat-square" alt="Multi-tenant config-driven agents"/> <img src="https://img.shields.io/badge/Provider%20failover-1F2937?style=flat-square" alt="Provider failover"/> <img src="https://img.shields.io/badge/Telegram-1F2937?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/> <img src="https://img.shields.io/badge/WhatsApp-1F2937?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🧠 LLMs</b></td>
    <td><img src="https://img.shields.io/badge/OpenAI-1F2937?style=flat-square&logo=openai&logoColor=white" alt="OpenAI"/> <img src="https://img.shields.io/badge/Gemini-1F2937?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/> <img src="https://img.shields.io/badge/Groq-1F2937?style=flat-square" alt="Groq"/> <img src="https://img.shields.io/badge/Open%20models%202B%E2%80%938B-1F2937?style=flat-square" alt="Open models 2B–8B"/> <img src="https://img.shields.io/badge/Structured%20outputs-1F2937?style=flat-square" alt="Structured outputs"/> <img src="https://img.shields.io/badge/LangChain-1F2937?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🔎 RAG &amp; document AI</b></td>
    <td><img src="https://img.shields.io/badge/BM25%20%2B%20dense%20hybrid-1F2937?style=flat-square" alt="BM25 + dense hybrid"/> <img src="https://img.shields.io/badge/ChromaDB-1F2937?style=flat-square" alt="ChromaDB"/> <img src="https://img.shields.io/badge/Vision--LLM%20extraction-1F2937?style=flat-square" alt="Vision-LLM extraction"/> <img src="https://img.shields.io/badge/Google%20Vision-1F2937?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Vision"/> <img src="https://img.shields.io/badge/Tesseract%20OCR-1F2937?style=flat-square" alt="Tesseract OCR"/> <img src="https://img.shields.io/badge/OpenCV-1F2937?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🧪 Evals &amp; observability</b></td>
    <td><img src="https://img.shields.io/badge/Scenario%20benchmarks-1F2937?style=flat-square" alt="Scenario benchmarks"/> <img src="https://img.shields.io/badge/P%20/%20R%20/%20F1-1F2937?style=flat-square" alt="P / R / F1"/> <img src="https://img.shields.io/badge/nDCG%4010-1F2937?style=flat-square" alt="nDCG@10"/> <img src="https://img.shields.io/badge/Latency%20instrumentation-1F2937?style=flat-square" alt="Latency instrumentation"/> <img src="https://img.shields.io/badge/Langfuse-1F2937?style=flat-square" alt="Langfuse"/> <img src="https://img.shields.io/badge/Call%20recordings%20%26%20logs-1F2937?style=flat-square" alt="Call recordings & logs"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🚀 Shipping to production</b></td>
    <td><img src="https://img.shields.io/badge/FastAPI-1F2937?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/Flask-1F2937?style=flat-square&logo=flask&logoColor=white" alt="Flask"/> <img src="https://img.shields.io/badge/Docker-1F2937?style=flat-square&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Kubernetes%20/%20GKE-1F2937?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes / GKE"/> <img src="https://img.shields.io/badge/Cloud%20Run-1F2937?style=flat-square&logo=googlecloud&logoColor=white" alt="Cloud Run"/> <img src="https://img.shields.io/badge/AWS%20EC2%20/%20S3-1F2937?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS EC2 / S3"/> <img src="https://img.shields.io/badge/nginx-1F2937?style=flat-square&logo=nginx&logoColor=white" alt="nginx"/> <img src="https://img.shields.io/badge/PostgreSQL-1F2937?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/React-1F2937?style=flat-square&logo=react&logoColor=white" alt="React"/> <img src="https://img.shields.io/badge/Next.js-1F2937?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/Vercel-1F2937?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/></td>
  </tr>
  <tr>
    <td width="22%"><b>🔥 ML</b></td>
    <td><img src="https://img.shields.io/badge/PyTorch-1F2937?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/Hugging%20Face-1F2937?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/> <img src="https://img.shields.io/badge/YOLOv8-1F2937?style=flat-square" alt="YOLOv8"/> <img src="https://img.shields.io/badge/MediaPipe-1F2937?style=flat-square&logo=mediapipe&logoColor=white" alt="MediaPipe"/></td>
  </tr>
</table>
