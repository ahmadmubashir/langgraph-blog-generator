# LangGraph Blog Generator

This project demonstrates a simple LangGraph workflow using OpenAI to:

* Generate a blog outline
* Generate a full blog from the outline
* Save results into a Word document (.docx)

## 🚀 Features

* Sequential LangGraph pipeline
* OpenAI integration
* Automatic Word export
* Clean and minimal implementation

## 🧠 Workflow

Topic → Outline → Blog → Word File

## 📦 Installation

```bash
pip install -r requirements.txt
```

## 🔑 Setup API Key

```bash
export OPENAI_API_KEY="your_api_key"
```

or (Windows):

```bash
set OPENAI_API_KEY=your_api_key
```

## ▶️ Run

```bash
python app.py
```

## 📄 Output

* Generates:

  * Blog outline
  * Full blog
  * `blog_output.docx`

## 🛠 Tech Stack

* LangGraph
* LangChain
* OpenAI
* Python-docx

## 📌 Future Improvements

* Streamlit UI
* Multi-agent workflow
* Blog styling
* Batch generation

---
