# MedicalVision
🧠 MedVision
MedVision is a web-based application designed to simplify and automate routine data processing tasks for medical researchers. It supports both tabular data and medical image analysis, providing an all-in-one platform for data visualization, preprocessing, model training, result evaluation, and comparison — all while maintaining a history of experiments.

🌟 Features
📁 Data Import (Tabular & Medical Images)

📊 Visualization Tools (Histograms, statistics, image metadata, etc.)

⚙️ Preprocessing Pipelines (Normalization, resizing, slicing, etc.)

🧠 Model Training (Including U-Net + Inception-based models)

📈 Evaluation Metrics (Accuracy, Dice coefficient, Recall, etc.)

🔄 Result Comparison (Multiple model outputs for informed decision-making)

📝 Experiment Tracking (Project history for reproducibility)

🖥️ Tech Stack: React (Frontend), Flask (Backend), MySQL (Database)

📸 Demo
👉 Watch Demo Video
📦 Download the Full Project Files (Google Drive)

Due to the large size of medical image data and models, the complete project is stored on Google Drive.

🚀 Getting Started
Prerequisites
Python 3.9+

Node.js 18+

MySQL Server (Local)

Virtualenv (recommended)

1. Backend Setup (Flask)
bash
Copier le code
cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
2. Frontend Setup (React)
bash
Copier le code
cd frontend
npm install
npm start
3. Database Setup
Import the provided schema.sql into your local MySQL server.

Update database credentials in config.py.
