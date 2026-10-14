<a href="https://kelyzhang.com"><img src="./assets/banner.jpg" alt="Kely Zhang — ML Engineer / AI Engineer / Platform Engineer" width="100%"></a>

<h3 align="center"><i>ML · AI · Platform Engineering — UChicago MS Applied Data Science ’26</i></h3>

<p align="center">
  <a href="https://www.linkedin.com/in/yichun-zhang-zyc/"><img src="https://img.shields.io/badge/LinkedIn-yichun--zhang--zyc-A9877A?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=423C35" alt="LinkedIn"></a>
  <a href="https://kelyzhang.com"><img src="https://img.shields.io/badge/Portfolio-kelyzhang.com-A9877A?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=423C35" alt="Portfolio"></a>
  <img src="https://img.shields.io/badge/Chicago-open%20to%20relocate-A9877A?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=423C35" alt="Chicago">
  <img src="https://img.shields.io/badge/Open%20to-full--time%20roles-800000?style=for-the-badge&labelColor=423C35" alt="Open to full-time roles">
</p>

---

<img src="./assets/kely.png" align="right" width="190" alt="Kely Zhang">

Hi, I’m **Kely (Yichun) Zhang**. I build the systems around models as much as the models themselves: the pipeline that feeds them, the automation that replaces a manual queue, and the dashboard that tells leadership something is off before production does.

Right now I’m a **Platform Engineering intern at The OCC** (Options Clearing Corporation), writing tools that sit between Jira, Artifactory, Kubernetes and the PR workflow. I’m also an **ML engineer on a HERE Technologies–sponsored capstone**, estimating real-world object dimensions from street-level imagery. Before that I built chatbots for **UChicago IT Services**, NL-to-SQL for **The Home Depot**, and forecasting and sentiment work for **Under Armour**.

**Statistics + Economics at the University of Toronto** (High Distinction, Dean’s List all four years), now finishing an **MS in Applied Data Science at the University of Chicago** in December 2026.

<br clear="right"/>

---

## What I’ve shipped

**A manual artifact-publishing process, now rule-based** · *The OCC*. A Python tool that reads incoming Jira requests, checks them against a whitelist, and publishes approved artifacts to Artifactory through its API. The whitelist is the safety net: bad or misrouted uploads stop there.

**End-of-Life libraries, flagged at PR time** · *The OCC*. A script that joins data across internal systems to find EoL dependency usage, then hooks into the PR workflow to alert the team that owns it. Long-standing tech debt, handled in code.

**Kubernetes config drift, visible across clusters** · *The OCC*. A live dashboard that diffs ConfigMaps across the West, East and RTOP clusters so production discrepancies reach engineering leadership. The prevention mechanisms I proposed were adopted to cut recurring deployment errors.

**Metric 3D from a dashcam’s point of view** · *HERE Technologies capstone*. Chicago street-view imagery collected through the Mapillary API, with MapAnything, DepthAnything and VGGT evaluated for depth and 3D reconstruction. Dimension estimates are checked against ground truth for accuracy and real-world feasibility.

**A chatbot that knows the account string** · *UChicago IT Services*. An Oracle Digital Assistant for the Purchase Requisition workflow, with a custom account-validation API, conversation flows and agent teams. Also on the Neo4j course-advisor AI: frontend, stakeholder demos, and Dockerizing it off the VM.

**Ask the data instead of opening the dashboard** · *The Home Depot*. An NL-to-SQL chatbot on BigQuery, plus a repaired Jotform → Apps Script → BigQuery → Power BI pipeline that keeps product-engineering dashboards up to date.

---

## How I work

