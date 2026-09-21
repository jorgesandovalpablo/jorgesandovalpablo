# Hi there, I'm Jorge Alejandro Sandoval Pablo 👋
### **Machine Learning & MLOps Engineer | Bionic Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorge-alejandro-sandoval-pablo/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jorge.sandoval.pablo@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jorgesandovalpablo)

---

## ⚡ About Me

I am a **Bionic Engineer** specializing in **MLOps, Cloud Architecture (AWS, GCP, OCI), and Machine Learning Engineering**. 

My core expertise spans building production-grade ML pipelines, containerized microservices, time-series forecasting models, and automated continuous retraining workflows (CI/CD). Backed by a strong foundation in hardware-software integration, signal processing, and multi-cloud environments, I focus on bridging the gap between raw data, experimental machine learning, and scalable cloud infrastructure.

- 🤖 **Specialization:** MLOps, Time Series Forecasting, Cloud Infrastructure, Data Engineering & Embedded/Edge AI.
- ☁️ **Cloud Certified:** AWS Certified AI Practitioner | AWS Cloud Practitioner | OCI Data Science Professional | OCI AI Vector Search | Google Cloud Computing Foundations.
- 🎯 **Target Focus:** Production ML Deployment, CI/CD for Machine Learning, Data Pipeline Orchestration, & Model Monitoring.

---

## 🛠️ Technical Stack

| Domain | Technologies & Tools |
| :--- | :--- |
| **MLOps & CI/CD** | MLflow, DagsHub, Docker, GitHub Actions, FastAPI, Optuna, SHAP |
| **Cloud Platforms** | **AWS** (SageMaker, Lambda, S3, EC2, Bedrock), **GCP** (Vertex AI, BigQuery, Dataproc), **OCI** (Data Science, Vector Search) |
| **Data Engineering** | PySpark, Apache Airflow, Apache Kafka, SQL, NoSQL (MongoDB, Firebase), Parquet |
| **ML / DL Frameworks** | Scikit-Learn, LightGBM, CatBoost, XGBoost, TensorFlow, PyTorch, OpenCV, NumPy, Pandas |
| **Languages** | Python (Advanced), C/C++, SQL, Shell/Bash |
| **Edge & Embedded Systems** | ESP32, Raspberry Pi, Biosignal Processing (EOG, ECG, EEG), CAD (Fusion 360, Inventor) |

---

## 🚀 Featured Production Project

### 📈 [End-to-End Retail Sales & Demand Forecasting Pipeline](https://github.com/jorgesandovalpablo/demand-forecast)

> **Production-ready time-series forecasting architecture for multi-item retail demand prediction across 1,782 time series and 54 stores over a 4.5-year horizon.**

```
                                 [ MLOps Pipeline Architecture ]
                                 
 +------------------+     +------------------+     +------------------+     +------------------+
 |  Data Ingestion  | --> | Feature Eng. &   | --> | Model Training & | --> | Experiment       |
 |  & Preprocessing |     | Walk-Forward CV  |     | Optuna Tuning    |     | Tracking (MLflow)|
 +------------------+     +------------------+     +------------------+     +------------------+
                                                                                     |
                                                                                     v
 +------------------+     +------------------+     +------------------+     +------------------+
 | Automated CI/CD  | <-- | Docker Container | <-- | REST API Service | <-- | Best Model       |
 | Retraining Workflow|   | Packaging        |     | (FastAPI)        |     | Registry         |
 +------------------+     +------------------+     +------------------+     +------------------+
```

#### Key Highlights & Engineering Achievements:
- **Data Engineering & EDA:** Processed and structured 1,782 individual time-series datasets across 54 retail store locations. Built dynamic horizon-based feature engineering (lags, rolling statistics, calendar indicators) preventing data leakage via strict **Walk-Forward Cross Validation**.
- **Model Optimization:** Trained gradient boosting models (LightGBM) against naive and seasonal baselines. Utilized **Optuna** for dynamic hyperparameter search and **SHAP** for feature explainability and global interpretability.
- **MLOps Architecture:** 
  - Instrumented continuous experiment tracking and model registry using **MLflow** integrated with **DagsHub**.
  - Containerized the inference interface into a lightweight **FastAPI** service inside **Docker**.
  - Built an automated **GitHub Actions CI/CD** pipeline triggering weekly automated retraining, validation, and promotion.
- **Impact & Performance:**
  - **30-Day Horizon (h30):** Reduced WAPE from **29.42%** (Seasonal Naive) down to **12.96%**.
  - **7-Day Horizon (h7):** Reduced WAPE from **26.60%** (Seasonal Naive) down to **11.48%**.

👉 **[Explore repository source code & documentation »](https://github.com/jorgesandovalpablo/demand-forecast)**

---

## 🎖️ Certifications & Education

* **AWS Certified AI Practitioner (AIF-C01)** — Amazon Web Services
* **AWS Certified Cloud Practitioner (CLF-C02)** — Amazon Web Services
* **OCI Data Science Professional (1Z0-1110-25)** — Oracle Cloud Infrastructure
* **OCI AI Vector Search Professional (1Z0-184-25)** — Oracle Cloud Infrastructure
* **Google Cloud Computing Foundations** — Google Cloud Platform
* **IBM Data Engineering Professional Certificate** (Coursera) — PySpark, Airflow, Kafka & Data Pipelines
* **B.S. in Bionic Engineering** — UPIITA, Instituto Politécnico Nacional (IPN)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jorgesandovalpablo&show_icons=true&theme=radial&hide_border=true" alt="Jorge's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jorgesandovalpablo&layout=compact&theme=radial&hide_border=true" alt="Most Used Languages" width="48%" />
</p>

---

## 📫 Connect with Me

- **Email:** [jorge.sandoval.pablo@gmail.com](mailto:jorge.sandoval.pablo@gmail.com)
- **LinkedIn:** [linkedin.com/in/jorge-alejandro-sandoval-pablo](https://www.linkedin.com/in/jorge-alejandro-sandoval-pablo/)
- **GitHub:** [github.com/jorgesandovalpablo](https://github.com/jorgesandovalpablo)
