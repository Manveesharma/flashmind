# 🌟 FlashMind AI — Smart CLI Quiz Game

> 🧠 An intelligent, adaptive, and voice-assisted quiz experience — right from your terminal.

FlashMind AI is a Python-powered CLI quiz app that fetches **live questions from Open Trivia DB**, adapts difficulty based on your performance, and motivates you through **AI-style encouragements, memory reinforcement, and speech feedback**.

---

## 🚀 Features

### 💡 Adaptive Intelligence
- Difficulty adjusts automatically using a **mini skill score model** based on your speed & accuracy.
- Missed topics are saved and **revisited next time** to help you improve.

### 🔊 Voice Interaction
- Uses `pyttsx3` for **offline text-to-speech**, making the experience engaging.
- Optional — you can disable voice if you prefer quiet mode.

### 🧩 Live Quiz API
- Fetches **real questions** from [Open Trivia DB](https://opentdb.com/).
- Categories & answers are decoded dynamically each round.

### 🧠 Memory Reinforcement
- Saves your **wrong questions** in `flashmind_mem.json`.
- On the next run, it starts with your weak topics.

### 🎯 Motivational Game Design
- “🔥 Combo Bonus” for consecutive correct answers.
- “⚡ Speed Bonus” for answering quickly.
- Friendly chatbot-style feedback when you get 3 wrong or 5 right in a row.

### 💾 Lightweight & Offline-Ready
- Works fully offline after installation (only quiz fetching needs the internet).
- No external UI or web dependency — pure terminal magic.

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/flashmind-cli.git
cd flashmind-cli
pip install -r requirements.txt
# flashmind
