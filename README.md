# Query Wizard 3.0

**Query Wizard 3.0** is an AI-powered, multilingual SQL query generator and executor that transforms natural language (text or voice) into executable SQL queries. Built with Streamlit, it offers an intuitive interface for users to interact with databases without writing complex SQL, making data access more inclusive and efficient.

![Query Wizard Logo](logo.png)

---

## 🚀 Features

- **Natural Language to SQL**: Convert plain English (or other supported languages) into accurate SQL queries using AI.
- **Voice Input Support**: Speak your queries—ideal for accessibility and hands-free environments.
- **Live SQL Execution**: Run generated queries directly on your database and view results instantly.
- **Schema Preview**: Visualize database tables and column structures for better context.
- **Multi-Language Support**: Interact in various languages, breaking down language barriers in data querying.
- **User Authentication**: Secure login system to manage user access.
- **Modular Architecture**: Easily extendable components for future enhancements.

---

## 💠 Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/) – Interactive UI for seamless user experience.
- **Backend**:
  - **AI Model**: Google Gemini AI for natural language processing.
  - **Database**: SQLite3 for managing and executing SQL queries.
  - **Voice Recognition**: [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) library for converting speech to text.
  - **Language Translation**: [Deep Translator](https://pypi.org/project/deep-translator/) for multi-language support.

---

## 📂 Project Structure

```
Query_Wizard_3.0/
├── __pycache__/              # Compiled bytecode files
├── ai_generator.py           # Handles AI-based SQL generation
├── db_config.py              # Database configuration settings
├── db_handler.py             # Functions for database connections and query execution
├── login.py                  # User authentication logic
├── logo.png                  # Application logo
├── main.py                   # Main application script
├── mysql_schema.json         # Sample MySQL schema for reference
├── prompt.py                 # Prompt templates for AI model
├── query_parser.py           # Parses and validates generated SQL queries
├── requirements.txt          # Python dependencies
├── schema_handler.py         # Manages database schema retrieval and display
└── README.md                 # Project documentation
```

---

## ⚙️ Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Rishivarshney100/Query_Wizard_3.0.git
   cd Query_Wizard_3.0
   ```

2. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**

   ```bash
   streamlit run main.py
   ```

---

## 🔐 Configuration

- **Database Settings**: Update `db_config.py` with your database credentials and connection details.
- **AI Model API Key**: Ensure you have access to the Google Gemini AI API and set the necessary keys in `ai_generator.py`.
- **Language Support**: Modify `deep_translator` settings in `main.py` to add or change supported languages.

---

## 🧪 Usage

1. **Login**: Start the application and log in with your credentials.
2. **Select Database**: Choose the database you want to interact with.
3. **Input Query**:
   - **Text**: Type your query in natural language.
   - **Voice**: Click on the microphone icon and speak your query.
4. **Generate SQL**: The AI model will convert your input into an SQL query.
5. **Execute Query**: Run the generated SQL and view the results directly in the app.

---

## 🚧 Future Enhancements

- Support for cloud databases (e.g., PostgreSQL, MongoDB, AWS RDS)
- OAuth 2.0 authentication for enterprise-level security
- Query history and version control
- Advanced data visualization for query results
- Integration with business intelligence dashboards

---

## 👤 Authors

- **Rishi Varshney**  
  [LinkedIn](https://www.linkedin.com/in/rishi-varshney100/) | [LeetCode](https://leetcode.com/u/Rishi_varshney/)  
  Email: csai22150@glbitm.ac.in

- **Tushar Ranjan**  
  [LinkedIn](https://www.linkedin.com/in/tushar-ranjan-4186a8179/) | [LeetCode](https://leetcode.com/u/tushar_ranjan/)  
  Email: csaiml22150@glbitm.ac.in

---

## 📊 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

Special thanks to the mentors and contributors at G. L. Bajaj Institute of Technology and Management for supporting this initiative.

---

> 📄 *Query Wizard 3.0 is built to make data interaction as natural as a conversation.*
