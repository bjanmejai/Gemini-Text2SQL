![Gemini Text2SQL Logo](images/gemini_text2sql_logo.png)


# Gemini-Text2SQL

# Gemini Text2SQL

Gemini Text2SQL is an AI-powered tool that converts natural language questions into precise SQL queries using Google’s Gemini large language model.  
Designed for ecommerce and other databases, it enables users to effortlessly generate accurate SQL queries without writing any SQL code.

## Features

- Leverages Google Gemini AI to translate English questions into SQL SELECT queries.
- Supports complex queries based on your database schema.
- Safe and read-only: generates queries without executing them.
- Easy to use in Python scripts or interactive notebooks.
- Perfect for ecommerce databases and adaptable to star schema data warehouses.

## Getting Started

### Prerequisites

- Python 3.8+
- Google Gemini API key (get it from [Google AI Studio](https://aistudio.google.com/app/apikey))
- Install required Python package:


### Usage

1. Replace `"YOUR_GEMINI_API_KEY"` in the script with your actual API key.
2. Update the `TABLE_SCHEMA` variable to match your database schema.
3. Run the Python script and enter your natural language questions.
4. Copy the generated SQL queries and run them on your database.

Example:

sql_query = generate_sql_from_text("What is the total revenue by city for 2024?")
print(sql_query)


## How It Works

The app sends your question plus the database schema as a prompt to Google Gemini’s text generation API. Gemini returns a well-structured SQL query matching your question and schema.

## License

This project is licensed under the MIT License.

---

*Made with ❤️ using Google Gemini API and Python.*
