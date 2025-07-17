# 🤖 AI Career Coach: Job Application Copilot with Gradio + watsonx.ai

Welcome to your personalized AI Job Application Coach powered by IBM watsonx.ai, open source LLMs, and Gradio. This interactive app helps job seekers improve their resumes, generate personalized cover letters, and receive career advice using cutting-edge LLMs.

---

## 🚀 Features

- **Resume Polisher**: Enhance your resume using AI feedback tailored to the position.
- **Cover Letter Generator**: Generate personalized cover letters for specific job roles.
- **Career Advisor**: Get strategic recommendations based on your resume and job descriptions.
- **LLM Q&A Bot**: Ask open-ended career-related questions powered by Meta’s LLaMA-3 model on IBM’s watsonx.ai.

---

## 🧠 Tech Stack

- `Python 3.11`
- [`Gradio`](https://gradio.app/)
- [`IBM watsonx.ai`](https://www.ibm.com/products/watsonx-ai)
- HuggingFace Meta LLaMA-3 (via watsonx.ai)

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-career-coach.git
cd ai-career-coach
```

### 2. Create a Virtual Environment

```bash
pip install virtualenv
virtualenv my_env
source my_env/bin/activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

---

## ⚙️ Running the Apps

Each app has its own `.py` file:

### ✍️ Run Resume Polisher

```bash
python resume_polisher.py
```

### 📄 Run Cover Letter Generator

```bash
python cover_letter.py
```

### 💡 Run Career Advisor

```bash
python career_advisor.py
```

### 🤖 Run Q&A Chatbot

```bash
python llm_chat.py
```

---

## 📁 File Structure

```
.
├── gradio_demo.py
├── simple_llm.py
├── llm_chat.py
├── resume_polisher.py
├── cover_letter.py
├── career_advisor.py
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgments

Built with ❤️ using IBM watsonx.ai and Gradio.
