Got it! Here's the updated `README.md` for your [AI-Chatbot](https://github.com/Thorfinn05/AI-Chatbot) repository using individual `pip install` commands instead of `requirements.txt`:

---

# 🧠 AI-Chatbot

A terminal-based chatbot powered by **LangChain** and **Google Gemini 1.5 Flash**, built to answer any question you throw at it in real time. Perfect as a minimal and extendable starting point for building your own AI assistant.

---

## 🚀 Features

- ⚡ Uses Gemini 1.5 Flash model via `langchain_google_genai`
- 🔐 API key management with `.env`
- 🛠️ Custom prompt design using `PromptTemplate`
- 🔁 Continuous Q&A loop with graceful exit
- 💬 Simple, clean code – easy to modify and expand

---

## 📁 Project Structure

```bash
.
├── main.py          # Main script to run the chatbot
├── .env             # Stores your Google API key
└── README.md        # Project documentation
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Thorfinn05/AI-Chatbot.git
cd AI-Chatbot
```

### 2. Create and Activate a Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install langchain
pip install langchain-google-genai
pip install python-dotenv
```

### 4. Set Up Your API Key

Create a `.env` file in the project directory and paste your [Google API Key](https://aistudio.google.com/app/apikey):

```
GOOGLE_API_KEY=your_google_api_key_here
```

---

## 🧪 Run the Chatbot

```bash
python main.py
```

You'll be prompted with:

```
Ask a question
Question:
```

Type your question and hit Enter. To exit, simply type `quit`.

---

## 🔒 Security Note

Make sure your `.env` file is listed in `.gitignore` to avoid accidentally uploading your API key.

Example `.gitignore`:
```
.env
```

---

## 🧩 Tech Stack

- [`LangChain`](https://github.com/langchain-ai/langchain)
- [`langchain-google-genai`](https://pypi.org/project/langchain-google-genai/)
- [`python-dotenv`](https://github.com/theskumar/python-dotenv)

---

## 📜 License

Licensed under the [MIT License](LICENSE)

---

## 💡 Future Improvements (Suggestions)

- Add memory so the chatbot remembers context
- Integrate into a web or mobile UI
- Support for voice input/output
- Logging or saving conversations

---

## ⭐ Support

If you found this helpful, consider giving the repo a ⭐ to show your support!

---

Let me know if you'd like me to generate a logo, banner, or deployment guide for a web version!
