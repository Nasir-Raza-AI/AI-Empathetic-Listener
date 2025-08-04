# 🫂 Empathetic Support Chatbot (LLM Fine-Tuned on EmpatheticDialogues)

A gentle and emotionally supportive chatbot fine-tuned on the **EmpatheticDialogues** dataset using **DistilGPT2**. This AI chatbot provides empathetic responses to stress, anxiety, and emotional wellness queries, ensuring a safe and comforting user experience.

> **Disclaimer:** This chatbot is for **supportive conversations only** and **does not provide medical or psychological advice**. Always consult a professional for mental health support.

---

## 🚀 Features
- Fine-tuned **DistilGPT2** using real empathetic dialogues.
- Understands emotionally charged queries and responds gently.
- Built with **Hugging Face Transformers Trainer API**.
- Clean and simple **Streamlit Web App Interface**.
- Safety filters and ethical design considerations.

---

## 🧰 Tech Stack
- Python 3.x 🐍
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/)
- [Hugging Face Datasets](https://huggingface.co/datasets)
- Streamlit (for Web UI)
- Pre-trained Model: **DistilGPT2** (can also use Mistral-7B)
- Dataset: **EmpatheticDialogues (Facebook AI)**

---

## 🗂 Folder Structure
EmpathyChatbot/
├── train_empathy_model.py # Fine-tuning script
├── empathy_chatbot_app.py # Streamlit Web Interface
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 📥 Installation
git clone https://github.com/Nasir-Raza-AI/AI-Empathetic-Listener.git
cd AI-Empathetic-Listener
pip install -r requirements.txt

**🔑 Setting Up**
No dataset download needed! The EmpatheticDialogues dataset will be loaded automatically using Hugging Face’s datasets library.

**🏋️‍♂️ Fine-Tuning the Model**

python train_empathy_model.py
This script will:

Load DistilGPT2

Format the dataset into “Context: ... Response: ...”

Fine-tune for empathetic conversations

Save the model to /empathy_model/

---

**🖥️ Running the Web App**

streamlit run empathy_chatbot_app.py
💬 Example Usage
vbnet
Copy code
You: I feel anxious about my exams.
Bot: I'm really sorry you're feeling that way. It's completely normal to feel anxious before big exams. You've got this!

---

**⚠️ Ethical & Safety Notice**
The chatbot is designed to provide supportive and empathetic conversation.

It is NOT a therapist and does not provide diagnoses or treatment.

Always consult a licensed professional for serious mental health issues.

---

**📄 License**
This project is licensed under the MIT License.

---

**🤝 Contributions**
Feel free to Fork & PR if you'd like to:

Integrate larger models (Mistral-7B, LLaMA)

Add emotion classification

Improve UI (chat history, sentiment-aware tone)

