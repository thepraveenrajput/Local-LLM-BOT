# 🤖 Local AI Chatbot using Ollama + Streamlit

This guide will help you install Python, Ollama, required libraries, and run your local AI chatbot.

---

# 📋 Requirements

- Python 3.8 or higher
- Ollama installed
- Internet connection (only for first model download)

---

# ⚙️ Step 1: Install Python

Download Python from:  
https://www.python.org/downloads/

Verify installation:

 ```bash
 python --version
 ```
# ⚙️ Step 2: Install Ollama
# ⚙️ Step 3: Download AI Model
- Pull the Qwen 2.5 model:
  
```bash
  ollama pull qwen2.5:0.5b
```
# ⚙️ Step 4: Install Required Libraries
  ```bash
  pip3 install streamlit ollama
  ```
# ⚙️ Step 5: Run the Chatbot
Make sure you are inside your project folder.
 ```bash
 streamlit run bot.py
 ```
# 🌐 Output
Open your browser and go to:
```bash
http://localhost:8501
```
# Your chatbot will be running locally.
<img width="1469" height="840" alt="Screenshot 2026-02-15 at 09 48 40" src="https://github.com/user-attachments/assets/d7d60eb4-6efa-46e3-896d-f57777951853" />





``` bash
project-folder/
│
├── bot.py
├── README.md
└── requirements.txt 
```

``` bash
pip install -r requirements.txt
```



