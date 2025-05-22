# 🎙️ Voice-Driven Automation Builder

A real-time, voice-controlled automation interface that uses the browser’s built-in WebKit Speech Recognition API to convert speech to text and seamlessly integrate with the **n8n** open-source workflow automation platform. This enables users to build, manage, and trigger workflows using only their voice.

---

## 🔧 What is n8n?

[n8n (pronounced "n-eight-n")](https://n8n.io/) is a powerful, extendable open-source workflow automation tool. Think of it as an open-source alternative to Zapier. It allows users to connect various services via APIs, build complex logic, and automate processes — all without writing much code.

---

## 🧠 Key Features

- 🎤 **Real-time voice-to-text** using `webkitSpeechRecognition`
- 🔄 **Automatic command parsing** to identify triggers and actions
- ⚙️ **Workflow generation** and execution via n8n’s REST API
- 💬 **Custom command templates** for intuitive automation setup
- 🌐 **Web-based UI** with live speech feedback

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (vanilla)
- **Speech Recognition**: `webkitSpeechRecognition` (Chrome only)
- **Automation Backend**: [n8n](https://n8n.io) (self-hosted or cloud)
- **HTTP Client**: Fetch API (REST integration with n8n)

---

## 📦 Project Structure
-voice-driven-automation-builder/
-├── index.html # UI for voice control
-├── style.css # Styling
-├── script.js # Voice recognition + integration logic
-├── README.md # Project documentation
