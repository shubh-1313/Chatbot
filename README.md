# 🤖 Simple Chatbot in Python

A basic rule-based chatbot built using Python. It responds to user inputs with predefined replies and keeps the conversation going until the user exits.

---

## 🚀 Features

- Interactive command-line chatbot
- Responds to common inputs like:
  - "hello"
  - "how are you"
  - "name"
  - "bye"
- Randomized responses for variety
- Handles unknown inputs with default replies
- Runs in an infinite loop until user exits

---

## 🛠️ How It Works

- The chatbot uses a dictionary of predefined responses
- It checks if user input contains certain keywords
- If a match is found → gives a random response
- If no match → gives a default reply

---

## 📦 Requirements

- Python 3.x  
- No external libraries required (uses built-in `random` module)

---

## ▶️ How to Run

1. Save the file as:
   ```
   Chatbott.py
   ```

2. Run the program:
   ```
   python Chatbott.py
   ```

3. Start chatting:
   ```
   You: hello
   🤖 Chatbot: Hi there!
   ```

4. Type `exit` to stop the chatbot

---

## 💡 Example Conversation

```
🤖 Chatbot: Hello! Type 'exit' to quit.

You: hello
🤖 Chatbot: Hey! How can I help you?

You: how are you
🤖 Chatbot: Doing great!

You: what is your name
🤖 Chatbot: I am your chatbot!

You: bye
🤖 Chatbot: See you later!

You: exit
🤖 Chatbot: Goodbye!
```

---

## 🧠 What You Learn

- Python dictionaries
- Loops (`while`)
- Conditional statements (`if-else`)
- String handling
- Random module usage

---

## 🔮 Future Improvements

- Add more advanced conversations
- Use NLP (Natural Language Processing)
- Convert into GUI (Tkinter)
- Build a web chatbot (Flask / Streamlit)
- Integrate AI models

---

## ⚡ Key Takeaways

- This is a **rule-based chatbot**
- Not AI-based, but great for beginners
- Helps build logic and Python fundamentals

---

## 📌 Note

This chatbot works on keyword matching, so it may not understand complex sentences. Expand the `responses` dictionary to improve it!
