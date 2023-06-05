NewsAPI Wrapper
This project is a Python wrapper for the NewsAPI (https://newsapi.org/) service. It provides a simple and convenient way to fetch top headlines and news articles based on categories or search queries.

Getting Started
To use this wrapper, you need to have a NewsAPI API key. You can sign up for a free API key on the NewsAPI website (https://newsapi.org/).

Once you have your API key, you need to replace the placeholder value with your actual API key in the API_KEY variable in the code.

Features
The wrapper currently supports the following features:

Fetch top headlines by category: You can specify a category (e.g., sports, technology, entertainment) to get the top headlines from that category in a specific country.
Fetch news articles by query: You can search for news articles based on a query string and get the top results.
Usage
The wrapper provides the following functions:

get_articles_by_category(category): Fetches top articles for a specific category. The category, sorting option, and country are customizable.
get_articles_by_query(query): Fetches top articles based on a search query. The sorting option and country are customizable.
get_sources_by_category(category): Fetches news sources for a specific category.
To use the functions, simply call them in your Python script, passing the appropriate parameters. The retrieved articles or sources will be printed to the console.

Examples
Here are some examples of how to use the wrapper:

python
Copy code
# Fetch top headlines in the sports category for France
get_articles_by_category("sports")

# Fetch top articles related to "technology" in the UK
get_articles_by_query("technology")

# Fetch news sources in the entertainment category
get_sources_by_category("entertainment")
Dependencies
This project requires the requests library to make HTTP requests. You can install it using pip:

Copy code
pip install requests
Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
