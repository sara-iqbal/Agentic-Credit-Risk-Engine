
#  End-to-End Agentic Credit Risk Engine
### *Bridging Traditional Finance (TradFi) with Generative AI*

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![AI Model](https://img.shields.io/badge/Model-Llama3-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

##  Executive Summary
This project builds a regulatory-grade **Credit Risk Scoring System** compliant with **Basel III** standards. Unlike "black box" machine learning models, this engine uses **Weight of Evidence (WoE)** transformation and **Logistic Regression** to ensure 100% interpretability—a critical requirement for financial regulation.

The system is operationalized via a full-stack **Streamlit Banking Dashboard** that goes beyond simple prediction. It integrates **Agentic AI (Llama-3)** to automate customer communication, performs real-time **IFRS 9 Stress Testing**, and includes an **MLOps Drift Monitor** to ensure model reliability in volatile economic conditions.

---

##  Key Features

### 1. Transparent Scoring Engine (Basel III)
* **Algorithm:** Logistic Regression calibrated with Points-to-Double-the-Odds (PDO).
* **Feature Engineering:** Implemented WoE (Weight of Evidence) and IV (Information Value) binning to handle non-linear data.
* **Explainability:** Integrated **SHAP waterfall charts** to explain every point of a customer's score (e.g., *"Your score dropped 40 points due to critical credit history"*).

### 2. Agentic AI Integration ("Human-in-the-Loop")
* **Powered by:** Llama-3-70b (via Groq API).
* **Role:** Acts as a "Virtual Underwriter."
* **Capabilities:**
    * Drafts **empathetic decision emails** (Approvals/Rejections) automatically.
    * Generates **technical validation reports** explaining the mathematical logic of the score to internal auditors.

### 3. Macro-Economic Stress Testing (IFRS 9)
* Simulates economic recession scenarios by artificially shifting Probability of Default (PD) distributions.
* Calculates **Projected Capital Loss** in real-time to assess the bank's Capital Adequacy.

### 4. MLOps & Model Monitoring
* Simulates a production environment to track the **Population Stability Index (PSI)**.
* Automatically flags **Concept Drift** (e.g., if a sudden influx of bad applicants occurs) and triggers retraining alerts.

---

## 🛠️ Technical Architecture

| Component | Tech Stack | Description |
| :--- | :--- | :--- |
| **Data Processing** | `Pandas`, `NumPy` | Cleaning, binning, and target mapping (Good/Bad). |
| **Modeling** | `Statsmodels`, `Scikit-Learn` | Logistic Regression, WoE Transformation, Calibration. |
| **Frontend** | `Streamlit` | Interactive dashboard for Loan Officers and Risk Managers. |
| **Generative AI** | `LangChain`, `Groq API` | Orchestrating Llama-3 agents for text generation. |
| **Visualization** | `Seaborn`, `Matplotlib` | Heatmaps, distribution plots, and SHAP charts. |
| **Deployment** | `Ngrok` | Tunneling the local server for public access. |

---

##  Business Impact & ROI
This project solves three critical banking challenges:

1.  **Regulatory Compliance:** By using a "White Box" model (Logistic Regression), the system meets strict explainability laws (e.g., Fair Lending Act) that Neural Networks often fail.
2.  **Capital Preservation:** The **Risk-Based Pricing** module ensures the bank charges higher interest rates (APR) to riskier customers, optimizing the Risk-Adjusted Return on Capital (RAROC).
3.  **Operational Efficiency:** The AI Agent reduces the time required to draft rejection letters from **10 minutes to 5 seconds**, ensuring consistent and polite communication.

---

