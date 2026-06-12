<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&customColorList=2,12,20&text=Welcome%20to%20Ha%20Lim's%20GitHub&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%7C%20Full%20Stack%20Developer&descAlignY=58&descSize=18" width="100%">
</p>

<h2 align="center">Hi, I'm Ha Lim 👋</h2>

<p align="center">
  CS major working at the intersection of <strong>AI agents and the web</strong>.<br/>
  I don't just use AI — I build the guardrails and products that make it dependable.<br/><br/>
  🛡️ Currently building <a href="https://github.com/hyde0395/grounded"><strong>grounded</strong></a> — a deterministic guardrail that makes AI coding agents prove it before they act.
</p>

---

## 🤖 What I'm Focused On

### 🧠 AI / Machine Learning

- **AI Agent Reliability** — guardrails and hooks that enforce evidence-based agent behavior
- **LLM & Prompt Engineering** — building with large language models, beyond the happy path
- **RAG (Retrieval-Augmented Generation)** — document-grounded AI chatbots
- **LangChain / LlamaIndex** — AI application pipelines

### 🌐 Web Development

- **React / Next.js** — server-side rendering and full-stack web apps
- **TypeScript** — type-safe frontend development
- **AI-powered Web Apps** — web services built on LLM APIs

---

## 🗂️ Projects

### 🛡️ grounded — Claude Code plugin
> **Make AI coding agents prove it before they act.**

A deterministic guardrail that blocks *ungrounded* agent actions — editing files it never read (including `sed -i` / `tee` shell bypasses), installing hallucinated packages, citing dead links. No LLM in the loop: just hooks, a
local evidence ledger, and exit codes.

- **Why it exists** — a USENIX Security '25 study found **5.2–21.7% of LLM-recommended packages dong" attack surface); grounded closes it at the moment of `install`
- **How** — a PostToolUse hook accrues evidence (files read, URLs fetched, registry checks) into a session ledger; a PreToolUse hook blocks actions that have none, feeding the reason back so the agent self-corrects
- **Engineering** — Python stdlib only, 210 offline tests, false-positives-are-worse-than-misses der path

<a href="https://github.com/hyde0395/grounded">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=hyde0395&repo=grounded&theme=tokyonight" />
</a>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square"/>
</p>

### ✈️ Flight Fare Forecast — when to buy Korea–Japan tickets
> **A NeuralProphet + XGBoost hybrid that predicts the optimal purchase moment for airfare.**

University AI project built on **18,472 rows** of real fare data I collected daily via SerpApi — answering "buy now, or wait?"

**Model**
NeuralProphet (per-route seasonality, base fare) + XGBoost (residuals: lead time, carrier, holidays
final price = exp( log(base fare) + XGB_log_residual )

**Performance** (18,472 rows / 6 Korea–Japan routes)

| Evaluation | R² | MAE |
|---|---|---|
| TimeSeriesSplit (production) | 0.713 | ₩34,017 |
| GroupKFold NO-lookup (academic) | 0.673 | ₩34,879 |

- Daily automated collection via GitHub Actions → accumulating data pipeline
- Conformal Prediction (CQR) for 80% prediction intervals — 81.2% coverage achieved
- Streamlit dashboard visualizing BUY / WAIT / DROP action plans
- SHAP explanations per prediction (carrier, holiday, FX contributions)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=whit
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColo
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

---

## 💼 Experience

### Ohble — Frontend Developer

Frontend developer at the startup **Ohble**.

- Built a React-based promotion website and a data-analytics dashboard
- Shipped and operated services in production

<p>
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_promotion_websit
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_promotion_website(1).png" width="28%">
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_analysis_website
</p>

---

## 🛠️ Tech Stack

**AI / Data**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColo
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logo
</p>

**Frontend / Web**
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoCo
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

**Tools & Infra**
<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=whit
  <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoCo
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hyde0395&theme=tokyonight&show_iconue&custom_title=GitHub%20Stats" height="180em"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hyde0395&theme=tokyonight&layout=compact&langs_count=8" height="180em"/>
</p>

---

## 📫 Contact

<p>
  <a href="https://www.linkedin.com/in/choi-ha-lim-97326a268/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColo
  </a>
  <a href="mailto:apologus0395@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>
