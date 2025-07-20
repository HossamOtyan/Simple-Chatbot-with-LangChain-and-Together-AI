# Simple Chatbot with LangChain and Together AI

A simple conversational AI chatbot using LangChain, DeepSeek-V3 model, and memory to maintain context.

## 📋 Description

This project demonstrates how to build a simple chatbot that can maintain conversation history and provide coherent, context-aware replies.

It uses:
- **LangChain** framework for chaining prompts and managing memory.
- **Together AI DeepSeek-V3 model** as the underlying LLM.
- **ConversationBufferMemory** to store and pass previous messages for contextual conversations.

## 🚀 Features

- Maintains full conversation history in memory.
- Uses a prompt template to guide the LLM for natural and helpful responses.
- Simple Python CLI interface (`input()` loop) for interaction.
- Environment variable-based API key loading using `dotenv`.

## 🛠️ Technologies Used

- Python 3
- LangChain
- Together AI (`deepseek-ai/DeepSeek-V3` model)
- dotenv for managing API keys securely

## 📦 Notes

- API key must be stored in an `.env` file with the variable name `API_KEY`.
- This is a minimal CLI-based chatbot for experimentation and learning purposes.

## 📄 License

Free to use for educational and experimentation purposes.

