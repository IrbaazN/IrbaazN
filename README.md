<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:24243e&height=260&section=header&text=IRBAAZ%20NOOR&fontSize=60&fontColor=c4b5fd&animation=twinkling&fontAlignY=40&desc=agents%20that%20research%2C%20write%20%26%20argue%20until%20the%20answer%20is%20good&descAlignY=62&descSize=16&descColor=a5b4fc" alt="Irbaaz Noor" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=A78BFA&center=true&vCenter=true&width=760&height=40&lines=%24+whoami+%E2%86%92+Irbaaz+Noor;%24+building+%E2%86%92+multi-agent+LLM+pipelines;%24+retrieval+%E2%86%92+FAISS+%2B+Groq;%24+day+job+%E2%86%92+LLM+post-training+%40+Ethara+AI;%24+location+%E2%86%92+Delhi+NCR+%F0%9F%93%8D" alt="typing"/>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-irbaaz--noor-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/irbaaz-noor)
[![Email](https://img.shields.io/badge/Gmail-noorirbaaz-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorirbaaz@gmail.com)
[![Live Demo](https://img.shields.io/badge/▶_MARS-Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://irbaaz-multi-agent-ai-research-system.streamlit.app)

</div>

<br>

## `~/about`

```bash
irbaaz@delhi-ncr:~$ cat about.txt

  B.Tech CSE (AI) · Jamia Hamdard University · 2026
  Day job   : LLM post-training @ Ethara AI
  Side quest: building agentic AI systems that fact-check themselves
  Obsessed  : pipelines where one agent's job is to criticise another
  Status    : open to collaborations ✅
```

<br>

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

### 🤖 MARS
**Multi-Agent AI Research System**

I built a 4-agent LangGraph pipeline that takes any topic and returns a researched, critiqued report. The Critic keeps sending drafts back until they pass review.

`LangGraph` `LLaMA 3.1` `Groq` `Tavily` `BeautifulSoup` `Streamlit`

[▶ Live demo](https://irbaaz-multi-agent-ai-research-system.streamlit.app) · [{ } Code](https://github.com/IrbaazN/multi-agent-research-system)

</td>
<td width="50%" valign="top">

### 💬 SHL Recommender
**Conversational assessment finder**

I built an AI chatbot that helps HRs find the right SHL assessments through multi-turn conversation, using FAISS vector search and a Groq-hosted LLM.

`FastAPI` `FAISS` `Groq` `Python`

[{ } Code](https://github.com/IrbaazN/SHL-recommender)

</td>
</tr>
</table>

### 🔬 Inside MARS

```mermaid
flowchart LR
    T([📝 Topic]) --> S[🔎 Search<br/><i>Tavily</i>]
    S --> R[📖 Reader<br/><i>BeautifulSoup</i>]
    R --> W[✍️ Writer]
    W --> C{🧐 Critic}
    C -- "❌ revise" --> W
    C -- "✅ approved" --> OUT([📄 Report])

    classDef agent fill:#302b63,stroke:#a78bfa,color:#fff,stroke-width:2px
    classDef io fill:#0f0c29,stroke:#6366f1,color:#c4b5fd
    class S,R,W,C agent
    class T,OUT io
```

### 🔬 Inside SHL Recommender

```mermaid
flowchart LR
    H([👩‍💼 HR message]) --> Q[💭 Clarify<br/><i>multi-turn</i>]
    Q --> V[(🧭 FAISS<br/>vector search)]
    V --> L[⚡ Groq LLM]
    L --> A([✅ Assessment picks])

    classDef node fill:#302b63,stroke:#a78bfa,color:#fff,stroke-width:2px
    classDef io fill:#0f0c29,stroke:#6366f1,color:#c4b5fd
    class Q,V,L node
    class H,A io
```

<br>

## `~/lab` &nbsp;·&nbsp; <sub>smaller experiments</sub>

<details>
<summary>💳 <b>Credit Card Fraud Detection</b></summary>
<br>
I built an XGBoost + SMOTE model for heavily imbalanced transaction data, reaching 97%+ precision.
</details>

<details>
<summary>🩺 <b>Breast Cancer Prediction</b></summary>
<br>
I built a classification model on clinical features.
</details>

<details>
<summary>🎙️ <b>VidSnapAI</b></summary>
<br>
I built a Flask app that generates voiceovers with ElevenLabs.
</details>

<br>

## `~/stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,flask,streamlit,sklearn,pandas,numpy,git,github&theme=dark" alt="stack icons"/>
<br><br>

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge)

</div>

<br>

<div align="center">

```text
┌──────────────────────────────────────────────────────────────┐
│  "I like pipelines where the agents argue until it's right." │
└──────────────────────────────────────────────────────────────┘
```

**Let's build something agentic 👇**

[![Say hi](https://img.shields.io/badge/Say_hi-noorirbaaz@gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorirbaaz@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=110&section=footer" alt="footer" width="100%"/>

</div>
