
# 🧠 Multi-Agent Research 

An AI-powered multi-agent  that automates research, analysis, and summarization of any topic using intelligent agent collaboration. Built with Streamlit, LangChain, OpenAI, and Tavily.

---

## 🚀 Features

- 🔍 **Search Agent (Tavily-powered)**  
  Fetches real-time, relevant, and reliable web data.

- 🧠 **Analysis Agent**  
  Processes collected data and extracts key insights.

- 📝 **Summarization Agent**  
  Generates structured, readable summaries.

- 🤖 **Multi-Agent Workflow**  
  Multiple AI agents collaborate for better results.

- 🌐 **Interactive UI**  
  Built using Streamlit for easy interaction.

- ⚡ **Real-Time Research**  
  Combines live search + AI reasoning.

---

## 🛠️ Tech Stack

- **Python 3.11+**
- **Streamlit**
- **LangChain / LangGraph**
- **OpenAI API**
- **Tavily API**

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/labsadik/Multi-agent-research.git
cd Multi-agent-research
````

---

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate:

**Windows**

```bash
.venv\Scripts\activate
```

**Mac/Linux**

```bash
source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

### 🔐 Get API Keys

* **OpenAI API Key:**
  [https://platform.openai.com/](https://platform.openai.com/)

* **Tavily API Key:**
  [https://tavily.com/](https://tavily.com/)

---

## ▶️ Running the Application

Run the Streamlit app:

```bash
streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

## 🧪 How It Works

1. User enters a research topic
2. **Tavily Search Agent** collects web data
3. **Analysis Agent** processes the information
4. **Summarization Agent** generates final output

---

## ⚠️ Common Issues

### ❌ Missing API Keys

Make sure `.env` file exists with:

```
OPENAI_API_KEY=...
TAVILY_API_KEY=...
```

---

### ❌ OpenAI Quota Error

* Add billing to your OpenAI account
* Or ensure your credits are available

---

### ❌ Tavily Not Working

* Check API key is correct
* Ensure internet connection is active

---

### ❌ Missing Modules

```bash
pip install -r requirements.txt
```

---

## 📌 Future Improvements

* Local LLM support (Ollama)
* Export research as PDF
* Multi-language support
* Advanced agent orchestration

---





