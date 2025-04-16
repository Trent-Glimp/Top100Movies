# Top100Movies

A Python application that scrapes the IMDB Top 100 movies list and allows users to filter and discover great movies based on various criteria.

## Description

Top100Movies is a command-line movie recommendation tool that scrapes data from IMDB's top 100 rated movies. The application allows you to filter these highly-rated films by:

- Specific year
- Decade
- Maturity rating
- Genre
- Rank in the Top 100 list
- Runtime
- IMDB rating

Perfect for movie enthusiasts looking to find their next great watch from the best-rated films of all time!

## Features

- Real-time scraping of IMDB's current Top 100 movies
- Multiple filtering options to narrow down movie choices
- Clean display of movie information including title, year, rating, runtime, maturity rating, and genres
- Interactive command-line interface

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Top100Movies.git
   cd Top100Movies
   ```

2. Install required dependencies:
   ```
   pip install requests beautifulsoup4
   ```

## Usage

Run the main script to start the application:
```
python main.py
```

Follow the on-screen prompts to:
1. Select a filtering option (1-7)
2. Choose from available values for your selected filter
3. View your recommended movies
4. Choose whether to run another search or exit

## Project Structure

- `main.py` - Entry point of the application with the user interface
- `imdb_scraper.py` - Contains the web scraping functionality
- `movie_class.py` - Defines the Movie class used to store and display movie data

## Requirements

- Python 3.6+
- requests
- BeautifulSoup4

## Acknowledgments

- Data is sourced from IMDB (Internet Movie Database)
- This project is for educational purposes only