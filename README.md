# Text to SQL Chatbot

Welcome to the **Text to SQL Chatbot** project!  
This system bridges the gap between non-technical users and databases by allowing natural language questions to be automatically converted into SQL queries.

## 📚 Table of Contents
- 📖 Project Overview  
- 🔧 Features  
- 🛠️ Installation  
- 🚀 Usage  
- 🗼 Architecture  
- 📊 Evaluation  
- 📝 Future Work  
- 📄 License  

## 📖 Project Overview

In many organizations, accessing SQL database information requires technical knowledge.  
This chatbot enables team members to retrieve data by simply asking questions in **plain English**, without writing SQL.

The system:  
- Understands user queries  
- Converts them into SQL  
- Executes the query on a MySQL database  
- Returns results in a clean, readable format  

This approach is applicable across industries like healthcare, retail, finance, and more.

## 🔧 Features

- Natural Language Processing → Converts user queries into SQL  
- Database Interaction → Connects to a MySQL database to fetch data  
- User-Friendly Output → Returns structured, readable responses  
- End-to-End Flow → From data ingestion to query execution  
- LLM-Powered → Uses a Large Language Model to generate accurate SQL  

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/shekyo/Text-to-SQL-Chatbot.git
cd Text-to-SQL-Chatbot
```

### 2. Set Up MySQL
- Create a MySQL database  
- Create tables as specified  
- Load Excel sheet data into MySQL  

### 3. Configure API Keys
Make sure you add your LLM API keys (Google Gemini, OpenAI, etc.).

## 🚀 Usage

1. Run the backend or notebook.  
2. Ask questions in plain English:
   - "List all customers from California"
   - "Show total revenue by department"
3. The chatbot:
   - Converts → SQL  
   - Executes → MySQL  
   - Returns → Clean natural language response  

## 🗼 Architecture

```
User Query 
   ↓
LLM Chain (NL → SQL) 
   ↓
MySQL Database 
   ↓
Output Parser 
   ↓
Final Answer
```

- Database: MySQL  
- LLM Chain: Converts natural language → SQL  
- Output Parser: Formats SQL results  
- Data Source: Excel → MySQL  

## 📊 Evaluation

- **Accuracy**: Correct SQL generated  
- **Response Time**: Speed of full pipeline  
- **User Feedback**: Quality and clarity of answers  

## 📝 Future Work

- Support multiple LLMs  
- Add Flask/Streamlit UI  
- Deploy to cloud  
- Improve SQL accuracy using schema-aware models  

