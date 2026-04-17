# Windows DFIR Operations Console with ML-based Threat Detection
This project is a Digital Forensics and Incident Response system that analyzes Windows logs such as EVTX and Registry data. It processes, normalizes, and extracts features from events, applies machine learning to detect suspicious activity, groups related events, and reconstructs timelines through an interactive dashboard.

## 📌 Overview
This project is a Digital Forensics and Incident Response (DFIR) system designed to automate the analysis of Windows forensic artifacts such as EVTX logs and Registry data. It helps identify suspicious activities, reconstruct event timelines, and visualize incidents through an interactive dashboard.

---

## 🚀 Features
- 🔍 Ingestion of forensic artifacts (EVTX logs, Registry files)
- ⚙️ Parsing and normalization of raw system data
- 🧠 Machine Learning-based detection using Logistic Regression
- 📊 Suspicious event scoring and classification
- 🔗 Clustering of related events into incidents
- 🕒 Timeline reconstruction for forensic analysis
- 📈 Interactive dashboard for visualization
- 📡 REST API-based backend (FastAPI)

---

## 🧠 System Workflow
Ingestion → Parsing → Normalization → Feature Extraction → ML Scoring → Clustering → Timeline → Dashboard

---

## 🛠️ Tech Stack

### Backend
- FastAPI
- SQLAlchemy
- Pydantic

### Machine Learning
- scikit-learn (Logistic Regression)
- NumPy

### Forensics
- python-evtx
- python-registry

### Frontend
- Vite
- TypeScript
- Tailwind CSS

---

## 📊 How It Works
1. The system ingests forensic artifacts from files or system paths.
2. Raw logs are parsed and converted into structured data.
3. Data is normalized to ensure consistency and remove duplicates.
4. Features such as user, process, and timestamps are extracted.
5. A Logistic Regression model classifies events as suspicious or normal.
6. Related events are grouped into clusters.
7. Events are arranged into a timeline for investigation.
8. Results are displayed through an interactive dashboard.

---

## 🎯 Use Cases
- Digital forensic investigations
- Incident response analysis
- Malware activity detection
- Log analysis automation

---

## ⚠️ Limitations
- Model accuracy depends on training data
- Advanced real-time detection is under development

---

## 🔮 Future Improvements
- Improve ML model accuracy
- Add real-time monitoring
- Enhance reporting system (AI-based insights)

---

## 👨‍💻 Author
Jaivardhan
