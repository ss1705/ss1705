# Hey, I'm Shwetha 👋
Graduate CS student at USC, working at the intersection of data engineering, ML, and software systems: building things that retrieve, rank, recommend, and run reliably in production.

## 🧠 About Me
- 🎓 MS Computer Science @ University of Southern California, graduating May 2027
- 💼 Business Data & Operations Analyst @ USC Hospitality BDO: SQL reporting over a 1.3M+ transactions/semester POS database, Power Automate workflow automation, and a Copilot Studio troubleshooting assistant in progress
- 💼 Previously: AI Engineer Intern @ Hyperionsoft: shipped a production drug-property prediction service on GCP Cloud Run (60% faster cold start, 83% smaller container)
- 💼 Previously: Data Engineering Intern @ Cloud Destinations: dbt on Redshift, ETL with AWS Glue
- 📍 Based in Los Angeles, CA

## 🔭 Projects
- **[AI Macro-Tracking Agent]**: LLM meal-logging agent on live USDA data with 7 tools across 3 MCP servers (1 custom), deployed on Cloud Run. Cut multi-food request latency up to 73% (25.7s → 6.9s) by redesigning the MCP client around long-lived sessions, benchmarked 4 LLM configurations, and added provider failover (11.9s recovery). A fault-injection MCP server exposed hangs and a startup crash, now fixed and covered by an 81-test suite
- **[Job Application Tracker]**: Self-hosted FastAPI + SQLite tool that turns Gmail job emails into a tracked pipeline with scheduled sync, deadline extraction, and a digest. A hybrid rule + LLM parser lifted status accuracy from 55% to 85% on 95 held-out emails (labeled blind against a frozen parser)
- **[NYC Taxi Streaming Pipeline](https://github.com/ss1705/nyc-taxi-streaming-pipeline)**: Replays ~3,000 historical NYC taxi trips through Kafka (KRaft) into PySpark Structured Streaming (10s micro-batches) and DuckDB, modeled in a 3-layer dbt project with 5 passing tests; Streamlit dashboard deployed on Railway
- **[Mood2Music](https://github.com/ss1705/Mood2Music)**: Mood-aware music recommender over 11.9K tracks: FAISS retrieval plus a CLAP audio + valence-energy reranker that lifted genre diversity ~48% over text-only across 120 queries. FastAPI backend with Modal GPU inference. Live at [mood2-music.vercel.app](https://mood2-music.vercel.app)
- **Task-Aware Orchestration for LLM Councils**: Research on task-aware LLM routing; built evaluation tooling for accuracy, latency, and cost across 12 LLMs, 5 benchmarks, and 4 routing policies on USC CARC HPC
- **SDOH Bias in LLM Clinical Responses**: Prompt-based bias evaluation across 3 LLMs and 5 SDOH conditions on 4 clinical dimensions (450 scored responses); presented at ShowCAIS 2026, USC

## 🛠️ Tech Stack
**Languages:** Python · SQL · Java · C++ · TypeScript · JavaScript  
**Frameworks & Libraries:** FastAPI · Flask · React · PyTorch · HuggingFace · Sentence-Transformers · CLAP · FAISS · LangGraph · pytest  
**Cloud & DevOps:** GCP (Cloud Run, Cloud Build, Firestore) · AWS (S3, Glue, Redshift) · Docker · Terraform · GitHub Actions CI/CD · Modal · Railway · Vercel  
**Data:** PostgreSQL · MySQL · SQLite · MongoDB · DuckDB · dbt · Kafka · PySpark · Streamlit  
**AI-Assisted Dev:** Claude Code · OpenAI Codex · MCP

## 📚 Interests
- Retrieval and recommendation systems
- Tool-use agents and multi-LLM orchestration
- LLM evaluation, fairness, and bias

## 📫 Let's Connect
[LinkedIn](https://www.linkedin.com/in/shwetha-sada) · Feel free to explore my repos or reach out!
