<h1>Audible Data Cleaning Project</h1>

<h2>Overview</h2>
<p>This project focuses on cleaning a dataset from Audible that includes information on audiobooks such as book names, authors, narrators, durations, release dates, languages, ratings, and prices. The aim is to prepare the dataset for further analysis or machine learning tasks by executing a series of cleaning operations.</p>

<h2>Prerequisites</h2>
<p>Before starting, ensure Python is installed along with the following packages:</p>
<ul>
  <li>pandas</li>
  <li>numpy</li>
</ul>

<h2>Dataset</h2>
<p>The dataset, named <code>audible_data_uncleaned.csv</code>, contains unclean audiobook information across several columns: <code>name</code>, <code>author</code>, <code>narrator</code>, <code>time</code>, <code>releasedate</code>, <code>language</code>, <code>stars</code>, and <code>price</code>.</p>

<h2>Cleaning Steps</h2>
<p>The cleaning process involves:</p>
<ol>
  <li><strong>Capitalizing Column Headers</strong>: Standardizing header names for consistency.</li>
  <li><strong>Removing Unwanted Content</strong>: Cleaning 'Author' and 'Narrator' columns by removing prefixes.</li>
  <li><strong>Separating Names</strong>: Adding spaces between first names and last names in 'Author' and 'Narrator' columns for better readability.</li>
  <li><strong>Date Formatting</strong>: Converting 'Release Date' to datetime format and categorizing 'Language'.</li>
  <li><strong>Language Capitalization</strong>: Capitalizing all entries in the 'Language' column for uniformity.</li>
  <li><strong>Splitting Rating Information</strong>: Dividing the 'Stars' column into 'Rating' and 'Number of Ratings' columns.</li>
  <li><strong>Cleaning Prices</strong>: Standardizing the 'Price' column by removing non-numeric characters and converting 'Free' to '0'.</li>
  <li><strong>Filling Missing Values</strong>: Addressing any missing values in 'Rating' and 'Number of Ratings' by substituting them with '0'.</li>
  <li><strong>Export Cleaned Data</strong>: Saving the cleaned dataset as <code>audible_data_cleaned.csv</code>.</li>
</ol>

<h2>Usage</h2>
<ul>
  <li>Clone this repository to your local machine.</li>
  <li>Ensure the <code>audible_data_uncleaned.csv</code> file is in the same directory as the script.</li>
  <li>Execute the script to perform the data cleaning.</li>
  <li>The cleaned dataset, <code>audible_data_cleaned.csv</code>, will be saved in the same directory.</li>
</ul>

<h2>Future Work</h2>
<p>Further enhancements could include in-depth data analysis, feature engineering, or developing machine learning models to predict audiobook popularity or make recommendations based on user preferences.</p>
