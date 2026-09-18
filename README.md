# Awesome-Model-Monitoring-Platform

## Top Model Monitoring Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on ML Observability, Model Performance Monitoring, Data & Concept Drift Detection, LLM Evaluation & Production AI Reliability*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Model Monitoring**. These systems continuously track machine learning and generative AI models in production—detecting data drift, concept drift, performance degradation, data quality issues, and (for LLMs) output quality—so teams can retrain, alert, or intervene before business impact occurs.



**Examples** include Arize AI, Fiddler AI, WhyLabs, Evidently AI, Superwise, Aporia, Arthur AI, TruEra, Galileo AI, and Monitaur (the category leaders).



**Open-source emphasis**: Model monitoring has one of the strongest open-source ecosystems in MLOps. **Evidently**, **Deepchecks**, **whylogs**, **NannyML**, and **Alibi Detect** provide production-capable libraries and self-hosted dashboards. Many commercial platforms also expose open-source components or companions. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

**Market Size & Sector Dynamics**: The AI Model Monitoring & Observability market is estimated at **$3.31 Billion in 2026** (projected to reach $20.52 Billion by 2035 at a 22.5% CAGR). The sector is currently **highly fragmented**, featuring specialized point solutions alongside cloud infrastructure providers and traditional APM platforms.

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limit | Company Size / Valuation |
| :--- | :--- | :--- | :--- | :--- |
| **[TruEra](https://truera.com/)** | Enterprise AI observability & LLM evaluation platform integrated into Snowflake AI Cloud. | $1,000 / month (Enterprise baseline prior to Snowflake acquisition) | 14-day free trial on cloud platform; TruLens open-source evaluation library free forever | **$60 Billion** (Acquired by Snowflake; $42.3M VC funding raised) |
| **[Arize AI](https://arize.com/)** | ML & LLM observability platform for drift, evaluation, and root-cause tracing across model fleets. | $50 / month (AX Pro plan) | Free forever (AX Free: 25,000 trace spans/month, 1 GB storage, 15-day retention) | **$915 Million** (Acquired by Dynatrace; $131M VC funding raised) |
| **[Fiddler AI](https://www.fiddler.ai/)** | AI observability and explainability platform combining drift detection, model monitoring & guardrails. | $0.002 / trace (Developer plan) | Free tier available (up to 1,000 traces/month trial access) | **$100 Million** total VC funding raised ($30M Series C in 2026) |
| **[Galileo AI](https://rungalileo.io/)** | Evaluation, observability, and real-time guardrails platform for LLMs & Generative AI. | $100 / month (Pro plan billed annually, or $150/mo monthly) | Free forever (5,000 traces/month, unlimited users, unlimited custom evals) | **$68.1 Million** total VC funding raised ($45M Series B in Oct 2024) |
| **[Arthur AI](https://www.arthur.ai/)** | Performance monitoring, explainability, and governance engine for enterprise AI models. | $60 / month (Premium plan) | Free plan ($0/mo: up to 4 use cases, 7-day data retention, unlimited seats) | **$60 Million** total VC funding raised ($42M Series B) |
| **[WhyLabs](https://whylabs.ai/)** | Privacy-aware statistical profiling & data drift monitoring platform. | $125 / month (Historical Expert tier prior to Apple acquisition) | Free forever (Starter tier: 1 model & 5 feature profiles free; whylogs OSS free forever) | **$37 Million** valuation (Acquired by Apple; $14M VC funding raised) |
| **[Aporia](https://www.aporia.com/)** | Model validation, monitoring, and live AI guardrail system for production ML pipelines. | $500 / month (Enterprise starter tier prior to Coralogix acquisition) | 14-day free trial (up to 10,000 predictions / 1 model on starter tier) | **$30 Million** total VC funding raised (Acquired by Coralogix; ~$8.4M ARR) |
| **[Monitaur](https://monitaur.ai/)** | AI governance, risk management, and auditability platform for regulated enterprise sectors. | $2,000 / month (Custom enterprise baseline for regulated compliance) | 14-day guided proof-of-concept trial (no permanent self-service free tier) | **$13.2 Million** total VC funding raised ($6M Series A in May 2024) |
| **[Superwise](https://www.superwise.ai/)** | Continuous model performance monitoring & runtime guardrail platform for ML agents. | $10 / month (Pro+ tier starter) | Free forever (Starter tier: 1 agent/dataset, basic guardrails & runtime policies) | **$4.5 Million** total VC funding raised (Acquired by Blattner Tech; ~$2.2M ARR) |
| **[Evidently AI (Cloud)](https://www.evidentlyai.com/)** | Managed SaaS and self-hosted platform built on open-source Evidently ML evaluation framework. | $49 / month (Pro / Expert tier) | Free forever (1 user, up to 100 reports/month; core Python library 100% free open-source) | **~$1.5 Million** ARR / funding (Independent open-source framework leader) |



## Open-Source GitHub Projects



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Leading open-source ML and LLM observability framework. Computes 100+ metrics for data drift, data quality, model performance, and generative AI evaluation. Supports reports, test suites, and a self-hosted monitoring dashboard (Apache 2.0).



- **[Deepchecks](https://github.com/deepchecks/deepchecks)**  

  Holistic open-source suite for AI & ML validation and monitoring. Includes testing (tabular, NLP, CV), CI integration, and production monitoring components (core under AGPL).



- **[whylogs](https://github.com/whylabs/whylogs)**  

  Open-source library for logging statistical profiles (sketches) of datasets and model inputs/outputs. Enables scalable, privacy-preserving drift and quality monitoring without storing raw data.



- **[NannyML](https://github.com/NannyML/nannyml)**  

  Open-source library specialized in estimating model performance without ground truth (CBPE) and detecting multivariate drift—valuable when labels arrive with long delay.



- **[Alibi Detect](https://github.com/SeldonIO/alibi-detect)**  

  Open-source Python library (from Seldon) for outlier, adversarial, and drift detection across tabular, text, and image data. Integrates well with Kubernetes/Seldon serving stacks.



- **[Other ML monitoring & drift libraries](https://github.com/search?q=model+monitoring+OR+data+drift+OR+concept+drift)**  

  Additional community tools for statistical tests, performance tracking, and custom monitoring pipelines.



- **[LLM evaluation & observability open tools](https://github.com/search?q=LLM+evaluation+OR+LLM+observability+open+source)**  

  Emerging open projects focused on tracing, evaluation metrics, and monitoring for generative AI systems.



- **[MLflow, Prometheus, and general observability integrations](https://github.com/mlflow/mlflow)**  

  Broader open MLOps and metrics stacks frequently combined with specialized model-monitoring libraries.



### Additional Strong Open-Source Options



- **Evidently self-hosted UI**: Full open-source monitoring dashboard on top of Evidently metrics and tests.

- **Deepchecks Monitoring**: Open components for tracking deployed models (check licensing for enterprise features).

- **Profile-based monitoring**: whylogs + custom comparison logic for high-throughput or privacy-sensitive pipelines.

- **Performance-without-labels**: NannyML for delayed-ground-truth scenarios.

- **Serving-integrated detection**: Alibi Detect inside model-serving pipelines.

- Composable stacks: Evidently or Deepchecks for metrics + Prometheus/Grafana or custom stores for long-term tracking and alerting.



**Frameworks for building custom systems**:  

The strongest open-source foundations are **Evidently** (most complete ML/LLM monitoring library + dashboard), **Deepchecks** (validation + monitoring), **whylogs** (lightweight profiling), **NannyML** (performance estimation without labels), and **Alibi Detect** (drift/outlier detection).  

These can be combined into robust self-hosted monitoring pipelines.  

Commercial platforms (Arize, Fiddler, WhyLabs, etc.) add enterprise-scale storage, advanced embedding/LLM tracing, collaboration, governance, and support.  

Many teams start with Evidently or Deepchecks for core monitoring and later adopt a commercial platform for multi-model fleets, compliance reporting, or advanced root-cause analysis. Fully open stacks are production-viable for many organizations that can operate the infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Model monitoring surfaces issues but does not automatically fix them. Teams still need clear ownership, retraining processes, and decision thresholds. False positives and alert fatigue are common risks.

- Open-source monitoring tools offer transparency and no vendor lock-in but require you to manage storage, alerting, security, and scalability. Validate that chosen metrics and statistical tests match your data types and risk tolerance before relying on them in production.



---



**Made for ML engineers, MLOps practitioners, data scientists, and AI platform teams keeping models healthy in production.**  

Let's keep model monitoring open, measurable, and actionable—through both excellent open-source libraries and complementary commercial observability platforms.
