# Hi there 👋 Hassan Khursheed | AI Engineer

## About Me

I’m a Computer Science graduate and an **AI Engineer** specializing in **Generative AI**, **Agentic AI** and **Workflow Automation**. I build LLM applications, multi-agent systems, RAG pipelines and n8n workflows with **LangChain** and **LangGraph**, designed with enterprise safeguards such as **PII protection**, **guardrails**, **human-in-the-loop approval**, **LLM evaluation** and **cost control**.

I also build **Python backends** with **FastAPI**, **PostgreSQL** and **Docker**, including secure **multi-tenant platforms for healthcare**, and have working knowledge of **web scraping**, **data analysis** and **machine learning**.

I’m always happy to connect about **AI Engineering** roles, collaborations and projects that turn manual business processes into reliable, automated systems.

---

### 📫 Let's Connect
- 📧 **Email:** hassankhursheed7878@gmail.com  
- 📍 **Location:** Lahore, Pakistan  
- 🔗 **LinkedIn:** [linkedin.com/in/hassankhursheed](https://www.linkedin.com/in/hassankhursheed)
- 🐙 **GitHub:** [github.com/hassankhursheed](https://github.com/hassankhursheed)  

---

## 🎓 Education

### **Bachelor of Science in Computer Science (BSCS)**
- **University of the Punjab (PU)**, Pakistan  
- **Duration:** 2020 – 2024  

---

## 💼 Work Experience

### **AI Engineer**
- **Vitruvia Technologies**, Lahore, Pakistan  
- **Duration:** Jun 2026 – Present  
- **Key Contributions:**  
  - Designed an end-to-end recruitment and onboarding automation with 13 n8n workflows, FastAPI and PostgreSQL, including human approval gates, an error queue with replay, a full audit trail and 261 tests at 90% coverage.  
  - Developed AI agents and multi-agent systems with LangGraph and Deep Agents, including human-in-the-loop control and short- and long-term memory persisted in PostgreSQL.  
  - Built advanced RAG systems to improve retrieval accuracy and reduce hallucinations: Agentic RAG, Corrective RAG, Self-RAG and vectorless RAG with PageIndex.  
  - Implemented guardrails to keep sensitive data and unsafe requests away from LLMs: PII redaction, harmful-request blocking and human approval of sensitive actions.  
  - Evaluated LLM apps in LangSmith and Langfuse, achieving 100% usable outputs in a 36-case AI evaluation, and set up a LiteLLM gateway for fallbacks, routing and cost tracking.  
  - Automated business workflows in n8n across Google Workspace, Supabase, Telegram and WhatsApp, including AI email drafting with human approval and calendar and task assistants.

### **Associate Software Engineer AI**
- **Vitruvia Technologies**, Lahore, Pakistan  
- **Duration:** Nov 2025 – Jun 2026  
- **Key Contributions:**  
  - Developed and maintained FastAPI backend features for a multi-tenant DICOM medical imaging platform serving hospitals and clinics.  
  - Raised backend test coverage from 41% to 83% with Pytest tests for all API endpoints, core services and Celery background jobs, including DICOM delivery and cloud archiving.  
  - Delivered 7 product requirements for hospital and clinic accounts, including demo workflow, subscription packages, storage purchasing, medical data archiving and renewal notifications with email alerts.  
  - Built a shared MinIO storage pool for medical imaging data with per-tenant limits, full data isolation between healthcare providers, on-demand allocation and admin alerts at 85% and 90%.  
  - Built admin controls for hospital and clinic accounts: usage tracking, Extend/Pause/Logs actions, Stripe payments with transaction history, and 5-sheet Excel usage reports with audit logs.

### **Freelance Online Seller**
- **Facebook Marketplace**, UK & Europe  
- **Duration:** Nov 2023 – Sep 2025  
- **Key Contributions:**  
  - Sold multiple products to customers across the UK and Europe.

### **Flutter Developer Intern**
- **Punjab Information Technology Board (PITB)**, Lahore, Pakistan  
- **Duration:** Jul 2024 – Aug 2024  
- **Key Contributions:**  
  - Developed and tested mobile application features.

### **Flutter Developer Intern**
- **bVoir Technologies**, Jhelum, Pakistan  
- **Duration:** Aug 2023 – Nov 2023  
- **Key Contributions:**  
  - Built responsive Flutter UIs and integrated Firebase authentication and database.

---

## 🛠️ Skills

- **Programming Languages:** Python, SQL  
- **Generative AI:** LangChain, Prompt Engineering, Structured Outputs, Tool Calling, Embeddings  
- **Agentic AI:** LangGraph, Multi-Agent Systems, ReAct Agents, Human-in-the-Loop, Memory & Persistence, Deep Agents  
- **RAG:** Agentic RAG, Corrective RAG, Self-RAG, Vectorless RAG (PageIndex), Advanced Retrievers, Chroma, FAISS  
- **LLMOps & Safety:** LangSmith, Langfuse (tracing, monitoring & evaluation), LiteLLM (LLM gateway), Guardrails, PII Redaction  
- **LLM Providers:** OpenAI, Anthropic (Claude), Google Gemini, Mistral AI, Hugging Face, Ollama (local LLMs)  
- **Workflow Automation:** n8n, Webhooks, API Integration, Error Handling & Retries, Google Workspace (Gmail, Sheets, Calendar, Tasks), Telegram, WhatsApp  
- **Backend:** FastAPI, REST APIs, SQLAlchemy, SQLModel, Alembic, Celery, Redis, JWT Auth, Multi-tenancy, Stripe  
- **Databases & Storage:** PostgreSQL, SQLite, Supabase, MinIO  
- **DevOps, Testing & Tools:** Git, GitHub, Docker, Docker Compose, Render, Pytest, Unit, Integration & White-box Testing, Claude Code, Cursor  
- **Frontend:** Familiar with React, Next.js, TypeScript, Tailwind CSS, Streamlit, HTML/CSS  
- **Web Scraping:** Requests, BeautifulSoup, API-based Data Extraction, JSON/CSV Export  
- **Data Analysis:** NumPy, Pandas, Matplotlib, Seaborn, EDA, Data Cleaning, Feature Engineering, Hypothesis Testing  
- **Machine Learning:** Scikit-learn, XGBoost, Regression, Classification, Clustering (K-means, DBSCAN), Model Evaluation, Hyperparameter Tuning, Ensemble Methods (Bagging, Boosting, Stacking)  

---

## 🚀 Projects

1. **[AI Hiring & Onboarding Automation](https://github.com/hassankhursheed/novatech-hiring-automation)**  
   - Takes candidates from application to first working day: rule-based CV scoring, advisory AI review, interview booking, HR-approved PDF offers and onboarding tasks.  
   - Runs on 13 n8n workflows with FastAPI, PostgreSQL, React, Mistral AI and Langfuse, with automatic retries, an error queue with replay, a full audit trail and 261 tests at 90% coverage.  

2. **[Multi-Agent AI Research System](https://github.com/hassankhursheed/multi_agent_research_system)** · [Live demo](https://multi-agent-research-system1.onrender.com)  
   - Agents research any topic and generate a final research report and a critic report, downloadable by the user.  
   - Built with LangChain, Mistral AI, Tavily and Streamlit, and deployed on Render.  

3. **[Radiology Report Management System](https://github.com/hassankhursheed/radiology-report-management-system)**  
   - Create, search, update and delete medical reports, export them to Word and re-upload edited files to update records.  
   - QR codes for online report viewing and a blood test reports page, built with FastAPI, PostgreSQL and python-docx.  

4. **[SaaS Subscription Flow with Stripe](https://github.com/hassankhursheed/saas-subscription-flow-fastapi-stripe)**  
   - Package selection, sign-up and sign-in, Stripe payment and confirmation, with a dashboard for returning subscribers.  
   - Built with FastAPI, PostgreSQL and an HTML, CSS and JavaScript frontend.  

5. **[Multi-Tenant Healthcare System](https://github.com/hassankhursheed/multi-tenant-healthcare-jwt-system)**  
   - Single-database system for multiple hospitals and clinics with JWT auth and isolated tenant data, where each tenant manages its own staff users and roles.  
   - A FastAPI REST API and a Streamlit dashboard on PostgreSQL with SQLAlchemy.  

6. **[Weather Data Scraper API](https://github.com/hassankhursheed/secure-weather-scraper-fastapi-streamlit)** · [Live API](https://vitruvia-tech-scraper-4.onrender.com/docs)  
   - API-based scraper with a login-protected Streamlit UI that fetches city weather as JSON and exports it to CSV or JSON.  
   - Saves every lookup to SQLite and exposes an API-key-secured REST endpoint deployed on Render.  

7. **[ML & Web Scraping Projects](https://github.com/hassankhursheed/vitruvia_tech)**  
   - Booking.com and Amazon scrapers, a heart disease prediction app, and machine learning notebooks for regression, classification, ensembles and clustering.  
   - A FastAPI product API with Pydantic validation.  

---

## 💡 Interests

I enjoy turning manual business processes into reliable, automated systems, and keeping up with new work in agentic AI, LLM evaluation and AI safety. Next on my list: voice AI, OCR and document AI.
