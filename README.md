# 📚 AI Exam Answer Evaluator & Feedback Generator

An AI-powered system that evaluates student exam answer sheets and generates feedback automatically using OCR + LLM.

This project is designed to help teachers reduce manual correction time by extracting questions and answers from PDFs (typed or handwritten), assigning marks, generating feedback, and exporting results.

---

## 🚀 Features

✅ Upload Teacher Question Paper PDF  
✅ Upload Student Answer Sheet PDF  
✅ Extract questions using OCR (EasyOCR)  
✅ Extract student answers from PDF  
✅ AI-based evaluation using Groq LLM  
✅ Marks and grade calculation  
✅ Feedback generation (Strengths + Improvements)  
✅ Export evaluation report as CSV  
✅ Streamlit based professional dashboard UI  

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **EasyOCR**
- **PyMuPDF (fitz)**
- **Groq API**
- **Pandas**
- **JSON**
- **PDF Processing**

---
## 📂 Project Structure

AI-Exam-Answer-Evaluator-Feedback-Generator/
│
├── gen_ai_project.ipynb # Main Colab notebook
├── app.py # Streamlit application (if added)
├── requirements.txt # Dependencies (if added)
└── README.md # Project documentation


---

## ⚙️ How It Works

1. Teacher uploads **Question Paper PDF**
2. Student uploads **Answer Sheet PDF**
3. OCR extracts text from both PDFs
4. System matches questions and answers
5. Groq LLM evaluates answers based on the question
6. Marks, feedback and grade are generated
7. Final results exported as CSV report

---

## 📌 Installation & Setup (Local)

### Step 1: Clone Repository
```bash
git clone https://github.com/Kaviyadharshini23/AI-Exam-Answer-Evaluator-Feedback-Generator.git
cd AI-Exam-Answer-Evaluator-Feedback-Generator
📊 Output

The system generates:

Extracted questions & answers

Marks per question

Total score

Grade

AI feedback

CSV report export

🎯 Use Cases

📌 Schools and colleges
📌 Online exam platforms
📌 Teachers and training institutes
📌 AI-based assessment tools
