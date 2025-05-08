
# 🚀 InsightViz: AI-Powered Insights at a Glance

InsightViz is a powerful Generative AI-based web application that allows users to upload CSV datasets and query them using natural language. The system interprets these queries with the help of advanced Large Language Models (LLMs) and generates visualizations and analytical insights — all without writing a single line of code.

![InsightViz UI](./UI%201.jpg)


---

## 📌 Table of Contents

- [🎯 Features](#-features)
- [🧠 How It Works](#-how-it-works)
- [🛠️ Technologies Used](#-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [🔒 Security](#-security)
- [📷 Sample Output](#-sample-output)
- [🧪 Testing Strategy](#-testing-strategy)
- [📚 Future Enhancements](#-future-enhancements)
- [🧾 License](#-license)

---

## 🎯 Features

- 🧠 **Natural Language Query Interpretation**
- 📈 **Automatic Chart Generation** (Bar, Line, Pie, Scatter)
- 🗃️ **CSV Upload & Data Preview**
- 🧾 **Real-time Statistical Summaries**
- 🔐 **Secure Code Execution via E2B Sandbox**
- 🔄 **Model Selection** from Meta-Llama, Qwen, DeepSeek, etc.
- 🖥️ **Streamlit-based Interactive UI**

---

## 🧠 How It Works

1. **User uploads a CSV** and enters a question like:
   > "Can you compare the average cost for two people across categories?"

2. **LLM (e.g., Meta-Llama via Together AI)** interprets the question and generates Python code.

3. **The code is executed** securely in the **E2B sandbox** environment.

4. **InsightViz returns visual output** like graphs, tables, or statistical summaries.

---

## 🛠️ Technologies Used

| Component         | Technology                          |
|------------------|-------------------------------------|
| Programming Lang | Python                              |
| Web Framework    | Streamlit                           |
| LLM API          | Together AI                         |
| Sandbox Engine   | E2B Secure Code Interpreter         |
| Visualization    | Matplotlib, Plotly, Seaborn         |
| Data Handling    | Pandas                              |
| Optional NLP     | HuggingFace Transformers            |
| Image Handling   | PIL, Base64                         |
| Dev Tools        | Google Colab, Jupyter, GitHub       |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/insightviz.git
cd insightviz
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install streamlit pandas matplotlib plotly together e2b-code-interpreter Pillow
```

### 3. Run the Application

```bash
streamlit run ai_data_visualisation_agent.py
```

### 4. API Keys

Before running, provide your API keys in the sidebar of the UI:

* 🔑 **Together AI API Key** — [Get it here](https://api.together.ai/signin)
* 🔑 **E2B API Key** — [Get it here](https://e2b.dev/docs/legacy/getting-started/api-key)

---

## 🔒 Security

All user-submitted code is executed **within the E2B sandbox**, ensuring a **safe and isolated environment**. No arbitrary code touches your local environment or host system.

---

## 📷 Sample Output

![InsightViz Output](./UI%202.jpg)
![InsightViz Output2](./UI%203.jpg.png)
<!-- Optional: Replace with your own -->

* Upload CSV ➜ Ask question ➜ Receive relevant graphs/statistics
* Works on numerical, categorical, and mixed datasets

---

## 🧪 Testing Strategy

### ✅ Manual Testing:

* Input variations (short, long, malformed questions)
* Dataset types and sizes
* User experience feedback

### ✅ Unit Testing:

* Data parsing, model interaction, code extraction

### ✅ Integration Testing:

* LLM ↔ Sandbox ↔ UI pipeline

### ✅ Performance Testing:

* Render time and model response speed for large CSVs

---

## 📚 Future Enhancements

* 📊 **Advanced analytics**: clustering, forecasting, outlier detection
* 🎨 **Chart customization**: colors, titles, axes formatting
* 🌍 **Multilingual Query Support**
* 💬 **Conversational mode** (LLM memory)
* 📥 **Export Insights as PDF/Slides**

---

## 🧾 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

> Made with ❤️ using Generative AI + Python + Streamlit

```
