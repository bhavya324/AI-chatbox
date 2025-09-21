
# 🤖 AI Chatbot (Jupyter Notebook)

A simple AI-powered chatbot built using [Hugging Face Transformers](https://huggingface.co/transformers/) and [DialoGPT-medium](https://huggingface.co/microsoft/DialoGPT-medium).  
This chatbot can hold interactive conversations directly inside a Jupyter Notebook.  

---

## 📌 Features
- Runs inside Jupyter Notebook 📓
- Uses `microsoft/DialoGPT-medium` conversational model
- Interactive text-based chat
- Lightweight and easy to use

---

## 🚀 Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/your-username/ai-chatbot.git
cd ai-chatbot
pip install -r requirements.txt
```
## 🛠 Requirements

- Python 3.8+
- PyTorch
- Transformers (Hugging Face)

Install them manually if needed:
```bash
pip install torch transformers
```
## ▶️ Usage

Run Jupyter Notebook:
```bash
jupyter notebook
```
Open the notebook and run the chatbot code cell.
Then start chatting:
```bash
AI Chatbot is ready! Type 'quit' to stop.

You: Hello  
Chatbot: Hi there! How are you doing?  

You: quit  
Chatbot: Goodbye! 👋
```
## 📚 Future Improvements

- Add a web UI using Streamlit or Gradio

- Support for multilingual chats

- Save conversation history
