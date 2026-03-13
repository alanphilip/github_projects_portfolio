# 🧑‍💻 Multi-Agent PDLC Assistant

A Streamlit-based web application that leverages multi-agent workflows to assist with **Project Development Life Cycle (PDLC)** tasks.  

The app extracts structured requirements, analyzes risks, advises on design, and provides recruiter-facing dashboards — all backed by Pinecone vector storage and automated CI/CD deployment on Azure.

This project demonstrates **multi-agent orchestration, long-context memory, and AI-driven innovation** — aligning with cutting-edge enterprise AI practices.

--- 

## 🚀 Features

- **Requirement Extractor**: Parses project specs or Jira-style tickets into structured fields (title, description, priority, dependencies, risk keywords).
- **Design Advisor**: Suggests design patterns and technical approaches based on requirements.
- **Risk Analyzer**: Flags potential risks (security, scalability, compliance) with severity levels.
- **Long-Context Memory**: Stores past requirements and decisions in Pinecone for conflict detection.
- **Dashboard**: Interactive Streamlit UI with:
    - Dashboard summary
    - Priority distribution visualization
    - CSV export
- **Requirement Management**:
    - Add Requirement
    - Search Requirement
    - Browse All Requirements

---

## 🛠️ Tech Stack

- **Frontend/UI**: [Streamlit](https://streamlit.io/)
- **Multi-Agent Framework**: Custom Python agents orchestrated for PDLC tasks
- **Database**: [Pinecone](https://www.pinecone.io/) for vector storage and semantic search
- **Containerization**: Docker (tested locally and deployed)
- **Cloud Deployment**: Azure App Service (Web App for Containers)
- **CI/CD**: GitHub Actions (automated Docker build, push to Azure Container Registry, redeploy)
- **Monitoring**: Azure Monitor for performance validation
- **Languages/Libs**: Python, pandas, altair, spaCy (planned upgrade to LangChain/HuggingFace Transformers)

---

## 📦 Deployment Journey

1. Built the **Multi-Agent PDLC Assistant** Streamlit app.
2. Containerized the app with Docker and tested locally.
3. Pushed Docker image to **Azure Container Registry (ACR)**.
4. Deployed to **Azure App Service (Web App for Containers)** and validated performance with Azure Monitor.
5. Integrated **GitHub Actions CI/CD** — every commit triggers Docker build, push to ACR, and redeployment automatically.

---

## ⚡ Getting Started
1. Clone the repo:
    ```bash
   git clone https://github.com/alanphilip/multiagent-pdlc-assistant.git
   cd multiagent-pdlc-assistant

2. Install dependencies:
    ```bash
   pip install -r requirements.txt

3. Run the dashboard:
    ```bash 
   streamlit run src/dashboard/app.py

---

## 📸 Screenshots

![App Screenshot Placeholder](images/project.png)

--- 

## 📈 Evaluation

Benchmarked the Multi-Agent PDLC Assistant against a manual baseline to measure efficiency and accuracy.

### Baseline
- Manual requirement analysis: human analyst extracts fields, flags risks, and suggests designs.

### Agentic System
- Automated extraction, design suggestions, and risk detection using multi-agent workflows.

### Metrics
- **Time Saved per Requirement**: Average time reduction compared to manual analysis.
- **Number of Risks Flagged**: Coverage of risks identified vs baseline.
- **Accuracy of Design Suggestions**: Validated against known best practices or expert review.

### Sample Results (Placeholder)

| Metric                        | Baseline (Manual) | Agentic System | Improvement |
|-------------------------------|-------------------|----------------|-------------|
| Avg. Time per Requirement     | 5 min             | 1.5 min        | 70% faster  |
| Risks Flagged (per 20 reqs)   | 12                | 15             | +25%        |
| Design Suggestion Accuracy    | 75%               | 82%            | +7%         |

---

📌 *Note: These numbers are illustrative placeholders. Actual evaluation will be conducted using a curated dataset of requirements, timed manual vs agentic runs, and expert validation of outputs.*

---

## 📜 License
- This project is licensed under the MIT License — free to use, modify, and distribute with attribution.

--- 

## 🤝 Contributions
- Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to add.

--- 

## 🌟 Why This Project?
- This project showcases agentic AI applied to PDLC innovation, demonstrating skills in:
  - Multi-agent orchestration 
  - AI/ML system design 
  - Risk-aware engineering 
  - End-to-end project delivery