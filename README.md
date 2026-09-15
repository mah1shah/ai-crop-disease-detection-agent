# 🌱 AgriSmart AI

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=28&pause=1200&center=true&vCenter=true&width=600&lines=Detect+early%2C+protect+fully+%F0%9F%8C%B1;AI-powered+crop+disease+detection;Your+digital+crop+health+assistant" alt="Typing Animation" />
</p>

<p align="center">

### 🚀 Live Demo

<a href="https://ai-crop-disease-detection-agent-feyn.onrender.com">
  <strong>Open AgriSmart AI</strong>
</a>

</p>

---

## 📖 About the Project

**AgriSmart AI** is an AI-powered web application designed to help farmers, gardeners, and agricultural users identify plant diseases from leaf images and receive practical crop-health recommendations.

The system combines **machine-learning-based image classification** with **context-based user inputs** to provide disease predictions, confidence scores, and actionable recommendations.

### How It Works

1. 📸 **Upload** a clear image of the affected plant or leaf.
2. 🌿 **Analyze** the image using the trained TensorFlow Lite model.
3. 📝 **Answer** follow-up questions about symptoms and environmental conditions.
4. 🤖 **Generate** an agricultural report using AI when available.
5. 🛡️ **Fallback support** ensures a report can still be displayed if the AI service is temporarily unavailable.

### Key Highlights

* 📸 **AI Image Recognition** for crop disease detection
* 🧠 **Machine Learning-Based Diagnosis**
* 📊 **Confidence Scores** for transparent predictions
* 🧭 **Interactive Agricultural Questionnaire**
* 💡 **Actionable Treatment Recommendations**
* 🌱 **Organic and Chemical Action Plans**
* 🌾 **Long-Term Crop Disease Prevention**
* 🌐 **Multilingual Support**
* 📱 **Responsive and Mobile-Friendly Interface**

---

## 🧑‍🌾 Step-by-Step Usage Guide

1. Open the **AgriSmart AI** web application.
2. Upload a clear image of the affected plant leaf.
3. Ensure the image is well-lit and focused.
4. Click **Analyze Image**.
5. Answer the follow-up questions about the plant and its environment.
6. Wait while the image classification model processes the image.
7. View the predicted disease and confidence score.
8. Review the recommended action plan and prevention strategies.

---

## 🧠 AI Architecture

AgriSmart AI uses multiple components to provide the complete experience:

```text
             🌿 Crop / Leaf Image
                     │
                     ▼
          TensorFlow Lite Model
                     │
                     ▼
             Disease Prediction
                     │
              ┌──────┴──────┐
              ▼             ▼
        User Context      Confidence
              │             │
              └──────┬──────┘
                     ▼
              AI Report Layer
                     │
             ┌───────┴───────┐
             ▼               ▼
       Gemini Available   Gemini Unavailable
             │               │
             ▼               ▼
       AI-Generated       Fallback
          Report           Report
```

### TensorFlow Lite Model

The trained model is stored as:

```text
crop_diagnosis_best_model.tflite
```

It performs the primary image-based disease classification.

### AI Report Generation

The predicted disease and questionnaire information are used to generate an agricultural report.

If the external AI service is unavailable or its quota is exhausted, the application uses a predefined fallback report so that the core application remains usable.

---

## 🗂 Project Structure

```text
📁 ai-crop-disease-detection-agent/
│
├── 📄 app.py
├── 📄 class_indices.json
├── 📄 crop_diagnosis_best_model.tflite
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 .gitattributes
├── 📄 .gitignore
│
├── 📁 static/
│   ├── 📁 css/
│   │   └── 📄 style.css
│   │
│   ├── 📁 images/
│   │   ├── 📄 apple_black-rot.JPG
│   │   ├── 📄 apple_cedar_rust.JPG
│   │   ├── 📄 apple_healthy.JPG
│   │   └── ... sample images
│   │
│   └── 📁 js/
│       ├── 📄 history.js
│       ├── 📄 main.js
│       ├── 📄 user_guide.js
│       ├── 📄 auth.js
│       └── 📄 emergency.js
│
└── 📁 templates/
    ├── 📄 history.html
    ├── 📄 index.html
    ├── 📄 tools.html
    └── 📄 user_guide.html
```

---

## ⚡ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/mah1shah/ai-crop-disease-detection-agent.git

cd ai-crop-disease-detection-agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

Set the required API/environment variables used by the application, including:

```text
GEMINI_API_KEY
```

Do **not** commit API keys or other secrets to GitHub.

### 4. Run the application

```bash
python app.py
```

### 5. Open the application

```text
http://127.0.0.1:5000
```

---

## 🚀 Live Deployment

The current deployed version of AgriSmart AI is available here:

**Live Demo:**
https://ai-crop-disease-detection-agent-feyn.onrender.com

**Source Code:**
https://github.com/mah1shah/ai-crop-disease-detection-agent

---

## 🤝 Contributing

Contributions and improvements are welcome.

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature-name
```

3. Make your changes.
4. Commit your changes.
5. Push your branch:

```bash
git push origin feature-name
```

6. Open a Pull Request.

Please review the project's contribution guidelines and code of conduct before contributing.

---

<p align="center">
  🌱 <strong>AgriSmart AI — Smarter Crop Health, Better Decisions</strong> 🌱
</p>
