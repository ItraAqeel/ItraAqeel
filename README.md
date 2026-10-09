# Itra Aqeel Abbasi

Computer Science graduate (FAST-NUCES, Islamabad) and Backend Development Intern at Switch Communications. My interests are AI/ML and backend engineering: scalable services, REST APIs and ML-powered features.

## Experience
**Backend Development Intern, Switch Communications** (current)
- Developed AzanAlerts, a subscriber provisioning module for a prayer-time alert service, using Java and Spring Boot:
  - REST API for subscription requests, with input validation, blacklist checks and failed-request tracking.
  - Integration with the operator provisioning platform over REST, plus a SOAP endpoint to receive subscription status callbacks.
  - Prayer-time generation per city, with support for multiple calculation methods (Hanafi and Jafari).
  - Promotional package management, with a scheduled job that expires promotions.
  - Event-driven notifications published to Kafka, with MariaDB for persistence and Redis for caching.
  - Prometheus metrics via Spring Boot Actuator, and unit and integration tests covering the main subscription flows.
- Build and maintain automated reporting pipelines that generate recurring reports for multiple telecom operator clients and for the company's own products, without manual effort.
- Schedule and manage recurring jobs with cron on Linux servers.
- Deploy and maintain scripts on remote servers using Xshell (SSH) and Xftp (file transfer).

**Fullstack/Backend Developer, Socialoholic**
- Built full-stack features with React, Node.js, REST APIs and PostgreSQL.
- Designed backend services within a microservices architecture, improving service isolation and deployment flexibility.
- Developed reusable React components integrated with Node.js APIs.

## Selected Projects
### Questor: Hybrid AI Framework for Financial Fraud Detection
Research team project (Python, ML, NLP). Team repository: [Questor](https://github.com/ChaudaryAbdullah/Questor) ([my fork](https://github.com/ItraAqeel/Questor)). The framework combines three components into one explainable fraud risk score for companies, built from financial data and SEC 10-K filings.

**My contribution:** data collection, training and evaluating the machine learning models (XGBoost, Isolation Forest, Random Forest), and writing the research paper.

The framework:
- **Structured pipeline:** a weighted ensemble of 17 models, covering classifiers (CatBoost, XGBoost, LightGBM, Random Forest, SVM, neural networks) and anomaly detectors (Isolation Forest, One-Class SVM, LOF, Autoencoder), with weights based on training AUC.
- **Unstructured pipeline:** NLP analysis of SEC filings with FinBERT, linked to a Neo4j knowledge graph of companies, executives and transactions, with ChromaDB for fast document retrieval.
- **Rule-based agents:** 15 financial fraud agents (Altman Z-Score, Beneish M-Score, Benford's Law, accrual and cash-flow checks, and others) that explain which red flags drive a score.
- **Results:** 0.97 F1-score and 0.999 precision. The NLP and knowledge-graph layer raised fraud recall by 11.5% over the numerical pipeline. In a comparison against five recent fraud-detection studies, it reached up to 6.67% higher accuracy and about 60% fewer false positives.
- **Output:** a unified risk score from 0 to 100 with five risk levels (minimal to critical), at roughly 15 to 18 seconds end to end.

## Technical Skills
- **Languages:** Python, Java, C++, JavaScript, SQL
- **Backend and Web:** Java (Spring Boot), Node.js, React, REST and SOAP APIs, Microservices, Kafka, Redis, PostgreSQL, MariaDB, MongoDB
- **Tools and Operations:** Linux, Cron, Xshell, Xftp, Git
- **AI/ML and Data:** Machine Learning, NLP, FinBERT, Knowledge Graphs (Neo4j), Pandas, NumPy, Power BI

## Contact
- LinkedIn: [linkedin.com/in/itraaqeel](https://www.linkedin.com/in/itraaqeel)
- Email: itraaqeel@gmail.com
