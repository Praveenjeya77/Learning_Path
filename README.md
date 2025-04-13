# 🎓 LearnMate - AI Learning Companion

**LearnMate** is an interactive AI-powered educational assistant built with Streamlit and Google Gemini. Whether you're planning your learning path, chatting with an AI twin, testing yourself with quizzes, generating audio summaries, or translating your thoughts regionally—LearnMate is your personalized study buddy!


## 🚀 Features

- 📘 **Learning Roadmap Generator**  
  Build a personalized, markdown-formatted learning plan based on your knowledge, goals, and learning style. Includes:
  - Step-by-step roadmap
  - YouTube video recommendations
  - Resources & study tips
  - Language translation support

- 💬 **AI Study Twin**  
  Interact with a friendly AI twin who:
  - Understands your confidence level
  - Suggests personalized strategies
  - Answers questions in a conversational flow

- 🧪 **Quiz Generator**  
  Test your understanding with:
  - Auto-generated MCQs (5 per topic)
  - Radio-button interface to answer
  - Instant feedback with correct answers
  - Downloadable quiz format

- 🎧 **Audio Summary Generator**  
  Paste any content and get:
  - MP3 audio summary via Text-to-Speech (TTS)
  - Downloadable audio file

- 🌐 **Regional Buddy**  
  Translate your messages into:
  - Hindi
  - Tamil
  - Telugu  
  Powered by Deep Translator, enabling cross-language learning assistance.

- 📌 **Sidebar Dashboard**  
  Track your:
  - Learning goals
  - To-do tasks
  - Completed study tasks  

## ⚠️ Notes

- This app uses **Google Generative AI (Gemini 1.5 Flash)**. You must have an API key from [Google AI Studio](https://makersuite.google.com/app) and save it in a `.env` file.

- Supported languages for translation and roadmap generation: `English`, `Hindi`, `Tamil`, `Telugu`.

- Audio summaries are generated using `gTTS`, which requires internet access.

## 🔮 Future Enhancements

- 🗣️ **Voice-based Interaction** – Allow users to speak questions and receive voice-based answers from the AI twin.
- 📈 **Progress Tracking Analytics** – Add visual dashboards to track learning milestones and quiz performance over time.
- 🧑‍🏫 **Tutor Matching** – Suggest real mentors or tutor resources based on user goals and region.
- 🧠 **Smarter Study Twin Memory** – Save long-term study history to provide more contextual responses.
- 🔒 **User Authentication** – Add secure login so users can save their goals, plans, and quiz data persistently.
