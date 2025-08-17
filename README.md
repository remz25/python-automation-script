# python-automation-script
a script that opens and checks a web page to check it if contans a keyword 
# Web Page Title Keyword Checker

A simple Python script that fetches a web page, extracts its title, and checks whether it contains a given keyword.

## Features
- Fetches any URL using `requests`
- Parses HTML to extract the `<title>` tag with `BeautifulSoup`
- Performs a case-insensitive keyword match
- Handles connection errors gracefully
- Prints clear ✅ / ❌ results

## Requirements
- Python 3.7+
- [requests](https://pypi.org/project/requests/)
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)

Install dependencies:
```bash
pip install requests beautifulsoup4
\

python check_title.py
url_to_check = "https://www.python.org"
keyword_to_find = "Python"
chec✅ Found 'Python' in title: 'Welcome to Python.org'
k_title_keyword(url_to_check, keyword_to_find)

import webbrowser
webbrowser.open(url_to_check)
Add this before calling check_title_keyword.
License

This project is licensed under the MIT License — see the  LICENSE file for details.



---


