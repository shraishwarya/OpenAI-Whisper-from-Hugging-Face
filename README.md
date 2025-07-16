# OpenAI-Whisper-from-Hugging-Face

---

# 🎧 Whisper Speech-to-Text & Translation (Google Colab)

This repository contains a Colab notebook implementation of **OpenAI's Whisper model** for **automatic speech recognition (ASR)** and **speech translation**, powered by **Hugging Face Transformers**.

👉 **[Open the Colab Notebook](https://colab.research.google.com/drive/11Yl9Oy6tTZ5OurxoY8LgYlizlEuhZzVw)**

---

## 📌 Project Highlights

* Uses the `openai/whisper` models via Hugging Face 🤗
* Transcribes audio files (`.mp3`, `.wav`, etc.)
* Translates spoken language to English (or other supported languages)
* Fully cloud-based: no local setup required
* Interactive and beginner-friendly

---

## 📁 Repository Contents

```
whisper-colab/
├── Whisper_ASR_Translation.ipynb   # Main Colab notebook
├── README.md                       # This file
```

---

## 🔧 Technologies Used

* [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
* [Torchaudio](https://pytorch.org/audio/stable/index.html)
* [Google Colab](https://colab.research.google.com/)
* Python 3.10+

---

## ⚙️ How to Use

1. **Open the Notebook** in Colab:
   [Click here to open](https://colab.research.google.com/drive/11Yl9Oy6tTZ5OurxoY8LgYlizlEuhZzVw)

2. **Upload Your Audio File** (`.mp3`, `.wav`)

3. **Run the Cells** to:

   * Install dependencies
   * Load the Whisper model
   * Transcribe or translate your audio

---

## 📝 Sample Output

```text
Audio File: bonjour_audio.mp3

Transcription: bonjour le monde
Translation (English): hello world
```

---

## 📦 Dependencies (installed inside Colab)

```python
!pip install transformers torchaudio --quiet
```

Optional (for audio preprocessing):

```python
!pip install librosa pydub --quiet
```

---

## 🙌 Credits

* OpenAI for Whisper
* Hugging Face for model hosting
* Google Colab for free compute!

---



