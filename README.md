# Painting Dataset Analysis with SQL

This repository contains SQL queries for an in-depth analysis of a painting dataset using PostgreSQL. The dataset encompasses information on paintings, artists, museums, and related aspects. The following questions are addressed through SQL queries to provide comprehensive insights into the dataset:

## Overview:

- **Data Cleaning:**
  - Removal of duplicate records from tables such as `work`, `product_size`, `subject`, and `image_link`.
  - Identification and deletion of invalid entries in the `museum` and `museum_hours` tables.

- **Top Rankings:**
  - Identification of the top 10 most famous painting subjects.
  - Determination of museums open on both Sunday and Monday.
  - Counting museums open every single day.
  - Recognition of the top 5 most popular museums based on the number of paintings.
  - Identification of the top 5 most popular artists based on the number of paintings.

- **Insights:**
  - Identification of artists with paintings displayed in multiple countries.
  - Determination of countries and cities with the most museums.
  - Recognition of the most and least popular painting styles.
  - Identification of the artist with the most portraits paintings outside the USA.

## Repository Structure:

- **data:** File containg data in csv format.
- **Loading the data:** Python notebook containg how to load data from pandas to sql.
- **Queries:** SQL files containing individual queries.
- **Qestions file:** PDF files containg the list of questions.
- **README.md:** Documentation explaining the dataset analysis and usage.

Feel free to explore and adapt these queries for your own analysis. If you have any questions or improvements, please don't hesitate to open an issue or contribute!
