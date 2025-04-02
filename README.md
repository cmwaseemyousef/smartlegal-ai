
# 🧠 SmartLegal AI – Free Legal Assistant with LangChain, FAISS & HuggingFace

🚀 A portfolio-ready Generative AI project built by **Waseem**, designed to answer legal questions using a Retrieval-Augmented Generation (RAG) pipeline – all with **100% free tools** and **zero paid APIs**!

---

## 📌 Features

- ✅ Built with **LangChain**, **FAISS**, and **Hugging Face Transformers**
- 📄 Analyzes and searches legal documents
- 🔍 Uses **semantic search** for question answering
- 🧠 Generates **natural language answers** with free LLMs
- 💻 Runs 100% **in Google Colab** – no downloads, no installs

---

## 📂 How It Works

1. **Text Input** – A legal document is chunked into manageable parts
2. **Embedding** – Each chunk is turned into a vector using `sentence-transformers`
3. **Vector Store** – Stored in FAISS (local, lightweight vector DB)
4. **Semantic Search** – Retrieves the most relevant chunk based on the user's question
5. **LLM Generation** – A HuggingFace model (e.g. `falcon-rw-1b`) generates a smart, human-like answer

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| `LangChain` | Document processing & RAG pipeline |
| `sentence-transformers` | Convert text to embeddings |
| `FAISS` | Fast semantic search |
| `Hugging Face Transformers` | Load open-source LLMs |
| `Google Colab` | Run everything in the cloud for free |

---

## 🚀 Run It Yourself (in Google Colab)

1. Open [this notebook in Google Colab](https://colab.research.google.com/)
2. Paste the full code from `smartlegal_ai_colab.ipynb`
3. Run all cells step-by-step
4. Ask your legal questions and get instant AI-powered answers!

---

## 📸 Example Output

```
❓ Question: What happens if someone wants to end the service?

📄 Retrieved Chunk:
Termination of services must be preceded by a 30-day written notice.

🤖 Final Answer:
The service provider must provide a 30-day written notice to the customer.
```

---

## ✨ Author

**Waseem** – AI Engineer in the making.  
Built with passion, guided by OpenAI's ChatGPT.

---

## 📬 Contact

Have ideas? Suggestions? Collaborations?  
Drop a message or connect via GitHub/LinkedIn!

---
