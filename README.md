# 📰 News Article Summariser using NLP & Transformers

## 🚀 Overview
This project focuses on building an **AI-powered News Article Summarization System** using **Natural Language Processing (NLP)** and **Transformer-based deep learning models**.

The system takes long news articles as input and generates **concise, meaningful summaries**, helping users quickly grasp essential information without reading the entire content.

---

## 🎯 Objective
- Automate summarization of lengthy news articles  
- Reduce reading time while preserving key information  
- Leverage **state-of-the-art transformer models (T5)** for text generation  

---

## 📂 Dataset
- **Dataset Used:** BBC News Summary Dataset
- link : https://www.kaggle.com/datasets/pariza/bbc-news-summary
- Contains:
  - News Articles  
  - Corresponding Human-written Summaries  
  - Categories such as Business, Politics, Sports, Tech, and Entertainment  

### 📊 Data Processing Steps
- Extracted dataset from ZIP file  
- Mapped articles with summaries  
- Created structured DataFrame  
- Cleaned and preprocessed text  
- Generated features like:
  - Article length  
  - Summary length  
  - Category labels  

---

## 📈 Exploratory Data Analysis (EDA)
Performed analysis to understand dataset patterns:
- Distribution of articles across categories  
- Average article vs summary length  
- Visualization using:
  - Bar plots  
  - Comparative graphs  

---

## 🧠 Model Architecture

### 🔹 Model Used:
- **T5 (Text-to-Text Transfer Transformer)**  

### 🔹 Why T5?
- Converts every NLP task into a **text-to-text problem**  
- Highly effective for:
  - Summarization  
  - Translation  
  - Text generation  

---

## ⚙️ Implementation Details

### 🛠️ Libraries Used
- `Transformers (HuggingFace)`  
- `PyTorch`  
- `Pandas`, `NumPy`  
- `Matplotlib`, `Seaborn`  

---

## 🔄 Workflow
1. **Data Loading & Extraction**  
2. **Data Cleaning & Structuring**  
3. **EDA & Visualization**  
4. **Train-Test Split**  
5. **Custom Dataset Class (PyTorch)**  
6. **Tokenization using T5 Tokenizer**  
7. **Model Training**  
8. **Summary Generation**  

---

## 🧩 Key Components

### 📌 Custom Dataset Class
- Built using PyTorch  
- Handles:
  - Tokenization  
  - Input-output mapping  
  - Efficient batching  

### ✂️ Tokenization
- Used **T5 Tokenizer**  
- Converted:
  - Articles → Input tokens  
  - Summaries → Target tokens  

---

## 📊 Results
- Model successfully generates **short, meaningful summaries**  
- Captures:
  - Core idea  
  - Important facts  
- Reduces noise and redundancy in articles  

---

## 💡 Features
✔ Automatic text summarization  
✔ Handles large news articles  
✔ Deep learning-based approach  
✔ Real-world dataset usage  
✔ Visualization & analysis included  

---

## 🔮 Future Improvements
- Fine-tune on larger datasets  
- Add **ROUGE score evaluation**  
- Deploy as:
  - Web app using Streamlit  
  - REST API  
- Improve summary coherence  

---

## 🖥️ How to Run

```bash
# Install dependencies
pip install transformers torch pandas numpy matplotlib seaborn

# Run the notebook
jupyter notebook News_Article_Summariser.ipynb
