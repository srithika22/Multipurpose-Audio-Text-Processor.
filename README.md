
# Multimodal AI Assistant (Text, Speech & Image Processing)

This project is a beginner-friendly, end-to-end Python application built in **Google Colab** that showcases **multimodal input processing** — enabling machines to understand and respond to data in various forms such as **text**, **audio**, and **images**. It brings together core AI capabilities like OCR, speech recognition, and basic NLP into a single prototype.

---

## Project Goals

✔️ Learn how different AI modules (TTS, STT, OCR) work independently and together  
✔️ Build a practical assistant that simulates user interaction  
✔️ Understand real-world pipelines combining multiple data formats  
✔️ Gain hands-on experience with Python libraries, audio/image preprocessing, and basic automation

---

## 🔧 Features Overview

| Task                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| 🗣️ Text to Speech          | Convert user-entered text into speech using `gTTS`                          |
| 🎧 Speech to Text          | Convert `.mp3` or `.wav` files to text using `SpeechRecognition` and `pydub` |
| 🖼️ Image to Text (OCR)     | Extract text from `.jpg` or `.png` images using `Pillow` and `pytesseract` |
| ➕ Math Expression Solver  | Detect and solve simple math equations within extracted or typed text      |
| 🤖 Unified Pipeline        | Accept multiple input types (audio/image/text), extract & process meaning  |
| 🔁 Audio Output Response   | Respond with synthesized speech after understanding inputs                 |

---

## 🧰 Libraries Used

- [`gTTS`](https://pypi.org/project/gTTS/) – Google Text-to-Speech  
- [`SpeechRecognition`](https://pypi.org/project/SpeechRecognition/) – Recognize spoken words from audio  
- [`pydub`](https://github.com/jiaaro/pydub) – Convert between audio formats (e.g., MP3 to WAV)  
- [`pytesseract`](https://github.com/madmaze/pytesseract) – OCR using Tesseract engine  
- [`Pillow`](https://pypi.org/project/Pillow/) – Image processing library for reading files  
- Standard Python libraries: `os`, `re`, `io`, `eval`, `IPython.display`, etc.

---

## 🖼 Sample Use Cases

- 🎓 Learning assistant that reads scanned notes aloud  
- 🎤 Audio transcription tool for small recordings  
- 📝 Extracting math from a photo and solving it  
- 🤖 Simple AI chatbot combining voice, vision, and logic

---

## 🔌 How to Run (Google Colab)

1. **Open** `main.ipynb` in Google Colab
2. **Install requirements** via `!pip install` commands
3. **Upload files**:
   - `.mp3` or `.wav` audio for speech recognition
   - `.png` or `.jpg` images for text extraction
4. **Follow sections** to:
   - Transcribe, solve, or convert inputs
   - Generate audio responses

---

## 📌 Limitations

- Designed for demo/educational use — not production optimized  
- Works best with short text, simple math, and clean audio  
- Limited math expression handling (basic operators only)

---

## 🔮 Future Enhancements

-  Real-time voice input using microphone support  
-  Streamlit-based web app interface  
   Integrate pretrained NLP models for better question answering  
-  Multi-language support using translation pipelines  
-  Noise-robust speech recognition models

---

