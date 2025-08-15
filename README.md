TalentAlign AI 🎯

TalentAlign AI is an intelligent resume–job description matching system powered by NLP and machine learning.
It parses resumes, extracts skills, compares them with job descriptions, and provides a semantic similarity score along with insights into common and missing skills.

The app is built with:

Frontend → React + TailwindCSS + Streamlit (UI for resume/JD uploads and insights)

Backend → Python (FastAPI / Flask) with ML models for embeddings & similarity scoring

Vector Search → Qdrant / FAISS for efficient semantic matching

ML/NLP → SentenceTransformers + OpenAI embeddings

🚀 Features

📄 Upload resumes and job descriptions in PDF format

🧠 Extract structured information (skills, experience, keywords)

🔍 Perform semantic similarity matching using embeddings

📊 Show overlap percentage and missing skills

🎨 Modern, responsive UI with clean design

🛠️ Installation & Setup
1. Clone the Repository
git clone https://github.com/Avi-Varma08/TalentAlign_AI.git
cd TalentAlign-AI

2. Install Dependencies
Backend (Python)
cd backend
pip install -r requirements.txt

Frontend (React)
cd talent_ai
npm install

▶️ Running the Application
Start Backend (Python API)
cd backend
python app.py

Start Frontend (React)
cd talent_ai
npm run dev


Now open http://localhost:5173/ (or the shown URL) in your browser.

📌 Project Structure
TalentAlign-AI/
│── backend/              # Python backend (Flask/FastAPI, ML logic)
│   ├── app.py            # Main API entry point
│   ├── models/           # NLP/ML models
│   └── utils/            # Helper functions
│
│── talent_ai/            # React frontend
│   ├── src/              # Components & pages
│   └── package.json      # Frontend dependencies
│
│── README.md             # Project documentation

⚡ Tech Stack

Frontend: React, TailwindCSS, Streamlit

Backend: Python (FastAPI/Flask), OpenAI API, SentenceTransformers

Database / Vector Store: Qdrant / FAISS

Other: PyPDF2, NumPy, scikit-learn
