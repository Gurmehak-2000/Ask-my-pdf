# Ask-my-pdf

````markdown
# Ask-My-PDF 🧠📄

Ask-My-PDF is an AI-powered application that allows users to upload a PDF and interact with its contents through natural language questions. It uses **LangChain**, **ChromaDB**, and **OpenAI/LLMs** to extract, embed, and retrieve information in real time.

---

## 🔍 Features

- 📁 Upload any PDF file
- 🤖 Ask questions about the content in plain English
- 🔄 Instant AI-powered answers using LLMs
- 🧠 Vector store with document embeddings
- 🚀 Built with LangChain, ChromaDB, and Streamlit

---

## 🧰 Tech Stack

- Python
- Streamlit
- LangChain
- ChromaDB
- OpenAI LLM (or HuggingFace, optional)
- FAISS (optional vector store backend)

---

## 📂 File Structure

```bash
ask-my-pdf/
│
├── app.py                  # Streamlit UI and core logic
├── requirements.txt        # Python dependencies
├── .gitignore              # To ignore venv and unnecessary files
├── .env                    # Store your API keys securely
├── Lecture_3.pdf           # Sample PDF
├── README.md               # Project documentation (this file)
└── venv/                   # (Excluded) Virtual environment
````

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Gurmehak-2000/ask-my-pdf.git
cd ask-my-pdf
```

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/Scripts/activate  # or source venv/bin/activate for Mac/Linux
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Add Your API Key

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_key_here
```

### 5. Run the App

```bash
streamlit run app.py
```

---

## 📸 Preview

![screenshot](link_to_screenshot_if_available)

---

## 🧠 How It Works (Simple Flow)

1. **PDF Loader** extracts content using LangChain.
2. **Text Splitter** breaks content into manageable chunks.
3. **Embeddings** are created using OpenAI (or other LLMs).
4. **ChromaDB** stores and indexes embeddings.
5. **LLM** answers user queries based on retrieved document chunks.

---

## 💡 Use Cases

* Academic research
* Document summarization
* Legal/medical document querying
* Quick insight extraction from large PDFs

---

## 🚧 Known Limitations

* Heavy dependencies (Torch) may cause GitHub push issues
* Works best with text-based PDFs (not scanned images)

---

## 🙌 Acknowledgments

* [LangChain](https://github.com/hwchase17/langchain)
* [ChromaDB](https://github.com/chroma-core/chroma)
* [Streamlit](https://streamlit.io/)

---

## 📬 Connect with Me

**Gurmehak Kour**
📫 [LinkedIn](https://linkedin.com/in/gurmehak-kour)
📁 [Portfolio](#) (optional)

---

> ⚠️ **Note**: The `venv/` folder is excluded from GitHub for size limitations. Please create a virtual environment manually.

```

---

Let me know if you want:
- A **PDF version** of this
- A **custom logo** or banner
- Auto-generated **badges** for GitHub (like "Made with Python", "OpenAI", etc.)

Want me to fill in the screenshot link too? Just upload a preview image of your app.
```
