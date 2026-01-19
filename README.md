Overview

This repository contains a simple Python web scraping program. The project demonstrates how to retrieve web page content from a given URL, extract the text using BeautifulSoup, and save the scraped content into a text file.

The implementation is provided in three formats:

A Python script (.py)

A Jupyter Notebook (.ipynb)

A text output file (.txt) containing the scraped article content

🛠️ Technologies Used

Python 3

Requests – to send HTTP requests and fetch web page content

BeautifulSoup (bs4) – to parse and extract text from HTML

OS module – to create directories and manage file paths

Google Colab Drive – to store output files persistently

📥 Input

A web article URL (entered by the user at runtime)

📤 Output

A .txt file containing the extracted text of the article

The file is saved inside a folder named scraped_articles

⚙️ How the Script Works

Accepts a URL as user input

Sends an HTTP request to fetch the web page

Parses the HTML content using BeautifulSoup

Extracts all visible text from the page

Creates a directory (if it does not already exist)

Saves the extracted content into a text file

📁 Repository Structure
.
├── task1_script.py      # Python web scraping script
├── task2.ipynb          # Jupyter Notebook version of the script
├── article.txt          # Scraped output text file
└── README.md            # Project description

🔍 Purpose of the Project

This project is designed to:

Demonstrate basic web scraping concepts

Practice GitHub workflows (branching, committing, pull requests, and merging)

Understand how Python scripts can be replicated in Jupyter Notebooks

Learn collaborative development using GitHub reviews
