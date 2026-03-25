# Chatbot with Conversation History using LangChain 🤖💬

*A beginner-friendly guide to building intelligent chatbots that remember conversations*

## 🎯 What is this project?

This project is perfect for **beginners** who want to learn how to build chatbots that can:
- Remember previous conversations 🧠
- Maintain context across multiple messages 📝
- Handle different chat sessions separately 🔄
- Respond in different languages 🌍
- Manage conversation length efficiently ⚡

## 🚀 What you'll learn

By exploring this project, you'll understand:

1. **Basic Chatbot Setup** - How to connect to AI models using LangChain
2. **Conversation Memory** - How to make chatbots remember what was said before
3. **Session Management** - How to handle multiple users or conversation threads
4. **Prompt Engineering** - How to give your chatbot personality and instructions
5. **Message Trimming** - How to manage long conversations efficiently

## 🛠️ Technologies Used

- **LangChain** - Framework for building AI applications
- **Groq API** - Fast AI model inference (using Llama 3.1)
- **Python** - Programming language
- **Jupyter Notebook** - Interactive development environment
- **python-dotenv** - Environment variable management

## 📋 Prerequisites

Before you start, make sure you have:
- Basic knowledge of Python 🐍
- A Groq API key (free at [groq.com](https://groq.com))
- Python 3.8+ installed on your computer

## 🔧 Setup Instructions

### 1. Clone or Download this Project
```bash
git clone https://github.com/Shashannk-22/Chatbot_with_conversation_history_using_Langchain.git
cd Chatbot_with_conversation_history_using_Langchain
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv chatbot_venv
source chatbot_venv/bin/activate  # On Windows: chatbot_venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up Environment Variables
Create a `.env` file in the project root:
```
GROQ_API_KEY=your_groq_api_key_here
```

### 5. Open the Notebook
```bash
jupyter notebook chatbot.ipynb
```

## 📚 Project Structure

```
├── chatbot.ipynb          # Main tutorial notebook with step-by-step examples
├── requirements.txt       # All required Python packages
├── README.md             # This file
├── chatbot_venv/         # Virtual environment (created after setup)
└── .env                  # Your API keys (create this file)
```

## 🎓 Learning Path

The notebook is organized in progressive steps:

### Step 1: Basic Chat (Cells 1-4)
- Learn how to set up a simple chatbot
- Understand API integration
- See how basic conversations work

### Step 2: Adding Memory (Cells 5-8)
- Discover how to add conversation history
- Learn about session management
- Test memory with different conversations

### Step 3: Multiple Sessions (Cells 9-11)
- Understand how to handle multiple users
- Learn session isolation
- Practice with different chat sessions

### Step 4: Custom Prompts (Cells 12-17)
- Learn prompt engineering
- Add system instructions
- Handle multiple languages

### Step 5: Advanced Features (Cells 18-23)
- Implement conversation trimming
- Manage long conversations
- Optimize for performance

## 🎯 Key Concepts Explained

### 💭 **Conversation Memory**
The chatbot remembers what you said earlier in the conversation, just like talking to a real person.

### 🔄 **Session Management**
Different users or conversation threads are kept separate, so the chatbot doesn't mix up conversations.

### ✂️ **Message Trimming**
When conversations get too long, the chatbot intelligently keeps the most important parts to stay efficient.

### 🌍 **Multi-language Support**
The chatbot can respond in different languages based on your preferences.


## 🔍 Common Use Cases

This chatbot pattern is perfect for:
- Customer support systems
- Personal AI assistants
- Educational tutoring bots
- Interactive documentation
- Multi-user applications
