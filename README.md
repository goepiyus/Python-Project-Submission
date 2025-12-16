# Python-Project-Submission
#  Book Data Collection & Recommendation System

This project collects book data from the **Open Library API**, processes and cleans the data, and provides interactive tools for **filtering, ranking, and randomly recommending books** based on user preferences such as genre, popularity, rank, and publication year.

## Features

### 1. Data Collection
- Fetches book data using the Open Library Search API
- Retrieves additional genre/subject information using the Open Library Works API
- Stores data in both **CSV** and **Excel** formats

### 2. Data Processing
- Removes unwanted book types (journals, notebooks, coloring books, etc.)
- Cleans and standardizes genre data
- Ranks books by popularity (edition count)

### 3. User Interaction
- Filter books by:
  - Genre
  - Popularity
  - Rank range
  - Publication year range
- Interactive command-line filtering interface
- Random book recommendation by genre 🎲

## 🧠 Data Source
- **Open Library API**
  - Search API: `https://openlibrary.org/search.json`
  - Works API: `https://openlibrary.org/works/{work_id}.json`


## Libraries Used

The following Python libraries are used in this project:

- Library - Purpose 

- requests- Making HTTP requests to the Open Library API 
- pandas-Data manipulation, cleaning, and analysis 
- time-Adding delays between API requests 
My project is a book suggestion app that integrates various concepts such as Data collection, data processing, user interaction, error handling and code quality.
I create my project using Jupyter Notebook as an IDE.

