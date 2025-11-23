🚀 IntrusiveX AI

AI-Powered Real-Time Intrusion Detection & Threat Intelligence System

🛡️ Overview

IntrusiveX AI is an intelligent cybersecurity system designed to detect malicious network activity in real time using Machine Learning. The system identifies attacks, explains the reasoning using Explainable AI (SHAP), and stores detected threats securely for tamper-proof auditing.

It provides a modern visual dashboard to analyze anomalies, classify intrusion attempts, visualize threat metrics, and suggest preventive actions.

📌 Key Features

🔍 Real-time Intrusion Detection using ML classification models

🎯 Binary & Multi-Class Intrusion Result Labeling

📊 Feature Importance & Confusion Matrix Visualization

🧠 Explainable AI using SHAP for model transparency

🔐 Secure Log Storage (Optional: Blockchain/Immutable Records)

🧾 Threat Summary, Suggestions & Response Guidance

⚡ Fast Web Interface with React Frontend and Python Backend

🏗️ Tech Stack
Layer	Technology
Frontend	React.js, Axios, Chart.js/Recharts
Backend	Python (Flask/FastAPI/Django), ML Model (Pickle/TensorFlow/Sklearn)
ML Model	RandomForest / XGBoost / Gradient Boosting
Explainability	SHAP
Storage	SQLite / MongoDB / IPFS (Optional)
📁 Project Structure
IntrusiveX-AI/
│
├── backend/
│   ├── model.pkl
│   ├── api.py
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
└── README.md

⚙️ Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/YourUser/IntrusiveX-AI.git
cd IntrusiveX-AI

2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
python api.py


Backend will start at:

➡️ http://localhost:5000

3️⃣ Frontend Setup
cd frontend
npm install
npm start


Frontend will start at:

➡️ http://localhost:3000

📡 How It Works (Workflow)

User uploads network traffic dataset or CSV file

Model processes data and detects:

Normal traffic

Multiple forms of intrusion (DOS, R2L, U2R, Probe, etc.)

Results are sent to UI:

Per-row detection results

Confidence score

Threat suggestion & remediation

Visualizations (Confusion Matrix, Feature Importance) displayed on dashboard

🧪 Sample Output
Input Data Row	Prediction	Confidence	Suggestion
Row #1	🔥 DOS Attack	97.2%	Block Source IP
Row #2	✔ Normal	92.5%	No action required
