# openai-assistant-app
# 🤖 OpenAI Assistant App

This is a Streamlit web app that lets you interact with OpenAI's GPT-4 and GPT-4 Vision APIs using:

- ✅ Text prompts
- 🖼️ Image uploads (analyzed via GPT-4 Vision)
- 📄 File uploads: PDF, TXT, DOCX, and XLSX

---

## 🚀 Features

- GPT-4 and GPT-4 Vision integration
- Document parsing and summarization
- Interactive prompt input
- Secure API key usage

---

## 📦 Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## 🔐 API Key Setup

Set your OpenAI API key in your environment:

### Windows (CMD)
```bash
set OPENAI_API_KEY=your_key_here
```

### macOS/Linux
```bash
export OPENAI_API_KEY=your_key_here
```

---

## 🌐 Deployment (Streamlit Cloud)

1. Push this project to GitHub
2. Go to [https://streamlit.io/cloud](https://streamlit.io/cloud)
3. Create a new app from your GitHub repo
4. Set `OPENAI_API_KEY` under Secrets
5. Click **Deploy** 🚀

---

## 📁 File Structure

```
openai_assistant/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # Python dependencies
├── .gitignore            # Cache and secrets exclusion
└── .streamlit/
    └── (Optional secrets.toml for local testing)
```

---

## 📝 License

MIT – Use and modify freely.
