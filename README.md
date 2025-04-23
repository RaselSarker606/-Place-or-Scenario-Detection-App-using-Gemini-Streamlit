# 🗺️ Place or Scenario Detection App using Gemini & Streamlit

## 📖 Overview

In this project Users can simply upload an image (e.g., a university, monument, or building), and the system analyzes it to return structured, informative details such as its name, type, country, establishment year, and description—all in real time through a clean **Streamlit** interface.

---

## 📂 Features

- 🖼️ **Image-Based Place Detection**  
  Upload a photo to identify famous locations, institutions, or public areas.

- 🌍 **Structured Output**  
  Returns official name, type (e.g., university, landmark), location, founding year, and description.

- 🧠 **Powered by Google Gemini (Gemini 1.5 Flash)**  
  Uses Google's generative AI to analyze visual content.

- ⚡ **Streamlit Interface**  
  Lightweight and user-friendly for easy interaction.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Streamlit** – For building the web UI
- **Google Generative AI (Gemini API)** – For image understanding and content generation
- **Pillow (PIL)** – For image handling

---

## 🚀 Installation & Setup

### 📦 Prerequisites

- Python 3.7 or above
- Google API Key with Gemini access

### 🔧 Installation

```bash
git clone https://github.com/your-username/place-scene-detector.git
cd place-scene-detector
pip install streamlit google-generativeai pillow
```

Update your API key in `app.py`:
```python
os.environ["GOOGLE_API_KEY"] = "your-google-api-key"
```

---

## ▶️ Running the App

```bash
streamlit run app.py
```

Then open in your browser:  
`http://localhost:8501/`

---

## 🖼️ How It Works

1. Upload an image (e.g., of a university, public park, or landmark).
2. The app sends it to Google Gemini with a structured prompt.
3. Gemini analyzes the image and returns detailed information about the place or scenario.

---

## 📌 Future Improvements

- 🗺️ **Map Integration** – Show detected place on an interactive map.
- 🌐 **Multilingual Descriptions** – Return info in different languages.
- 📥 **Drag-and-Drop Upload or Camera Capture**
- 🧠 **Custom Fine-Tuning** – Improve accuracy on local/regional landmarks.

---

🚀 **See the world through AI—one image at a time.**
