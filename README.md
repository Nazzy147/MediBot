# 🩺 MediBot – Your AI-Powered Health Buddy

MediBot is an **AI-driven medical assistance system** designed to provide quick, reliable, and context-aware health guidance through natural conversations.
It helps users understand their symptoms, identifies urgency, and advises whether professional care is needed — all within seconds.

> ✅ *A smarter way to triage symptoms before visiting a doctor.*

---

## 🚀 Why MediBot?

Traditional health assistants and search engines provide generic answers with no sense of urgency, context, or personalization.
MediBot fixes that by combining **NLP, severity assessment, timeline-based analysis, and multilingual support** to deliver medically contextual responses.

---

## 🔥 Key Highlights

* 💬 **Interactive Medical Chatbot**
* 🤖 **Intent Classification**
* ⚠️ **Emergency & Severity Detection**
* 🕒 **Timeline-Aware Symptom Interpretation**
* 🌐 **Multilingual Assistance**
* 📚 **Rule-based Medical Knowledge Base**
* 🧠 **Neural Model-Driven Reasoning**
* 🌙 **Real-time Health Suggestions**
* 🎛️ **Clean Gradio Interface**
* ✅ **~95.96% Accuracy in Intent Prediction**

---

## 🧠 Core Features

### ✅ Intelligent Symptom Understanding

Understands user queries using NLP and maps them to relevant medical categories.

### ✅ Severity-Based Triage

Categorizes conditions as *mild / moderate / severe* and highlights emergency cases.

### ✅ Timeline Extraction

Analyzes symptom duration to provide appropriate recommendations.

### ✅ Multilingual Support

Breaks language barriers to make health accessibility inclusive.

### ✅ Modular Components

* **SeverityChecker**
* **SymptomTracker**
* **InteractiveAssessment**
  (All work together to provide targeted medical help.)

---

## 🏗️ System Workflow

1. User describes symptoms
2. MediBot interprets text using NLP
3. Model identifies intent & medical category
4. Timeline + severity evaluation
5. Suggestions provided (self-care / medical visit / emergency)

---

## 🧩 Tech Stack

| Component     | Technology                             |
| ------------- | -------------------------------------- |
| Front-end UI  | **Gradio**                             |
| Backend Logic | **Python**                             |
| NLP           | **NLTK**                               |
| ML Model      | **Deep Neural Network (3-layer)**      |
| Optimizer     | **RMSprop**                            |
| Data Handling | **Custom knowledge base (rule-based)** |

---

## 📊 Performance

* **Intent Classification Accuracy:** ~95.96%
* **Response Time:** < 2 seconds
* Supports **20+ Medical Categories** and **300+ Symptom Patterns**

---

## ✅ What Makes MediBot Special?

* Goes **beyond symptom lookup**
* Detects **severity & emergency conditions**
* Understands **how long symptoms have persisted**
* Communicates in **different languages**
* Gives **actionable suggestions** instead of generic responses

> MediBot bridges the gap between online health information and preliminary medical triage — **safe, fast, and accessible.**

---

## 💡 Applications

* Early-stage medical screening
* Public health awareness
* Remote / rural health assistance
* First-level triage before seeking care

---

## 🧭 Future Scope

* Expanded disease coverage
* Integration with wearable data
* Voice-based interaction
* Prescription & appointment routing

---

## 👥 Developer

Created during an **AI/ML internship**, focusing on building practical, socially impactful AI solutions.

---

# ⚙️ Installation

Follow these steps to run MediBot locally:

```bash
# Clone this repository
git clone https://github.com/your-username/MediBot.git
cd MediBot

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
```

---

# ▶️ Usage

Run the MediBot application:

```bash
python app.py
```

This will launch the **Gradio interface** in your browser.
You can start chatting immediately by describing your symptoms.

> Example queries:
> • “I have chest pain since yesterday”
> • “I feel feverish for 3 days”
> • “My stomach hurts a little”

---

# 🖼️ Demo

### 🔹 UI Preview

> <img width="891" height="608" alt="image" src="https://github.com/user-attachments/assets/a042e4f3-1b10-4b2d-b15b-2ba8bec7ae2b" />
> <img width="886" height="602" alt="image" src="https://github.com/user-attachments/assets/dfaeaee4-3504-422c-8aeb-705d36a35ad5" />
> <img width="888" height="654" alt="image" src="https://github.com/user-attachments/assets/81b0d664-e6fb-4d03-913e-353a7be5d136" />
> <img width="882" height="648" alt="image" src="https://github.com/user-attachments/assets/cfdb85a7-0ad2-472c-84d2-760ebea6dd7d" />
> <img width="940" height="635" alt="image" src="https://github.com/user-attachments/assets/639e940c-dad9-4457-8b56-ed707ccbc7bd" />
> <img width="940" height="643" alt="image" src="https://github.com/user-attachments/assets/4df69f64-bb84-4065-b2f8-84c5fa3a1b56" />

---

# ✅ Example Output

```
User: I have chest pain and short breath
MediBot: This may be serious. Please seek emergency care immediately.
```

```
User: Mild throat pain for 2 days
MediBot: Likely mild. Stay hydrated, rest, and monitor symptoms.
```

---

## 🔄 Stopping the App

```
Press `CTRL + C` in terminal
```
OR
```
Just say "Bye" to the chatbot
```

---


