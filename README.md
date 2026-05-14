# 🧠 AI Drug Discovery System using RDKit, XGBoost & Gradio

An advanced AI-powered drug discovery web application that predicts whether a molecule is a potential active drug candidate or an inactive molecule using molecular descriptors and machine learning.

This project combines:

- Bioinformatics
- Machine Learning
- Molecular Chemistry
- Explainable AI
- Web Application Development

Built with RDKit, XGBoost, and Gradio.

---

# 🚀 Project Overview

Drug discovery is one of the most expensive and time-consuming processes in the pharmaceutical industry.

This project demonstrates how Artificial Intelligence and Machine Learning can assist in virtual screening by analyzing molecular structures represented as SMILES strings and predicting biological activity.

The system:

✅ Accepts molecular SMILES input  
✅ Extracts chemical descriptors using RDKit  
✅ Applies machine learning prediction using XGBoost  
✅ Generates feature importance analysis  
✅ Provides an interactive Gradio web interface  

---

# 🖼️ Application Features

## 🔬 Molecular Analysis
- SMILES String Processing
- Descriptor Extraction
- Molecular Property Calculation

## 🤖 Machine Learning
- XGBoost Classifier
- Binary Drug Activity Prediction
- Probability Score Generation

## 📊 Visualization
- Feature Importance Plot
- Descriptor Analysis

## 🌐 Web Application
- Interactive Gradio Interface
- Real-Time Predictions
- User-Friendly Design

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| RDKit | Molecular Descriptor Extraction |
| XGBoost | Machine Learning Model |
| Scikit-Learn | ML Utilities |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Gradio | Web Application UI |
| Joblib | Model Serialization |

---

# 📂 Project Structure

```bash
AI-Drug-Discovery/
│
├── app.py
├── requirements.txt
├── README.md
├── drug_discovery_model.pkl
└── sample_dataset.csv
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/AI-Drug-Discovery.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd AI-Drug-Discovery
```

---

## 3️⃣ Create Virtual Environment (Recommended)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Application

```bash
python app.py
```

After running:

```bash
Running on local URL: http://127.0.0.1:7860
```

Open the URL in your browser.

---

# 🧪 Example SMILES Inputs

| Molecule | SMILES |
|---|---|
| Ethanol | `CCO` |
| Ethylamine | `CCN` |
| Propane | `CCC` |
| Chloroethane | `CCCl` |
| Bromoethane | `CCBr` |

---

# 📊 Machine Learning Workflow

## Step 1 — Molecular Input
User enters SMILES notation.

## Step 2 — Descriptor Extraction
RDKit extracts:
- Molecular Weight
- LogP
- Hydrogen Donors
- Hydrogen Acceptors
- TPSA
- Ring Count
- Rotatable Bonds

## Step 3 — Feature Engineering
Descriptors converted into ML-ready format.

## Step 4 — Model Prediction
XGBoost classifier predicts:
- Active Drug Candidate
- Inactive Molecule

## Step 5 — Visualization
Feature importance graph generated.

---

# 🧠 AI Concepts Used

- Molecular Informatics
- Drug Discovery
- Feature Engineering
- Classification Algorithms
- Ensemble Learning
- Explainable AI
- Bioinformatics

---

# 📈 Future Improvements

## 🔥 Planned Features

- Deep Learning Drug Prediction
- Graph Neural Networks (GNN)
- ChemBERTa Integration
- Real ChEMBL Dataset Support
- Molecular Docking Integration
- Toxicity Prediction
- Drug Similarity Search
- Multi-Class Prediction
- Cloud Deployment

---

# 🌐 Deployment Options

You can deploy this project on:

- Hugging Face Spaces
- Render
- Railway
- Replit
- AWS
- Google Cloud
- Azure

---

# 📦 requirements.txt

```txt
gradio
pandas
numpy
matplotlib
scikit-learn
xgboost
joblib
rdkit-pypi
```

---

# 📄 Resume Project Description

## AI Drug Discovery System

Developed an end-to-end AI-powered drug discovery system using RDKit and XGBoost to predict molecular drug activity from SMILES representations.

Key contributions:
- Built molecular descriptor extraction pipeline
- Developed machine learning classification model
- Created interactive Gradio web application
- Implemented feature importance visualization
- Designed scalable prediction workflow for virtual screening

---

# 🤝 Contributing

Contributions are welcome.

Steps:
1. Fork repository
2. Create feature branch
3. Commit changes
4. Push updates
5. Open Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Sagar Kamble

AI Engineer | Machine Learning Enthusiast | Gen ai | NLP | Agentic ai

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
📢 Share with others  

---
