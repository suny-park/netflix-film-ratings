# Netflix Original Film Rating Analysis
## Goal
Compare ratings of Netflix original films across different movie websites, define key predictors that lead to higher ratings, and generate predictions of unreleased films.

## Key Techniques
- Webscraping with `beautifulsoup`
- Data cleaning with `pandas`
- SQL table manipulation with `LEFT JOIN`, `INNER JOIN`, `UNION`, etc.
- (to be added)

## Code Overview
### [01 Webscraping Wikipedia for Netflix original films.ipynb](01%20Webscraping%20Wikipedia%20for%20Netflix%20original%20films.ipynb)
Webscrape a list of Netflix original films from [wikipedia pages](https://en.wikipedia.org/wiki/Lists_of_Netflix_original_films) using `beautifulsoup` and save as a csv file.

### [02 Creating a Database with IMDB and Netflix Data.ipynb](02%20Creating%20a%20Database%20with%20IMDB%20and%20Netflix%20Data.ipynb)
Download [IMDB rating data from kaggle](https://www.kaggle.com/datasets/ashirwadsangwan/imdb-dataset) and create a SQLite database using `sqlite3`.

### [03 Combining Netflix and IMDB data.ipynb](03%20Combining%20Netflix%20and%20IMDB%20data.ipynb)
Obtain IMDB ratings for the Netflix films in the list using SQL `JOIN` keywords on film title and other information.
