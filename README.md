# 📝 Text Summarizer App

A web application that summarizes text/dialogues using the **T5 Transformer** model from HuggingFace. Built with FastAPI for the backend and a clean HTML/CSS frontend.

🚀 **Live Demo:** [Summaraizer Text](https://huggingface.co/spaces/karthik0055/text-summarizer-app)

---

## 🛠️ Tech Stack

- **Model:** T5-small (HuggingFace Transformers)
- **Backend:** FastAPI + Uvicorn
- **Frontend:** HTML, CSS, Vanilla JS
- **Deployment:** HuggingFace Spaces (Docker)

---

## ⚙️ How It Works

1. User inputs text or dialogue into the UI
2. FastAPI receives the input via POST request
3. Text is cleaned and tokenized using T5Tokenizer
4. T5 model generates a summary using beam search
5. Summary is returned and displayed on the UI

---

## 🚀 Run Locally

**1. Clone the repo**
```bash
git clone https://github.com/SudeepKarthik30/text-summarizer-app.git
cd text-summarizer-app
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the app**
```bash
uvicorn app:app --reload
```

**4. Open in browser**
```
http://127.0.0.1:8000
```

---

## 📁 Project Structure

```
text-summarizer-app/
├── app.py              # FastAPI backend
├── templates/
│   └── index.html      # Frontend UI
├── Dockerfile          # For HuggingFace deployment
├── requirements.txt    # Dependencies
└── README.md
```

---

## 📌 Features

- Clean and minimal UI
- Real-time text summarization
- Handles long dialogues and paragraphs
- Deployed and accessible publicly

---

## 🙋‍♂️ Author

**Thirumalasetty Karthik**  
[GitHub](https://github.com/SudeepKarthik30) • [HuggingFace](https://huggingface.co/karthik0055)
