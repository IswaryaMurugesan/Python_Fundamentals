# 🎫 Customer Support Ticket Analyser

## 📌 Project Overview

The **Customer Support Ticket Analyser** is a Python-based project developed to analyze customer support tickets, clean textual data, and generate meaningful insights. The project demonstrates the use of Python fundamentals, including dictionaries, lists, loops, conditional statements, functions, string manipulation, and sets.

---

## 🎯 Objectives

* Display customer support tickets in a readable format.
* Add new customer tickets dynamically.
* Validate user inputs for ticket priority.
* Clean and standardize issue descriptions.
* Analyze ticket descriptions based on keywords.
* Generate summary statistics and business insights.

---

## 🛠️ Technologies Used

* Python 3
* Google Colab 

---

## 📂 Dataset

The project uses a **preloaded dictionary of lists** containing customer support ticket information, including:

* Ticket Number
* Customer Name
* Issue Description
* Priority Level

Users can also add new tickets during program execution.

---

## ✨ Features

### ✅ Display Ticket Information

* Prints all customer tickets in a well-formatted structure.

### ✅ Add New Tickets

* Accepts user input for:

  * Customer Name
  * Issue Description
  * Priority (High/Medium/Low)
* Automatically generates the next ticket number.
* Validates priority input.

### ✅ Data Cleaning

Issue descriptions are cleaned by:

* Removing leading and trailing spaces
* Converting text to lowercase
* Removing punctuation marks
* Replacing multiple spaces with a single space
* Standardizing text for analysis

### ✅ Keyword-Based Analysis

A reusable Python function performs a **case-insensitive** search to count the number of ticket descriptions containing specific keywords such as:

* Poor
* Good
* Slow
* Excellent

### ✅ Final Analytics

The project generates:

* Priority-wise ticket count
* Longest issue description
* Total unique words used
* Sorted list of unique words

---

## 📚 Python Concepts Used

* Variables
* Lists
* Dictionaries
* Loops (`for`, `while`)
* Conditional Statements (`if`, `elif`, `else`)
* Functions
* String Methods
* List Methods (`append`)
* Sets
* User Input Validation

---

## 📈 Learning Outcomes

Through this project, I improved my understanding of:

* Data cleaning techniques
* Dictionary and list manipulation
* Function creation and reuse
* String processing
* Input validation
* Basic text analysis
* Writing structured and reusable Python code

---

## 🚀 Future Enhancements

* Read ticket data from CSV files.
* Export analysis results to Excel.
* Perform sentiment analysis on issue descriptions.
* Visualize insights using charts.
* Store ticket information in a database.

---

## 👩‍💻 Author

**Iswarya Murugesan**

**Course:** AI-Driven Data Analyst (Entri Elevate)

---

⭐ *If you found this project useful, feel free to explore the repository and share your feedback!*

