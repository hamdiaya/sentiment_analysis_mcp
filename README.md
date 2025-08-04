# MCP Sentiment Analysis Server

This project is a **simple sentiment analysis server** built with [Gradio](https://gradio.app/), powered by [TextBlob](https://textblob.readthedocs.io/en/dev/), and integrated with the **MCP (Model-Component Protocol)** for remote communication.

## 📌 Features

- Sentiment analysis of English text: returns **polarity**, **subjectivity**, and a basic **assessment**.
- Exposes a Gradio UI and an MCP-compatible API endpoint.
- Lightweight and beginner-friendly implementation for learning MCP.

## 🧠 Technologies Used

- Python 3
- [Gradio](https://www.gradio.app/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)
- JSON + SSE (for MCP transport)

## 🚀 How to Run

1. Install dependencies:

```bash
pip install gradio textblob
python -m textblob.download_corpora
```
2. Run the server:
   ```
   python app.py
   ```
3.The Gradio interface will launch at http://localhost:7860 and expose the MCP server at http://localhost:7860/gradio_api/mcp/sse
   
