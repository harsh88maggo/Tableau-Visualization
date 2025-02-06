# Amazon Top 50 Bestselling Books 2009-2019 Dataset

## Overview
This repository contains analysis based on the **Amazon Top 50 Bestselling Books 2009-2019** dataset, which includes information about bestselling books from Amazon, spanning both fiction and non-fiction categories. The analysis answers key questions such as the most reviewed books, the highest-rated authors, and the most expensive bestsellers.

### Dataset Source
The dataset was scrapped in October 2020 by Saalu Sooter. You can access the dataset on Kaggle [here](https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019).

## Key Sections of the Workbook

### 1. **Data Preprocessing**
   - **Description**: This section processes the raw data, ensuring all columns are clean, formatted properly, and ready for analysis.
   - **Actions**: Removes duplicates, handles missing values, and standardizes column names for consistency.

### 2. **Top 10 Most Reviewed Books**
   - **Purpose**: Identifies the top 10 books with the most reviews from the dataset.
   - **Action**: Books are sorted by the number of reviews in descending order, showing the book title, author, and review count.

### 3. **Preferred Genre Among Bestsellers**
   - **Purpose**: Determines which genre (fiction or non-fiction) is more prominent based on the number of reviews and ratings.
   - **Action**: A comparison chart shows the number of reviews, ratings, and bestsellers in each genre.

### 4. **10 Most Loved Authors Based on User Ratings**
   - **Purpose**: Displays the top 10 authors with the highest average user ratings.
   - **Action**: Lists authors with the highest ratings across all their books.

### 5. **Top 5 Most Reviewed Authors**
   - **Purpose**: Finds the top 5 authors whose books have the highest number of reviews.
   - **Action**: Books by these authors are listed with the number of reviews for each book.

### 6. **10 Most Expensive Bestsellers**
   - **Purpose**: Lists the top 10 bestselling books with the highest prices.
   - **Action**: Books are sorted by price in descending order.

### 7. **10 Highest-Rated Bestsellers**
   - **Purpose**: Displays the top 10 bestselling books with the highest user ratings.
   - **Action**: Books are sorted by user ratings in descending order.

### 8. **10 Most Affordable Books**
   - **Purpose**: Highlights the 10 most affordable bestselling books in the dataset.
   - **Action**: Books are listed by price, sorted in ascending order.

## How to Use the Workbook

### Step 1: **Load the Dataset**
Ensure the dataset is loaded into the workbook. It should be in CSV format containing the following columns:
   - **Title**: Book title
   - **Author**: Author of the book
   - **Genre**: Fiction or Non-fiction
   - **Price**: Price of the book
   - **User Rating**: Average rating from users
   - **Number of Reviews**: Number of reviews submitted for the book
   - **Year**: Year of release for the book

### Step 2: **Run Data Preprocessing**
Go to the **Data Preprocessing** section to clean and prepare the data. This will handle missing values, remove duplicates, and format the columns properly.

### Step 3: **Navigate to Each Analysis Section**
- **Top 10 Most Reviewed Books**: View a list of books with the highest number of reviews. This gives insight into popular books.
- **Preferred Genre Among Bestsellers**: Compare the frequency of reviews, ratings, and bestsellers in fiction vs. non-fiction.
- **10 Most Loved Authors Based on User Ratings**: Check out the authors with the highest ratings.
- **Top 5 Most Reviewed Authors**: See which authors have the most reviewed books.
- **10 Most Expensive Bestsellers**: Get a list of books with the highest price points.
- **10 Highest-Rated Bestsellers**: View the best books by user ratings.
- **10 Most Affordable Books**: Find affordable bestsellers sorted by price.

### Step 4: **Interactive Features**
If the workbook supports filtering:
- **Select specific genres** (fiction/non-fiction).
- **Sort by attributes** such as price, ratings, or review count.
- **View graphs** to visualize genre preferences and rating distributions.

### Step 5: **Save or Export Results**
Once the analysis is complete, you can export the tables, charts, and findings to Excel or PDF for reporting purposes.

## Important Notes
- **Data Quality**: The dataset includes books from 2009 to 2019. Some entries may have missing or incomplete data. Always verify the completeness of the dataset before making conclusions.
- **Price Information**: Prices may be outdated or vary by region or book availability.
- **Ratings**: User ratings are averages, and may not fully represent the opinions of all readers.

