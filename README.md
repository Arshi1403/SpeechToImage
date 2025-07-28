# 🖼️ Voice-Based AI Image Generator 🎤 ➜ 🧠 ➜ 🖼️

This Python app uses **voice input** to generate AI-powered images using **MonsterAPI's `txt2img` model**. Just speak your prompt, and the app listens, converts speech to text, sends it to the API, and downloads the resulting image to your computer.

---

## 🎯 Features

- 🎙️ Uses microphone input to capture speech
- 🔤 Converts voice to text using Google Speech Recognition
- 🧠 Sends text as a prompt to **MonsterAPI’s `txt2img`** model
- 🌄 Downloads and displays the generated image in your browser
- 🧾 Option to customize parameters like guidance, seed, aspect ratio

---

## 🛠️ Requirements

Install the dependencies using pip:

```bash
pip install monsterapi requests SpeechRecognition
