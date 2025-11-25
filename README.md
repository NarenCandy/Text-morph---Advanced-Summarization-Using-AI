# 📝 TextMorph: Advanced Text Summarization & Paraphrasing

🚀 **TextMorph** is an AI-powered system for **document summarization, simplification, Q&A, and translation**. It ingests large documents, extracts key insights, and generates **clear, concise summaries** across multiple domains like **news, research papers, legal & policy documents, and education**.

---

## 🎯 Project Overview

TextMorph is an advanced text processing application designed for summarization and paraphrasing, built as part of a milestone-driven development internship project.

✅ **The project has successfully completed all planned milestones**, encompassing:
- 🧪 Model training
- 🔗 Backend and frontend integration
- 📊 Evaluation systems
- 🛠️ Admin dashboard for content and user management

---

## ✨ Why This Project?

- 📢 **News Summarization** → Get digestible news highlights in seconds
- 📑 **Research Papers** → Quickly understand lengthy academic texts
- ⚖️ **Legal & Policy Docs** → Simplify complex jargon into plain language
- 🎓 **Education** → Help students & teachers with short, simplified content

---

## 🚀 Features

- Upload documents (PDF, DOCX, URL ingestion)
- AI-powered **Summarization** (short, medium, long)
- **Paraphrasing** for simplified versions
- **Multilingual Translation** support
- Query-based **QnA system**
- Analytics-powered **Admin Dashboard**
- 🔐 User Authentication & Profile Management
- 📂 Document Ingestion & Indexing

---

## 🛠️ Tech Stack

- **Frontend** → Streamlit
- **Backend** → FastAPI
- **Database** → MySQL
- **AI Models** → Pegasus XSUM, Facebook BART
- **Deployment** → TBD

---

## 👨‍💻 Team

- Vidisha
- Varshita
- Ajith Reddy

---

## 📦 Model Checkpoints

The necessary pre-trained models for summarization and paraphrasing have been uploaded to Google Drive due to their large size (~2.08 GB each).

📥 **Download the models from the following links:**

- **facebook-bart-summary**: [Download](https://drive.google.com/drive/folders/17vlFTM0ZSE_DQ3YGDT8NNck1UiAe-2Ay?usp=drive_link)
- **facebook-bart-paraphrase**: [Download](https://drive.google.com/drive/folders/1fLjidgeBNmuxMcXKhwshfsQlALGeYsW-?usp=drive_link)
- **pegasus-xsum**: [Download](https://drive.google.com/drive/folders/1DU8I2ORp4J42CaA4ffXaSFY918ht0Vo4?usp=drive_link)

📁 **After downloading, place the model files inside the project directory at:**
```
backend/models/
```

---

## 📚 Dataset

The dataset used for training and evaluation is also available for download via Google Drive:

- **Dataset**: [Download](https://drive.google.com/file/d/1IOxJszNGT6B6ZJFatdH_ixEamusSTuOJ/view?usp=drive_link)

📁 **Download the dataset and place it in the project directory under:**
```
dataset/
```

⚠️ **Note:** If you are going to use your own dataset, make sure that it has `input_text`, `target_text`, and `task` (summary or paraphrase) columns.

---

## ⚙️ Setup Instructions

1. **Create a `.env` file** in the project root containing your environment variables—refer to `.env.example` for required variable names.

2. **Install project dependencies** using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure that the downloaded model checkpoints and dataset are in the paths specified above.**

4. **Run the application:**
   ```bash
   # Start the backend
   cd backend
   uvicorn main:app --reload

   # Start the frontend (in a new terminal)
   streamlit run app.py
   ```

---

## 📅 Development Timeline

| Week | Task |
|------|------|
| **1-2** | Setup repo, environment, authentication module |
| **3-4** | Document ingestion & indexing module |
| **5-6** | Summarization & translation modules |
| **7** | Admin dashboard & testing |
| **8** | Final review, bug fixing, presentation |

---

## 📂 Project Structure

```
TextMorph/
├── backend/
│   ├── models/          # Place downloaded model checkpoints here
│   ├── main.py          # FastAPI application
│   └── ...
├── frontend/
│   ├── app.py           # Streamlit application
│   └── ...
├── dataset/             # Place downloaded dataset here
├── .env                 # Environment variables
├── .env.example         # Example environment variables
├── requirements.txt     # Python dependencies
└── README.md           # This file
```

---

## 🎯 Project Goals

- ✅ User Authentication & Profile Management
- ✅ Document Ingestion & Indexing
- ✅ Query Processing & QnA
- ✅ Summarization & Simplification
- ✅ Language Translation
- ✅ Admin Dashboard

---

## 📄 License

[Add your license information here]

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---


