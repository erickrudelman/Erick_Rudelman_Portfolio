---
date: 2023-08-08T11:00:59-04:00
description: "Web scraping from a Disney movie list "
featured_image: "/images/disney.jpg"
tags: []
title: "Chapter III: Disney Movies Web Scraping"
---

The provided code is a Python script that performs web scraping to gather information about Disney movies from Wikipedia. It utilizes libraries like `beautifulsoup4` and `requests` to extract and process data from HTML web pages.

The script effectively scrapes Wikipedia pages, extracts movie information, and enhances the data by fetching additional details from external sources. It then saves the enriched data in different formats for further analysis or display.

**TASK 1:**

1. The script starts by importing the necessary libraries.
2. It specifies the URL of a Wikipedia page about the movie "Toy Story 3".
3. The script sends a GET request to the URL and converts the response to a Beautiful Soup object for parsing.
4. The title of the webpage is extracted and printed.

**TASK 2:**

1. The script specifies the URL of a Wikipedia page listing Disney movies.
2. It sends a GET request to the URL and converts the response to a Beautiful Soup object.
3. The script selects elements with the class `wikitable.sortable i` (which represents movie titles) from the HTML.
4. It then iterates through the selected movie titles and extracts their relative paths and titles.
5. For each movie, it constructs the full URL, sends a request to the movie's page, and extracts information about the movie using the `get_info_box` function.

**TASK 3:**

1. The script defines a function `minutes_to_integer` to convert running time strings (e.g., "74 minutes") to integers.
2. It defines functions `clean_date` and `date_conversion` to clean and convert release date strings to datetime objects.
3. It adds the integer running time and datetime release date to each movie's dictionary.

**TASK 4:**

1. The script defines functions to save and load data using both JSON and pickle formats.
2. It loads the previously cleaned movie data using pickle.
3. It utilizes the OMDB API to fetch additional movie information such as IMDb rating, Metascore, and Rotten Tomatoes score for each movie.
4. The fetched information is added to each movie's dictionary.

**TASK 5:**

1. The script copies the cleaned movie data to a new list, converting datetime objects to formatted strings.
2. It saves the data in JSON format and CSV format using the `save_data` function and a Pandas DataFrame, respectively.



[Link to GitHub Repository](https://github.com/rudicr/data_science_projects/blob/Data-Science-Projects/Disney%20Movies%20Web%20Scraping%20Project.py)