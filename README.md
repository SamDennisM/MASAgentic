# 📄 AI-Powered Resume Optimizer & Career Chatbot  
_Resume Tailoring + Career Guidance with Groq, LangChain & Agno_

![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red?logo=streamlit)
![LangChain](https://img.shields.io/badge/Orchestration-LangChain-blue?logo=python)
![Groq](https://img.shields.io/badge/LLM-Groq-green?logo=groq)
![Agno](https://img.shields.io/badge/Agentic-Agno-purple)
![spaCy](https://img.shields.io/badge/NLP-spaCy-lightblue?logo=spacy)

---

## 🌟 Features  
✅ Upload resumes in **PDF/DOCX**  
✅ Extract text & preprocess using **spaCy**  
✅ **AI Resume Analysis**: strengths, weaknesses, missing skills  
✅ **AI Resume Optimization**: tailor to job description  
✅ **Agentic Chatbot** powered by **Agno**  
✅ Knowledge Base of **historical placement data**  
✅ Interactive **Streamlit UI**  

---

## ⚙️ Tech Stack  
- **Frontend/UI** → Streamlit  
- **Resume Parsing** → pdfplumber, python-docx  
- **NLP** → spaCy (en_core_web_lg)  
- **LLM Engine** → Groq API  
- **Orchestration** → LangChain Agents  
- **Agentic Chatbot** → Agno Framework  
- **Knowledge Base** → Vector DB (placement history)  

---

## 🛠️ Installation  

```bash
# Clone repository
git clone https://github.com/yourusername/resume-optimizer.git
cd resume-optimizer

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
