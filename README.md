# CodeAlpha AI Suite 🤖

> **CodeAlpha Internship — Artificial Intelligence Domain**
> Completed Tasks: Task 1 (Language Translation Tool) + Task 2 (Chatbot for FAQs)

---

## 🚀 Live Demo

Open `index.html` directly in any browser — **no server needed, no API key required!**

---

## ✅ Task 1: Language Translation Tool

### Features
- 🌍 Translate between **25+ languages** (English, Hindi, Spanish, French, German, Chinese, Arabic, Japanese, Korean, and more)
- 🔄 **Auto language detection** for source text
- ⇄ **Swap languages** button to reverse translation instantly
- 📋 **Copy to clipboard** button for translated output
- 🔊 **Text-to-speech** for both source and translated text
- ⚡ **Free API** — uses MyMemory Translation API (no key needed)
- 📊 Character count with 5000 char limit

### Tech Stack
- Vanilla HTML, CSS, JavaScript
- [MyMemory Translation API](https://mymemory.translated.net/) (free, no auth)
- Web Speech API (for text-to-speech)

---

## ✅ Task 2: Chatbot for FAQs

### Features
- 🧠 **NLP-powered** matching using **cosine similarity** algorithm
- 📚 **30+ FAQ knowledge base** about CodeAlpha internship
- ⚡ **No backend** — fully client-side NLP
- 💬 **Quick-question buttons** for common queries
- ✍️ Typing indicator animation
- 🎯 Topics covered: certificates, tasks, GitHub, LinkedIn, perks, LOR, tools, APIs

### NLP Implementation
```
User Input → Tokenize → Remove stop words → TF vector
FAQ Questions → Tokenize → Remove stop words → TF vector
Cosine Similarity → Best Match → Display Answer
```

### Tech Stack
- Vanilla HTML, CSS, JavaScript
- Custom NLP: Tokenization + Stop word removal + Cosine Similarity
- No external NLP libraries (pure JS implementation)

---

## 📁 Project Structure

```
CodeAlpha_AITasks/
├── index.html    ← Complete app (single file)
└── README.md     ← This file
```

---

## 🛠️ How to Run

1. Download / clone this repository
2. Open `index.html` in any modern browser
3. **Translator Tab**: Type text → Select languages → Click Translate
4. **FAQ Bot Tab**: Type your question or click a suggested question

---

## 📸 Screenshots

### Translation Tool
- Multi-language selector with 25+ languages
- Side-by-side input/output panels
- Copy & Text-to-speech buttons

### FAQ Chatbot
- Chat-style UI with bot/user bubbles
- Suggested question chips
- Real-time cosine similarity matching





