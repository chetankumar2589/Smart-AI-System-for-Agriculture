# 🌱 Smart-AI-System-for-Agriculture using CrewAI + Groq

A smart agricultural support system that not only **detects plant diseases from leaf images** but also **analyzes infection severity** and **recommends remedies** intelligently using **CrewAI Agents** and **Groq LLM**.
# LinkedIn Link:
https://www.linkedin.com/posts/chetan-kumar-patruni_crewai-aiagents-groq-activity-7323279775538499584-UFhm?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD4_SUQBBYHcCbB8fGJDReojMInn5E4i0Ew

---

## 🚀 Project Overview

This system integrates **Computer Vision + AI Agents** to assist farmers and agricultural researchers:

| Stage | What Happens | Tech Used |
|------|-------------|-----------|
| 🔍 Disease Detection | CNN model identifies plant disease from leaf image | Custom Trained CNN |
| 🧮 Severity Calculation | OpenCV calculates infection percentage on the leaf | OpenCV |
| 🧠 AI Reasoning | CrewAI agent interprets disease + severity to decide severity label | CrewAI + Groq LLM |
| 💡 Remedy Advice | AI generates the best treatment suggestion | Groq Cloud API |

---

## 🧠 Key Features

- Detects disease type from input image  
- Calculates % leaf damage  
- Classifies severity: **Mild / Moderate / Severe**  
- Provides **clear & practical remedy recommendations**  
- Workflow orchestrated by **CrewAI Agents** collaborating intelligently  
- Ultra-fast inference powered by **Groq LLM**  

---

## 🗂 Notebook Workflows

| Notebook | Purpose | Link |
|---------|---------|------|
| **1. Plant Disease Detection (CNN + Severity Estimation)** | Loads model, predicts disease + measures infection area | [Colab Notebook](https://colab.research.google.com/drive/1t88ltpmWro8iRUUzIBJT-giw3sqJbuHe?usp=sharing) |
| **2. Disease Remedy AI Agent (CrewAI + Groq)** | Takes disease + severity → outputs label + remedy | [Colab Notebook](https://colab.research.google.com/drive/1OjCcHZYML18zNdTjuHglMs2-TtGpTDkh?usp=sharing) |

---

## 🏗 Tech Stack

- **Python**
- **TensorFlow / Keras** (CNN Model)
- **OpenCV** (Leaf infection analysis)
- **CrewAI** (Agent collaboration framework)
- **Groq Cloud API** (LLM intelligence layer)
- **Google Colab** (Runtime environment)

---

## 🖼 System Flow

Leaf Image → CNN Model → Disease Name
↓
OpenCV Severity %
↓
CrewAI Agent Pipeline
↓
Severity Label + Best Remedy Recommendation


---

## 📦 How to Use Locally

```bash
git clone <this-repo-url>
cd Smart-AI-System-for-Agriculture

# Install dependencies
run these codes in colab , cell by cell

# Add your Groq API Key to environment:
GROQ_API_KEY="your-key-here"

Run the workflow inside the notebooks.
```

### 💡 Future Enhancements

Voice-based farmer interaction assistant

Real-time mobile camera disease analysis

Multi-crop knowledge base expansion

Offline edge-device deployment


