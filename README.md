# GenAI-assistant

# 🤖 Smart Assistant for Research Summarization (GenAI Assistant)

This project is a document-aware GenAI assistant that:
- 📄 Accepts uploaded PDFs
- 🧠 Automatically summarizes content
- 💬 Answers user questions based on document context
- 🎯 Poses logic-based “Challenge Me” questions and evaluates responses
- 🔎 Uses only document-based evidence (no hallucination)

> ✅ Fully powered by Hugging Face models — no OpenAI API key needed  
> ✅ Runs completely inside Google Colab with Gradio UI

---

## 🚀 Demo

🎥 [Demo Video – YouTube or Loom Link Here](#)

🧪 [Try it in Colab →](https://colab.research.google.com/drive/1NAA4t4rikX4qGSPI6NzI25VS1yHj3gBD?usp=sharing)


---

## 🧱 Project Architecture

```plaintext
PDF Upload → Text Extraction → Chunking → Embeddings (MiniLM) → 
→ Vector Search (FAISS) → QA / Summary / Logic Questions (DistilBERT, BART, GPT2)
