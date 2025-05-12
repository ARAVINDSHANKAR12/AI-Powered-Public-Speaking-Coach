# 🗣️ AI-Powered Public Speaking Coach

An intelligent web-based platform designed to enhance your public speaking skills using cutting-edge AI technologies like OpenAI Whisper, MFCC feature extraction, Hugging Face models, and LLaMA 3.2.

## 🚀 Overview

This project is a speech training platform that helps users improve clarity, coherence, and vocal expression through interactive AI-driven speaking exercises. Whether preparing for presentations, debates, or everyday communication, this tool provides personalized feedback to make your speaking more impactful.

## 🎯 Key Features

- **🎤 Real-time Transcription**: Utilizes **OpenAI Whisper** to convert spoken words into accurate text.
- **🔊 Speech Clarity Analysis**: Employs **MFCC (Mel-Frequency Cepstral Coefficients)** to assess vocal clarity and articulation.
- **😃 Emotion Detection**: Leverages **Hugging Face NLP models** to identify emotional tone and provide expressive feedback.
- **🧠 Smart Feedback Engine**: Uses **LLaMA 3.2** to generate human-like, constructive feedback tailored to the user’s performance.
- **🎮 Interactive Exercises**: Includes 3 AI-powered speaking tasks with **adaptive difficulty** and **AI-generated distractors** for realistic practice.
- **📈 Skill Tracking**: Helps users measure improvement over time in coherence, clarity, and expression.

## 🛠️ Tech Stack

- **Frontend**: HTML/CSS, JavaScript (or specify framework if used)
- **Backend**: Python (Flask/FastAPI)
- **AI/ML Libraries**:
  - [OpenAI Whisper](https://github.com/openai/whisper) – Speech-to-text transcription
  - MFCC – Feature extraction for vocal clarity
  - [Hugging Face Transformers](https://huggingface.co/models) – Emotion detection
  - LLaMA 3.2 – Natural language generation for feedback

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/ai-speaking-coach.git
cd ai-speaking-coach

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
