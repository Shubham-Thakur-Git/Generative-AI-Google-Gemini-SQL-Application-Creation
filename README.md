## Generative AI Google Gemini SQL Application Creation

### Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Getting Started](#getting_started)
4. [Usage](#usage)
5. [License](#license)

---

### Overview
This project demonstrates the integration of Google Gemini's generative AI capabilities with SQL-based applications. 
The goal is to create intelligent, data-driven applications that can process natural language queries, generate SQL code dynamically, and produce actionable insights.


### Features
1. Natural Language to SQL: Converts user queries into SQL commands.
2. Interactive SQL Queries: Dynamically generates and executes SQL queries on databases.
3. Customizable Workflows: Tailor AI prompts to specific datasets and queries.



### Getting Started
1. Install Dependencies:
   google.generativeai : for using generativeai prompt model (gemini-1.5-flash)
   db-sqlite3          : allows you to interact with SQLite databases using SQL queries
   streamlit           : for building and sharing data-driven web applications
   localtunel          : Node.js package that allows you to expose a locally running web server (on your local machine) to the internet.
                         It creates a secure tunnel between your local development environment and the web by assigning a temporary, public URL to your local web application.
2. Configure Database (Here we worked with sqlite)
3. Run the Application : Execute python main.py to start the app. You can now input natural language queries that will be converted to SQL commands.


### Usage
Input natural language questions like : "Show me the total no of employees"
The AI will generate a corresponding SQL query, execute it, and display results.


### License
This project is licensed under the [MIT License](LICENSE).
