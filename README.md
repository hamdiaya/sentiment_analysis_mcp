# MCP Sentiment Analysis Server

This project is a **simple sentiment analysis server** built with [Gradio](https://gradio.app/), powered by [TextBlob](https://textblob.readthedocs.io/en/dev/), and integrated with the **MCP (Model-Component Protocol)** for remote communication.

---

## 📌 Features

- Sentiment analysis of English text: returns **polarity**, **subjectivity**, and a basic **assessment**.
- Exposes a Gradio UI and an MCP-compatible API endpoint.
- Lightweight and beginner-friendly implementation for learning MCP.

---

## 🧠 Technologies Used

- Python 3
- [Gradio](https://www.gradio.app/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)
- JSON + SSE (for MCP transport)

---

## 🚀 How to Run

### 1. Install Dependencies:

Make sure you have Python 3 installed, then run:

```bash
pip install gradio textblob
python -m textblob.download_corpora
```
### 2.  Run the Server:

Make sure you're in the project folder and run:

```bash
python app.py
```
### 3.  Access the Interface:

After running the server, you'll get:

    🖥 Gradio Interface:
    Open your browser and go to:
    http://localhost:7860

    🔗 MCP Server Endpoint:
    Accessible at:
    http://localhost:7860/gradio_api/mcp/sse