| As an ML / AI engineer | As a platform engineer |
| --- | --- |
| Pick the model that holds up against ground truth, not the one with the best demo | Replace manual queues with rule-based automation that has a fail-safe |
| Fine-tune and evaluate: DistilBERT, BERTopic, ViT / ResNet, SqueezeNet, depth models | Wire tools into the APIs teams already use: Jira, Artifactory, GitHub PRs |
| Ship it where people can use it: ONNX in the browser, Streamlit / web dashboards | Make drift visible: Kubernetes config diffs across clusters |
| RAG, agents and NL-to-SQL on real enterprise data | Docker, CI/CD, GitHub Actions, Jenkins, IaC |

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-423C35?style=flat-square&logo=python&logoColor=EAE3DA)
![SQL](https://img.shields.io/badge/SQL-423C35?style=flat-square&logo=postgresql&logoColor=EAE3DA)
![JavaScript](https://img.shields.io/badge/JavaScript-423C35?style=flat-square&logo=javascript&logoColor=EAE3DA)
![TypeScript](https://img.shields.io/badge/TypeScript-423C35?style=flat-square&logo=typescript&logoColor=EAE3DA)
![R](https://img.shields.io/badge/R-423C35?style=flat-square&logo=r&logoColor=EAE3DA)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-423C35?style=flat-square&logo=pytorch&logoColor=EAE3DA)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-423C35?style=flat-square&logo=huggingface&logoColor=EAE3DA)
![TensorFlow](https://img.shields.io/badge/TensorFlow-423C35?style=flat-square&logo=tensorflow&logoColor=EAE3DA)
![ONNX](https://img.shields.io/badge/ONNX-423C35?style=flat-square&logo=onnx&logoColor=EAE3DA)
![RAG](https://img.shields.io/badge/RAG%20%26%20Agents-423C35?style=flat-square&logo=langchain&logoColor=EAE3DA)
![Neo4j](https://img.shields.io/badge/Neo4j-423C35?style=flat-square&logo=neo4j&logoColor=EAE3DA)

**Cloud, Platform & DevOps**

![AWS](https://img.shields.io/badge/AWS-423C35?style=flat-square&logo=amazonwebservices&logoColor=EAE3DA)
![GCP](https://img.shields.io/badge/Google%20Cloud-423C35?style=flat-square&logo=googlecloud&logoColor=EAE3DA)
![Azure](https://img.shields.io/badge/Azure-423C35?style=flat-square&logo=microsoftazure&logoColor=EAE3DA)
![Kubernetes](https://img.shields.io/badge/Kubernetes-423C35?style=flat-square&logo=kubernetes&logoColor=EAE3DA)
![Docker](https://img.shields.io/badge/Docker-423C35?style=flat-square&logo=docker&logoColor=EAE3DA)
![Jenkins](https://img.shields.io/badge/Jenkins-423C35?style=flat-square&logo=jenkins&logoColor=EAE3DA)
![GitHubActions](https://img.shields.io/badge/GitHub%20Actions-423C35?style=flat-square&logo=githubactions&logoColor=EAE3DA)
![Jira](https://img.shields.io/badge/Jira-423C35?style=flat-square&logo=jira&logoColor=EAE3DA)
![Artifactory](https://img.shields.io/badge/Artifactory-423C35?style=flat-square&logo=jfrog&logoColor=EAE3DA)

**Data & BI**

![BigQuery](https://img.shields.io/badge/BigQuery-423C35?style=flat-square&logo=googlebigquery&logoColor=EAE3DA)
![PowerBI](https://img.shields.io/badge/Power%20BI-423C35?style=flat-square&logo=powerbi&logoColor=EAE3DA)
![Tableau](https://img.shields.io/badge/Tableau-423C35?style=flat-square&logo=tableau&logoColor=EAE3DA)
![Excel](https://img.shields.io/badge/Excel%20%2F%20VBA-423C35?style=flat-square&logo=microsoftexcel&logoColor=EAE3DA)

---

## Selected projects

| Project | What it is |
| --- | --- |
| [**ai-news-sentiment-pipeline**](https://github.com/Yichun-Zhang-ZYC/ai-news-sentiment-pipeline) | BERTopic + NER + fine-tuned DistilBERT tracking how news media covers AI’s impact on business and industry, with an interactive sentiment and topic dashboard. |
| [**plant-disease-classifier**](https://github.com/Yichun-Zhang-ZYC/plant-disease-classifier) | SqueezeNet 1.1 fine-tuned on PlantVillage (98.13% test accuracy). A drag-and-drop leaf classifier that runs entirely client-side with ONNX Runtime Web. |
| [**Street-level dimension estimation**](https://github.com/Yichun-Zhang-ZYC/Real-World-Dimension-and-Metric-Estimation-of-Physical-Features-from-Street-Level-Imagery-) | HERE capstone: real-world metric estimation of physical features from Mapillary imagery and 3D reconstruction. |
| [**chatbot_db11**](https://github.com/Yichun-Zhang-ZYC/chatbot_db11) | Natural language → SQL query chatbot. |
| [**course_advisor_simple_version**](https://github.com/Yichun-Zhang-ZYC/course_advisor_simple_version) | AI course advisor for UChicago students. |
| [**room-to-grow**](https://github.com/Yichun-Zhang-ZYC/room-to-grow) | An open-source, web-first personal growth app: completing real-life tasks builds a room you actually care about. |
| [**MLOps-final**](https://github.com/Yichun-Zhang-ZYC/MLOps-final) · [**data-science-blog-with-devops**](https://github.com/Yichun-Zhang-ZYC/data-science-blog-with-devops) | MLOps and DevOps coursework: CI/CD, containers, deployment. |

---

## Experience

| | Role | When |
| --- | --- | --- |
| **The OCC** | Software (Platform) Engineering Intern, Tools Automation | Jun 2026 – present |
| **HERE Technologies** | Machine Learning Engineer, sponsored capstone | Mar 2026 – present |
| **UChicago IT Services** | AI Developer | Nov 2025 – Jun 2026 |
| **The Home Depot** | AI & Data Engineer Intern, Shanghai | Jul – Sep 2025 |
| **Under Armour** | Data Scientist Intern, Shanghai | Mar – May 2025 |

## Education

**MS, Applied Data Science, University of Chicago** · 2025 – Dec 2026<br>
<sub>Big Data & Cloud Engineering · Next-Gen NLP · MLOps · Time Series Analysis · Machine Learning</sub>

**BS, Statistics (Major), Economics with Data Analytics Focus (Major), Math (Minor), University of Toronto** · 2019 – 2023<br>
<sub>High Distinction · Dean’s List, 4 consecutive years · Excellent Academic Performance Scholarship, 3 years</sub>

---

<p align="center"><i>Statistics taught me to doubt the number. Engineering taught me to automate the doubt.</i><br>
<sub>Let’s talk: <a href="https://www.linkedin.com/in/yichun-zhang-zyc/">LinkedIn</a> · <a href="https://kelyzhang.com">kelyzhang.com</a></sub></p>
