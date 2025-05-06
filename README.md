# 📊 VizQuery-Agent  
**LLM-Powered Natural Language Data Visualization Assistant**

**VizQuery-Agent** is an LLM-powered tool that transforms natural language queries into insightful data visualizations from raw CSV data. Built with Streamlit, Together AI, and E2B’s secure sandbox environment, it enables effortless data exploration without any coding.

---

## 🔍 Key Features

- 💬 Natural language interface for data querying and analysis  
- 📊 Supports multiple visualization types: line, bar, scatter, pie, and bubble charts  
- 🧹 Automatic data cleaning and preprocessing  
- 🔐 Secure code execution in E2B's sandboxed environment  
- 🖥️ Interactive Streamlit interface for easy CSV upload and visualization  
- ⏱️ Real-time code execution and result rendering  
- 🤖 Model selection support for top-performing LLMs  

---

## 🧠 Supported LLMs (via Together AI)

- Meta-Llama 3.1 405B  
- Meta-Llama 3.3 70B  
- DeepSeek V3  
- Qwen 2.5 7B  
- Meta Llama 3.3 70B Instruct Turbo 

---

## 📁 Project Structure

```
vizquery-agent/
├── LLM_data_visualisation_agent.py    # Core logic for data processing and visualization
├── requirements.txt                   # List of required Python packages
├── README.md                          # Project documentation
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/thillai-c/vizquery-agent.git
cd vizquery-agent
```

### 2. Install the Dependencies

```bash
pip install -r requirements.txt
```

### 3. Get API Keys

- [Together AI API Key](https://api.together.ai/signin)  
- [E2B API Key](https://e2b.dev/docs/legacy/getting-started/api-key)

Enter the API keys into the app when prompted or via a `.env` file (optional).

### 4. Run the Streamlit App

```bash
streamlit run LLM_data_visualisation_agent.py
```

---

## 🧪 Tech Stack

- **Frontend**: Streamlit  
- **Language Models**: Together AI (Llama 3, DeepSeek, Qwen)  
- **Execution**: E2B Code Interpreter  
- **Backend**: Python  

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🔗 Links

- Main Repository: [https://github.com/thillai-c/vizquery-agent](https://github.com/thillai-c/vizquery-agent)  
- Application Code: [LLM_data_visualisation_agent.py](https://github.com/thillai-c/vizquery-agent/blob/main/LLM_data_visualisation_agent.py)
