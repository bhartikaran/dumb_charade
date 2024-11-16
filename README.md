# Bollywood Movie Fetcher 🎬
This project is a fun Python-based tool designed to fetch Bollywood movies from Wikipedia for user-specified years. It provides a random movie suggestion from the fetched list and can also be used for games like Dumb Charades!
The project includes a Jupyter Notebook script and a pre-saved CSV file of movie names for further use.

# Features ✨
Fetches a list of Bollywood movies from Wikipedia for the year(s) entered by the user.
Randomly suggests a Bollywood movie from the fetched list.
Includes a pre-saved CSV file with movie names, which can be used for games or analysis.
## How It Works 🛠️
User Input: You input the desired year(s) (e.g., 2018, 2019) in the Jupyter Notebook.
Web Scraping: The script fetches movie data from Wikipedia for the specified year(s).
Random Movie Selection: The script randomly selects a movie from the fetched list.
CSV File: The project includes a CSV file containing Bollywood movie names that can be used independently for games like Dumb Charades.

# Repository Structure 📂

├── bollywood.ipynb ======> Jupyter Notebook containing the movie fetching and random movie selection script

├── movies.csv ======> Pre-saved CSV file containing Bollywood movie names

├── README.md  ======> Documentation file
# Prerequisites 📋
To run the script, you'll need the following:

Python 3.x
Jupyter Notebook
Required libraries:
pandas
random
requests
beautifulsoup4
You can install the libraries using pip:

pip install pandas requests beautifulsoup4

# How to Use 🚀
Clone the repository to your local machine:
Open the fetch_movies.ipynb file in Jupyter Notebook:

jupyter notebook bollywood.ipynb
Enter the desired year(s) when in the notebook, and the script will:

Fetch the list of Bollywood movies for those years.
Save the movies in a list.
Suggest a random movie from the list.
Use the pre-saved movies.csv file for other purposes, such as playing Dumb Charades.

# Use Case 🎮
Dumb Charades: Use the pre-saved movies.csv file to randomly select movie names.
Movie Enthusiasts: Quickly get a list of Bollywood movies for specific years.
Game Nights: Randomly select movies for fun challenges with friends.
# Future Enhancements 🚀
Add support for more years and other movie industries (e.g., Hollywood, Tollywood).
Enable direct fetching of movie posters or trailers.
Build a GUI for non-technical users.
