# 🧠 Self-Learning Chatbot in Python

A simple chatbot that **learns from user interactions** and stores knowledge in a JSON file.  
Every time you teach it something new, it remembers for future conversations.  

---

## ✨ Features
- Loads knowledge base from `knowledge_base.json`
- Finds best matches using `difflib.get_close_matches`
- Learns from user input when it doesn’t know the answer
- Saves new Q&A pairs permanently into the JSON file
- Lightweight, no external dependencies except Python standard library

---

## 🚀 How It Works
1. Run the chatbot:
   ```bash
   python bot.py
  
    2. Chat with it: 
    You: Hey!
    Bot: I dont know the answer. Can you teach me?
    Type the answer or 'skip' to skip: Hello, How are you?
    Bot: Thank You! I learned a new thing :)
    
    3. Next time:
    You: Hey!
    Bot: Hello, How are you?
   
🛠 Future Improvements
	
🌐 Add NLP/embeddings for better semantic understanding

📊 Use a vector database (FAISS, Pinecone, Weaviate) for scalable memory

🎨 Create a simple UI with Flask/Streamlit

💬 Integrate with messaging apps (WhatsApp, Telegram, Slack)

📸 Example Run

![Chatbot Screenshot](Screenshot%202025-08-22%20at%209.50.58 PM.png)

