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

- 📞 **Production Arabic voice agents** — config-driven multi-tenant design, SIP telephony, speech-to-speech; we measured p50 latency falling from ~2.05 s to ~1.2 s in testing
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
      Bilingual RAG assistant with article-level citations — I built v1 (<a href="https://github.com/mohammed-elhaj/FinancialRag">repo</a>) and co-built the production platform.<br/><br/>
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

### 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,docker,kubernetes,gcp,aws,postgres,react,ts&theme=dark" alt="Tech stack"/>
</p>

<p align="center">
  <b>Voice:</b> LiveKit · SIP · Speechmatics · ElevenLabs · Gemini Live &nbsp;|&nbsp;
  <b>LLMs:</b> OpenAI · Gemini · Groq · open models &nbsp;|&nbsp;
  <b>Retrieval:</b> BM25 · dense · hybrid fusion · ChromaDB
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohammed-elhaj&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohammed-elhaj&layout=compact&hide_border=true&theme=tokyonight" height="165" alt="Top languages"/>
</p>

<p align="center"><i>"أبني وكلاء صوت يتكلمون العربية" — I build voice agents that speak Arabic.</i></p>
