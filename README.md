# 🎨 Comic Panel Creator 

Create AI-generated comic strips from simple prompts using large language models and image generation APIs. The app uses Groq (LLaMA3) to write scripts, Unsplash to fetch scene images, and overlays speech bubbles on panels. Optional audio and PDF export included.

---

## 🚀 Features

- ✍️ AI-generated comic scripts via **Groq LLaMA3**
- 🖼️ Automatic image selection using **Unsplash API**
- 🗯️ Auto-layout speech bubbles drawn over comic panels
- 🎤 Voice narration using **gTTS**
- 📄 Export to PDF comic book
- 🧡 Stylish Gradio UI with dark mode + orange theme
- 📦 Runs entirely in Google Colab or locally

---

## 🧰 Tech Stack

- 🧠 `Groq API` (OpenAI-compatible LLM)
- 🖼️ `Unsplash API` (image fetching)
- 🎛️ `Gradio` (UI)
- 🗯️ `Pillow` (image drawing)
- 🔊 `gTTS` (text-to-speech)
- 📄 `fpdf` (PDF export)
- 🐍 Python 3

---

## 🔧 Setup Instructions

1. **Clone or open in Colab:**
 
2. **Install dependencies:**

Already included in the notebook:
```python
!pip install openai==0.28 gradio requests pillow fpdf gTTS


