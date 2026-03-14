# KAUTILYA – AI Tutor Bot

KAUTILYA is an AI-powered tutor designed to help students learn interactively.
It can answer academic questions, generate quiz questions, explain concepts step-by-step, and even use uploaded study material (PDFs) to provide answers.

The goal of the project is to create a simple and intelligent learning assistant that adapts to the student's level and subject.

---

## Features

• AI powered academic question answering
• Multiple subjects support (Math, Physics, Chemistry, Biology, Computer Science, General Studies)
• Automatic quiz generation with explanations
• Difficulty levels (Easy / Medium / Hard)
• Student score tracking
• Upload PDF study material and ask questions from it
• Multi-language support (English / Hindi / Auto Detect)
• Interactive chat interface
• Built with Streamlit for a clean and simple UI

---

## Screenshots

images/img1.jpeg

images/img2.jpeg

images/img3.jpeg

images/img4.jpeg

images/img5.jpeg

images/img6.jpeg

images/img7.jpeg

images/img8.jpeg

images/img9.jpeg


---

## Technology Stack

Python
Streamlit
OpenRouter API (OpenAI compatible models)
PyPDF
python-dotenv
Streamlit Mic Recorder

---


## Installation and Setup

### 1. Clone the repository

```
git clone https://github.com/yourusername/kautilya-ai-tutor.git
```

```
cd kautilya-ai-tutor
```

---

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

### 3. Add your API Key

Create a `.env` file in the project folder and add:

```
OPENROUTER_API_KEY=your_api_key_here
```

---

### 4. Run the application

```
streamlit run KAUTILYA.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## How It Works

1. Student enters their name and selects a subject
2. The AI tutor answers questions using a language model
3. Quiz questions are generated dynamically based on class level and difficulty
4. If a PDF is uploaded, the AI answers questions using the uploaded study material
5. The student receives explanations and quiz feedback instantly

---

## Future Improvements

Voice interaction for asking questions
Student progress tracking system
More advanced quiz analytics
Integration with school learning platforms

---

## Author

Prashant Choudhary
B.Tech CSE (AI)

---

## License

This project is for educational purposes.
