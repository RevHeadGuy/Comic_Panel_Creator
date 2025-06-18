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
   
3. ** Add API Keys:In the notebook:**

GROQ_API_KEY = "your_groq_api_key"

UNSPLASH_ACCESS_KEY = "your_unsplash_api_key"

Get Groq key

Get Unsplash key

💡 How to Use

Enter a scene prompt (e.g., “A robot time travels to the dinosaur era”)

Choose:

Comic style (funny, sci-fi, noir, etc.)

Characters (comma-separated names)

Number of panels (1–4)

Click Generate Comic

View:

Script

First panel image

Narration (audio)

Downloadable PDF





