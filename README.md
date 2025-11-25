🧠 TextMorph
Advanced Text Summarization, Paraphrasing & Document Intelligence

🚀 TextMorph is an AI-powered system for summarization, paraphrasing, Q&A and translation of large documents such as news articles, academic research, legal policies, and educational content.

It combines state-of-the-art NLP models, secure backend services, and a streamlined UI to deliver fast and meaningful text transformations.

✨ Key Use Cases

📢 News Summarization → Quick and accurate digest of real-time updates

📑 Research Papers → Faster comprehension of complex content

⚖️ Legal & Policy Docs → Simplified interpretation with reduced jargon

🎓 Education → Helps students & teachers with clarity and accessibility

🎯 Achievements

✔ Completed end-to-end development
✔ Model training + fine-tuning
✔ Backend–Frontend integration
✔ Live evaluation & metrics
✔ Admin dashboard for user/content management

🛠️ Tech Stack
Layer	Technology
Frontend	🧩 Streamlit
Backend	⚡ FastAPI
Database	🛢️ MySQL
AI Models	🧠 Pegasus-XSum (Summarization), Facebook BART (Summary + Paraphrasing)
Version Control	🐙 GitHub
Deployment	Local (Docker support planned)
🚀 Core Features

📂 Upload documents: PDF, DOC, Text input

📝 Summarization: Short, Medium, Detailed

✍️ Paraphrasing: Multiple rewriting styles

🌐 Multilingual Translation

❓ Question & Answering from document context

📊 Admin dashboard: Analytics + user management

📦 Model Checkpoints (Required)

Large pre-trained models are hosted on Drive (~2 GB each):

facebook-bart-summary

facebook-bart-paraphrase

pegasus-xsum

📥 Download from Drive:
🔗 https://drive.google.com/drive/folders/17vlFTM0ZSE_DQ3YGDT8NNck1UiAe-2Ay?usp=drive_link

🔗 https://drive.google.com/drive/folders/1fLjidgeBNmuxMcXKhwshfsQlALGeYsW-?usp=drive_link

🔗 https://drive.google.com/drive/folders/1DU8I2ORp4J42CaA4ffXaSFY918ht0Vo4?usp=drive_link

📍 Place downloaded models under:

backend/models/

📚 Dataset (for training/evaluation)

Dataset used for experimentation and testing:
🔗 https://drive.google.com/file/d/1IOxJszNGT6B6ZJFatdH_ixEamusSTuOJ/view?usp=drive_link

Expected columns:

input_text, target_text, task (summary/paraphrase)


📍 Place dataset under:

dataset/

⚙️ Setup Instructions
# Create environment
pip install -r requirements.txt

# Add environment variables
# Create `.env` and follow `.env.example`

# Run Backend (FastAPI)
cd backend
uvicorn main:app --reload

# Run Frontend (Streamlit)
cd frontend
streamlit run app.py

📁 Project Structure (Simplified)
TextMorph/
│
├─ backend/
│  ├─ models/
│  ├─ routes/
│  └─ ...
├─ frontend/
│  └─ app.py
├─ dataset/
├─ requirements.txt
└─ README.md

👥 Team Members
Name	Role
Vidisha	Model Training & Evaluation
Varshita	UI/UX & Streamlit Frontend
Ajith Reddy	Backend Engineering & API
You	Full Integration + Backend & Dashboard + Deployment Setup

⭐ You can customize your role to highlight maximum impact

🔮 Future Scope

🔐 JWT-based Authentication

☁️ Cloud deployment (Render / AWS / Azure)

📊 Real-time metrics & analytics

🎚️ CPU/GPU auto-optimization

🧩 Plugin architecture for more NLP tasks

📌 Development Timeline
Week	Milestone
1-2	Backend/Auth setup
3-4	Document ingestion & indexing
5-6	Summarization + Paraphrasing
7	Admin dashboard
8	Final testing & review
📄 License

This project is intended for educational and internship demonstration purposes.
