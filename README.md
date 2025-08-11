# 📝 Text-to-SQL LLM App with SQL Database Querying using Gemini Pro

![Gemini Pro](https://img.shields.io/badge/Gemini_Pro-LLM-purple)
![Python](https://img.shields.io/badge/Python-3.8%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)

End-to-End solution for natural language database querying: Convert plain English questions to SQL queries and execute them on an SQL database, powered by **Google Gemini Pro** LLM.

> 📁 **Repository**: `GENAI-project7-Text-to-SQL-LLM-App-along-with-Quering-SQL-database-using-Gemini-Pro`

---

## 🚀 Project Highlights

- 🔄 **Text-to-SQL Conversion**: Use LLM to generate SQL queries from user input
- 🗄️ **Query Execution**: Run generated SQL directly on SQLite databases
- 🤖 **Gemini Pro Integration**: Harness cutting-edge LLM for accurate SQL translation
- 🛠️ **Modular Design**: Easily extend to other databases or use-cases
- ⚡ **Fast Prototyping**: Ready for real-time and batch querying

---

## 🧠 Technical Stack

### 🤖 AI & Utilities
![Gemini Pro](https://img.shields.io/badge/Gemini_Pro-LLM-purple)
![sqlite3](https://img.shields.io/badge/SQLite-3.0+-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-yellow)

### 🛠️ Python Ecosystem
![Python](https://img.shields.io/badge/Python-3.8%2B-brightgreen)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110+-green)

---

## 🏗️ Project Structure

```bash
GENAI-project7-Text-to-SQL-LLM-App-along-with-Quering-SQL-database-using-Gemini-Pro/
├── sql.py                  # Main text-to-SQL logic and query execution
├── sqlite.py               # SQLite database handler
├── sqlite copy.py          # (Optional) SQLite backup/alternative handler
├── requirements.txt        # Python dependencies
├── LICENSE                 # MIT License
├── README.md               # Project documentation
└── .gitignore              # Git ignore rules
```

---

## ⚡ Installation & Usage

```bash
# Clone repository
git clone https://github.com/mdzaheerjk/GENAI-project7-Text-to-SQL-LLM-App-along-with-Quering-SQL-database-using-Gemini-Pro.git
cd GENAI-project7-Text-to-SQL-LLM-App-along-with-Quering-SQL-database-using-Gemini-Pro

# Install dependencies
pip install -r requirements.txt

# Run main Text-to-SQL logic
python sql.py
```

---

## 📊 Example Use Cases

- **Natural Language Database Querying:** "Show me all employees who joined after 2022."
- **Dynamic SQL Generation:** "Get the average sales for the last quarter."
- **Database Insights:** "List customers from New York with orders above $500."

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

#### Key Features:
1. Translate plain English to SQL using Gemini Pro LLM
2. Execute generated SQL queries on SQLite database
3. Modular codebase for easy extension and customization
4. Simple installation and usage for rapid prototyping
