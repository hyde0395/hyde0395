<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&customColorList=2,12,20&text=Welcome%20to%20Ha%20Lim's%20GitHub&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%7C%20Full%20Stack%20Developer&descAlignY=58&descSize=18" width="100%">
</p>

<h2 align="center">Hi, I'm Ha Lim 👋</h2>

<p align="center">
  <a href="https://hits.seeyoufarm.com">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhyde0395&count_bg=%230A0047&title_bg=%23004687&icon=github.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false"/>
  </a>
</p>

<p align="center">
  컴퓨터공학을 전공하고, AI와 웹 개발을 공부하고 있는 개발자입니다.<br/>
  단순히 AI를 사용하는 것을 넘어, <strong>AI를 웹 서비스에 자연스럽게 녹여내는 풀스택 개발자</strong>가 목표입니다.
</p>

---

## 🤖 What I'm Focused On

### 🧠 AI / Machine Learning

- **LLM & Prompt Engineering** — Large Language Model 활용 및 프롬프트 최적화
- **RAG (Retrieval-Augmented Generation)** — 문서 기반 AI 챗봇 구현
- **LangChain / LlamaIndex** — AI 애플리케이션 파이프라인 구축
- **AI Agent** — 자율적으로 작업을 수행하는 AI 에이전트 개발

### 🌐 Web Development

- **React / Next.js** — 서버사이드 렌더링 및 풀스택 웹 앱 개발
- **TypeScript** — 타입 안정성을 갖춘 프론트엔드 개발
- **AI-powered Web Apps** — LLM API를 활용한 웹 서비스 개발

---

## 💼 Experience

### Ohble — Frontend Developer

스타트업 **Ohble**에서 프론트엔드 개발자로 활동했습니다.

- React 기반 프로모션 웹사이트 및 데이터 분석 대시보드 개발
- 실서비스 운영 및 배포 경험

<p>
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_promotion_website.png" width="28%">
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_promotion_website(1).png" width="28%">
  <img src="https://raw.githubusercontent.com/hyde0395/hyde0395/master/works/ohble_analysis_website.png" width="28%">
</p>

---

## 🗂️ Projects

### ✈️ 항공권 최저가 예측 시스템
> **NeuralProphet + XGBoost 하이브리드 모델로 한-일 노선 항공권의 최적 구매 시점을 예측합니다.**

수원대학교 컴퓨터SW학과 AI 프로젝트. SerpApi로 직접 수집한 **18,472행** 실데이터를 기반으로 "지금 살지, 기다릴지"를 예측합니다.

**모델 구조**
```
NeuralProphet (노선별 계절성·기저가) + XGBoost (잔차: 예약시점·항공사·공휴일·환율)
최종 예측가 = exp( log(기저가) + XGB_log_residual )
```

**성능** (18,472행 / 6개 한-일 노선 / 2026-06-07 기준)

| 평가 방식 | R² | MAE |
|---|---|---|
| TimeSeriesSplit (운영 기준) | 0.713 | 34,017원 |
| GroupKFold NO-lookup (학술 기준) | 0.673 | 34,879원 |

**주요 기술**
- GitHub Actions로 매일 자동 수집 → 데이터 누적 파이프라인
- Conformal Prediction(CQR)으로 80% 예측 구간 제공 (커버리지 81.2% 달성)
- Streamlit 대시보드로 BUY / WAIT / DROP 액션 플랜 시각화
- SHAP으로 개별 예측 해석 (항공사·공휴일·환율 기여도 분해)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

---

## 🛠️ Tech Stack

**AI / Data**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</p>

**Frontend / Web**
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

**Tools & Infra**
<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hyde0395&theme=tokyonight&show_icons=true&include_all_commits=true&custom_title=GitHub%20Stats" height="180em"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hyde0395&theme=tokyonight&layout=compact&langs_count=8" height="180em"/>
</p>

---

## 📫 Contact

<p>
  <a href="https://www.linkedin.com/in/choi-ha-lim-97326a268/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://www.instagram.com/harim_chicken03/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white"/>
  </a>
  <a href="mailto:apologus0395@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>
