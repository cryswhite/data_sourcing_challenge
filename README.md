# data_sourcing_challenge
This is the start of my README file for Week 6 Challenge. For this challenge, I used soooo many sources: ChatGPT, GitHub Copilot, Bard, _Python Programming for Dummies_, _Hands-On Python Foundations Scenarios_ by Arianne Dee, examples from class, the assignment instrutions and supplied code, a tutor, my husband, and good ol' Google. 

And, unfortunately, the assignment instructions warned of calling too many files from the NYT API _after_ I performed the function correctly, then got an error at a later point, so I went back and deleted/recoded the previous sections. What I didn't do is see the warning which occurred _after_ the instructions of what to do, warning me about the NYT API limit. So, then I started throwing errors like a two-year-old throws tantrums.

I have now created a new API and am hoping the gods will be kind and make this code semi-function. If it doesn't, well, I hope this will be like college Calculus and statistics where if you show your work, you still get partial credit even though it doesn't execute correctly. My faith is minimal considering I seem to have a very hard grader who doesn't consider anything partly correct to be worth partial credit. But, maybe someone's looking out for me today and will grant me some grace.

And, without further adieu, I will turn it once again over to ChatGPT who provided the info for the following documentation.

# Data Sourcing and Analysis Assignment README

## Assignment Overview

This README document provides an overview of the Data Sourcing and Analysis assignment. The assignment required extracting movie-related data from The New York Times API and The Movie Database (TMDB) API, merging the data, and performing various data manipulation tasks.

## Approach

### Section 1: The New York Times API

- **Build URL**: Created a base URL for The New York Times API, including the necessary filters, date range, and API key.
- **API Requests**: Used a loop to make multiple requests to the API, handling rate limits by adding a delay.
- **Error Handling**: Implemented error handling to capture failed requests and continue the loop.
- **Data Extraction**: Extracted relevant data fields from the API responses.
- **Data Transformation**: Converted the data into a Pandas DataFrame.
- **Data Cleaning**: Removed duplicate records and null values.
- **Keyword Extraction**: Extracted keywords from the "keywords" column.
- **Title Extraction**: Extracted movie titles from the "headline.main" column.
- **Data Export**: Exported the cleaned and transformed data to a CSV file for further analysis.

### Section 2: The Movie Database (TMDB) API

- **TMDB Query Preparation**: Prepared the query URL for TMDB API by including the API key and the movie title.
- **API Requests**: Utilized a loop to send requests to TMDB API, managing rate limits with a delay.
- **Error Handling**: Implemented try-except blocks to handle errors gracefully and continue the loop.
- **Data Extraction**: Extracted relevant movie details from TMDB API responses.
- **Data Transformation**: Converted the data into a list of dictionaries.
- **Data Merging**: Merged the TMDB data with the NYT reviews data based on the movie title.
- **Data Export**: Exported the merged data to a CSV file.

## Troubleshooting

Throughout the assignment, troubleshooting was conducted for various issues, including:
- Handling API rate limits and sleep intervals.
- Handling missing or incomplete data from API responses.
- Ensuring data integrity and accuracy during merging.

## Citations

- The New York Times API documentation: [NYT API Documentation](https://developer.nytimes.com/apis)
- The Movie Database (TMDB) API documentation: [TMDB API Documentation](https://developers.themoviedb.org/3/getting-started/introduction)
- Pandas documentation for data manipulation: [Pandas Documentation](https://pandas.pydata.org/docs/)
- Assistance and guidance provided by ChatGPT, an AI language model by OpenAI.

## Conclusion

This assignment allowed us to practice data sourcing, data cleaning, and data analysis skills. It involved extracting data from multiple sources, handling rate limits, and merging datasets to perform further analysis. Troubleshooting and error handling were essential in ensuring the success of the project.

For any questions or clarifications, please contact Crystal White at pleasedontcontactmeaboutthis@email.com.
