# AgenticCoachAI

A Streamlit app that uses a CrewAI agent to answer questions about uploaded PDF documents.

Upload one or more PDFs (coaching materials, books, notes), then ask questions in a chat interface. The agent uses `PDFSearchTool` with semantic search over the documents, backed by GPT-4 and `text-embedding-ada-002`.

## Stack

Python · Streamlit · CrewAI · LlamaIndex · OpenAI GPT-4

## Run

```bash
pip install -r requirements.txt
cp .env.example .env  # add OPENAI_API_KEY
streamlit run app.py
```
