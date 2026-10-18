# Sriteja Valaboju

Software Engineer at Airbus. I build production agent systems, RAG pipelines, and cloud infrastructure on GCP and AWS. Mostly, I try to stop LLMs from making things up in front of 80,000 aerospace engineers.

| Metric | Number | Context |
| :--- | :--- | :--- |
| **Users served** | 80,000 | Total Airbus employees with access to Augmented BMS, over 5,000 monthly active |
| **Latency drop** | 120s to 5s | Cut multi-agent search to 30s, then added a direct semantic search fast mode |
| **Docker diet** | 80% smaller | Shrunk frontend images by 80%, ingestion by 50%, and backend by 10% |
| **UI components** | 50+ | Co-developed the Airbus Vue 3 Design System in Storybook |

---

### Work at Airbus

- **Augmented BMS.** Architected and shipped a conversational GenAI assistant indexing 4,000 internal documents. It answers employee questions so they do not have to read 4,000 PDFs themselves.
- **Multi-agent search and latency.** Built multi-agent workflows with Google ADK for deep search, link analysis, and human-in-the-loop checkpoints. Rewrote Vertex AI vector retrieval pipelines with LangChain and pruned document chunks from 33,000 to 25,000. This cut search latency by 75 percent, from 120 seconds to 30 seconds. For people who cannot wait 30 seconds, I built a fast mode that returns answers in 5 seconds.
- **Evaluation and grounding.** Added hallucination detection and response grounding using RAGAS and golden datasets. In an aerospace company, we prefer our AI answers to stay grounded.
- **AI Portfolio and Skill Registry.** Led production delivery of the centralized AI project tracking platform using React, FastAPI, pgvector on Cloud SQL, and Cloud Run with role-based access control. Built the innersourced Skill Registry to package reusable agent skills and publish them to Artifactory and GCP Artifact Registry via Jenkins CI/CD.
- **Container optimization.** Cut Docker image sizes by 80 percent for the frontend, 50 percent for the ingestion service, and 10 percent for the backend. Our CI/CD runners can breathe again.
- **ModelOps Platform and Design System.** Led the Vue 3 frontend for the official Airbus AI platform, unifying model creation, AWS SageMaker deployments, drift detection, and cost dashboards under Vite and Pinia. Co-developed the Airbus Vue 3 Design System and convinced official engineering guidelines to adopt Vue alongside React and Angular.

---

### Tech stack

| Category | Technologies |
| :--- | :--- |
| **GenAI and agents** | Google ADK, Gemini Enterprise, LangChain, LangGraph, Model Context Protocol, ReAct patterns, RAG, pgvector, Vertex AI, RAGAS, LangSmith |
| **Languages and backend** | Python, TypeScript, JavaScript, SQL, FastAPI, Node.js, PostgreSQL, REST APIs, 3-legged OAuth 2.0 |
| **Google Cloud** | Cloud Run, Cloud Functions, Cloud Build, Pub/Sub, Cloud SQL, BigQuery, Cloud Logging, Looker Studio, Terraform |
| **AWS** | Lambda, API Gateway, S3, DynamoDB, SageMaker, CloudFormation, Python CDK, ECS |
| **Frontend** | React, Vue 3, Vite, Pinia, Zustand, Tailwind CSS, Chart.js, Recharts, Storybook |
| **Testing and DevOps** | Docker, Jenkins, Git, Cypress, Jest, Vitest |

---

### Certifications and awards

- **Google Cloud Certified Professional Machine Learning Engineer**
- **Google Cloud Advanced Generative AI certification on Vertex AI**
- **Airbus SPOT Award in November 2025** for shipping Augmented BMS to 80,000 users without breaking prod.
- **Airbus SPOT Award in March 2025** for leading frontend architecture on the ModelOps Platform.

### Education

B.Tech in Computer Science Engineering from Chaitanya Institute of Technology and Science, graduated in 2022 with an 8.07 CGPA.

### Contact

- **Email:** [sritejavalaboju000@gmail.com](mailto:sritejavalaboju000@gmail.com)
- **Portfolio:** [sriteja11.github.io/Sriteja-portfolio](https://sriteja11.github.io/Sriteja-portfolio/)
- **LinkedIn:** [linkedin.com/in/sriteja-valaboju-65184717a](https://www.linkedin.com/in/sriteja-valaboju-65184717a/)
- **Location:** Bengaluru, Karnataka, India
