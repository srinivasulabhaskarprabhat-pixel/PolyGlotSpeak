# PolyGlotSpeak
# 🌍 Polyglot Speak
### Multilingual Voice & Text Translation App using AWS Translate + Polly

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![HTML](https://img.shields.io/badge/Frontend-HTML%20CSS%20JS-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 🚀 Overview
Polyglot Speak is a multilingual web application that enables users to:

- Translate text between multiple languages  
- Convert speech to text using microphone input  
- Listen to translated output using natural voices  
- Perform voice-assisted multilingual communication in real time  

This project integrates **Amazon Translate**, **Amazon Polly**, and **Web Speech API** to build an interactive voice translation platform.

---

## ✨ Features

✅ Text Translation between multiple languages  
✅ Voice Input (Speech-to-Text)  
✅ Text-to-Speech using Amazon Polly  
✅ Source and Target Language Selection  
✅ Input and Output Audio Playback  
✅ Responsive Modern User Interface  
✅ Supports Voice-assisted Translation  

---

## 🏗 Architecture

```text
User Input (Text/Voice)
        |
        v
+------------------+
| Frontend (UI)    |
| HTML/CSS/JS      |
+------------------+
        |
        v
+------------------+
| AWS Translate    |
| Language Convert |
+------------------+
        |
Translated Text
        |
        v
+------------------+
| AWS Polly        |
| Speech Synthesis |
+------------------+
        |
Audio Output
        v
User Receives Translation
```

---

## 🛠 Tech Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### AWS Services
- Amazon Translate  
- Amazon Polly  
- AWS SDK for JavaScript  

### Additional APIs
- Web Speech API

---

## 📂 Project Structure

```bash
polyglot-speak/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── logo.png
│   ├── mic.png
│
└── README.md
```

---

## ⚙️ How It Works

1. User enters or speaks text.
2. Input text is sent to **AWS Translate**.
3. Translation is returned in selected target language.
4. **Amazon Polly** converts translated text into speech.
5. User can listen to both input and translated output.

---

## 🎤 Supported Languages

- English  
- German  
- Spanish  
- French  
- Portuguese  
- Korean  
- Hindi  
- Telugu  
- Tamil  
- Dutch  

*(Can be extended further.)*

---

## 🔧 Setup Instructions

### Clone Repository

```bash
git clone https://github.com/yourusername/polyglot-speak.git
cd polyglot-speak
```

---

## Configure AWS Credentials

Update credentials in script:

```javascript
AWS.config.credentials = new AWS.Credentials(
"YOUR_ACCESS_KEY",
"YOUR_SECRET_KEY"
);
```

> ⚠ For production use IAM roles or Cognito instead of exposing keys.

---

## Run Project

Open:

```bash
index.html
```

in browser.

---

## 📸 UI Preview

- Modern multilingual dashboard  
- Voice-enabled translator  
- Glassmorphism UI  
- Responsive design

---

## 🔮 Future Enhancements

- Auto language detection  
- Translation history  
- Chat-style translator interface  
- Download translated audio  
- AI conversation translator  
- Real-time multilingual chatbot

---

## 💡 Use Cases

- Language learning  
- Travel communication  
- Accessibility support  
- Cross-language conversations  
- Educational applications

---

## 📖 Learning Outcomes

Through this project I gained experience in:

- AWS Cloud Services Integration  
- Translation APIs  
- Speech Synthesis  
- Voice-enabled Web Applications  
- Frontend Development  
- Cloud-based Application Design

---

## 👨‍💻 Author

**Bhaskara Prabhat Srinivasula**

LinkedIn: www.linkedin.com/in/bhaskara-prabhat-srinivasula-96b7a32b6  
GitHub: https://github.com/BhaskarPrabhat

---

## ⭐ If you like this project
Give this repository a star!

---

### Break Language Barriers, Speak to the World 🌎
