

# Contextual Car Manual Assistant (RAG Chatbot)

This project is a **proof-of-concept context-aware chatbot** that helps drivers understand their vehicle's warning messages and recommended actions.
It leverages **Retrieval-Augmented Generation (RAG)** using **LangChain** and an **LLM** (DeepSeek / GPT / other) to answer queries based on a car manual.

The chatbot can be easily extended to support in-car conversational interfaces through **Text-to-Speech (TTS)** systems.

---

## 🚗 Project Goal

Automobile manufacturers are increasingly exploring **AI-based assistants** for vehicles. This project demonstrates how to:

✅ Parse and ingest an HTML-based car manual
✅ Create document chunks with embeddings
✅ Build a RAG pipeline using LangChain and an LLM
✅ Answer driver queries with **contextual, manual-based responses**

---

## 📚 Example Use Case

**User Query:**

> "The Gasoline Particular Filter Full warning has appeared. What does this mean and what should I do about it?"

**Assistant Response (example):**

> "The Gasoline Particulate Filter Full warning indicates that the filter is full of particulates. You should drive the vehicle at highway speeds for at least 15 minutes to allow the filter to regenerate..."

---

## 🛠️ Tech Stack

* **LangChain** (RAG Pipeline)
* **LLM:** DeepSeek / GPT-4o-mini / OpenAI / other
* **Document Loader:** HTML (car manual)
* **Embeddings:** DeepSeek / OpenAI Embeddings
* **Vector Store:** Chroma DB
* **Environment:** Python, Jupyter Notebook

---

## 🚀 Project Structure

```
├── notebook.ipynb          # Main implementation notebook
├── mg-zs-warning-messages.html  # Car manual HTML document
├── README.md               # Project documentation (you are here)
├── requirements.txt        # Python dependencies
```

---

## ⚙️ Setup & Usage

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/contextual-car-assistant.git
cd contextual-car-assistant
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set API Key

```bash
export DEEPSEEK_API_KEY=your_deepseek_api_key
# or
export OPENAI_API_KEY=your_openai_api_key
```

### 4️⃣ Run Notebook

Open `notebook.ipynb` and run the cells.

---

## 💡 Features

* ✅ **HTML Manual Parsing** → Load and preprocess car manual
* ✅ **Chunking** → Split text into context-friendly chunks
* ✅ **Embeddings** → Generate semantic representations of chunks
* ✅ **RAG Pipeline** → Retrieve relevant chunks + generate final answer
* ✅ **LLM-based Reasoning** → Answer user queries accurately and contextually

---

## ✨ Possible Extensions

* Add **TTS (Text-to-Speech)** integration for in-car audio responses
* Ingest **multi-manual documents** and vehicle-specific knowledge
* Implement **conversation memory** to enable multi-turn dialogues
* Support **voice-based query input**

---

## 🤝 Credits

This project was implemented as part of an **LLM exploration project** for **automotive AI applications**.
The car manual used is from an **MG ZS SUV** (publicly available document).

---

## 📜 License

MIT License.

---

## 📫 Contact

If you found this project interesting or want to collaborate:

* **GitHub:** [yourusername](https://github.com/noctis122)
* **Email:** [your.email@example.com](mailto:farhatmouhib76@ieee.org)

---

---


