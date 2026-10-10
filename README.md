<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Irbaaz%20Noor&fontSize=54&fontColor=c4b5fd&fontAlignY=38&desc=I%20build%20agentic%20AI%20systems&descAlignY=60&descSize=18&descColor=a5b4fc" alt="Irbaaz Noor banner" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=A78BFA&center=true&vCenter=true&width=760&height=40&lines=Multi-agent+LLM+pipelines;RAG+with+FAISS+%2B+Groq;LLM+post-training+at+Ethara+AI;Delhi+NCR+%F0%9F%93%8D" alt="typing intro"/>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-irbaaz--noor-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/irbaaz-noor)
[![Email](https://img.shields.io/badge/Gmail-noorirbaaz-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorirbaaz@gmail.com)
[![Live Demo](https://img.shields.io/badge/▶_MARS-Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://irbaaz-multi-agent-ai-research-system.streamlit.app)

</div>

<br>

## 🧠 About Me

```python
class AIEngineer:
    def __init__(self):
        self.name       = "Irbaaz Noor"
        self.location   = "Delhi NCR, India"
        self.role       = "LLM Post-Training @ Ethara AI"
        self.focus      = ["Multi-Agent AI", "RAG Systems", "LLM Evaluation"]
        self.stack      = ["Python", "LangGraph", "FastAPI", "FAISS", "Groq"]
        self.philosophy = "Impactful AI solves real problems for real people."

    def currently(self):
        return {
            "building" : "Agentic pipelines & RAG chatbots",
            "exploring": "Multi-agent orchestration, retrieval, LLM evals",
            "open_to"  : "Collaborations, open-source, exciting AI projects"
        }

me = AIEngineer()
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

<details>
<summary>🔬 <b>How MARS works</b> (click to expand)</summary>
<br>

```mermaid
flowchart TD
    T([Topic]) --> S[Search<br/>Tavily]
    S --> R[Reader<br/>BeautifulSoup]
    R --> W[Writer]
    W --> C{Critic}
    C -- revise --> W
    C -- approved --> OUT([Final report])

    classDef agent fill:#302b63,stroke:#a78bfa,color:#fff,stroke-width:2px
    classDef io fill:#0f0c29,stroke:#6366f1,color:#c4b5fd
    class S,R,W,C agent
    class T,OUT io
```

</details>

<details>
<summary>🔬 <b>How SHL Recommender works</b> (click to expand)</summary>
<br>

```mermaid
flowchart TD
    H([HR message]) --> Q[Clarify<br/>multi-turn]
    Q --> V[(FAISS<br/>vector search)]
    V --> L[Groq LLM]
    L --> A([Assessment picks])

    classDef node fill:#302b63,stroke:#a78bfa,color:#fff,stroke-width:2px
    classDef io fill:#0f0c29,stroke:#6366f1,color:#c4b5fd
    class Q,V,L node
    class H,A io
```

</details>

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

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

<div align="center">

**Let's build something agentic 👇**

[![Say hi](https://img.shields.io/badge/Say_hi-noorirbaaz@gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorirbaaz@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=110&section=footer" alt="footer" width="100%"/>

</div>
