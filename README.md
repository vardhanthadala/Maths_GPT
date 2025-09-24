# 📖 Text to Math Problem Solver and Data Search Assistant  

An interactive **Streamlit chatbot** that can:  
- 🧮 Solve **mathematical problems** using a calculator chain  
- 🔍 Search for information from **Wikipedia**  
- 🤔 Handle **logic & reasoning** with detailed step-by-step answers  
- ⚡ Powered by **Groq LLM (Gemma2-9b-It)**  

---

https://mathsgpt-solver.streamlit.app/

---

## 🚀 Features
- Streamlit chat interface  
- Uses **LangChain Tools**:
  - **Calculator** → solves math expressions  
  - **Wikipedia** → fetches real-world knowledge  
  - **Reasoning Tool** → provides structured step-by-step solutions  
- Remembers chat history within the session  

---

## 📂 Project Structure
```
📦 your-project/
 ┣ 📜 app.py          # Main Streamlit app
 ┣ 📜 README.md       # Documentation
 ┗ 📜 requirements.txt # Python dependencies
```

---

## ⚙️ Installation

1. **Clone this repo** (or copy the files into a folder):
   ```bash
   git clone https://github.com/your-username/math-bot.git
   cd math-bot
   ```

2. **Create virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## 📜 requirements.txt
Create a `requirements.txt` file with:
```txt
streamlit
langchain
langchain_groq
langchain_community
```

---

## 🔑 Setup API Key
- Get your **Groq API Key** from [https://console.groq.com/keys](https://console.groq.com/keys)  
- Paste it in the **Streamlit sidebar** when running the app.  

---

## ▶️ Run the App
```bash
streamlit run app.py
```

Then open the link in your browser (usually `http://localhost:8501`).

---

## 🧪 Example Usage
### Input:
```
I bought 3 packs of pencils. Each pack contains 12 pencils. 
I gave 7 pencils to my friend and then bought 15 more pencils. 
How many pencils do I have in total now?
```

### Output:
```
Step 1: 3 × 12 = 36
Step 2: 36 - 7 = 29
Step 3: 29 + 15 = 44

✅ Final Answer: 44 pencils
```


ist history across sessions  
- Enhance UI with **chat avatars**  
