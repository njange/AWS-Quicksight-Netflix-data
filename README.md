## Amazon QuickSight Project - README

# This project details the steps I followed to learn about Amazon QuickSight and explore the netflix_titles.csv dataset. The findings are documented in a Canva presentation [Link to your Canva presentation].

## Key Learnings

Storing Data in S3: Uploading data to an S3 bucket allows QuickSight to access and process it.

Manifest.json: This file provides metadata about the data in the CSV file, including structure and organization.

Connecting S3 to QuickSight: The manifest.json file acts as a bridge between the S3 bucket and QuickSight, enabling data connection.

Data Visualization: QuickSight offers various chart types (donut, bar charts, etc.) to explore and understand data.

Adding Filters: Filters allow you to focus on specific data subsets within your visualizations.

## Step-by-Step Guide

This section provides a high-level overview of the steps covered in the project.

Downloaded the netflix_titles.csv and manifest.json datasets.

Created an S3 bucket and uploaded the data files. Edited the manifest.json file with the S3 bucket URL.
![S3](https://github.com/njange/AWS-Quicksight-Netflix-data/assets/128843179/9023ca36-b478-44bb-a968-54197a22f50c)


Signed up for a free trial of Amazon QuickSight and connected the S3 bucket containing the datasets.

Created the first visualizations - a donut chart showing release year distribution and a horizontal bar chart comparing release year with content type (movie/TV show).
![Quicksight](https://github.com/njange/AWS-Quicksight-Netflix-data/assets/128843179/525afc62-e5f6-4ef0-a308-02522c2d4f43)


Explored further using filters to answer questions provided by a data team lead:

Stacked bar chart visualizing the percentage of movies vs TV shows per release year.

Table showing the number of movies vs TV shows per release year.

Identifying the day with the most significant number of movies/TV shows added to the Netflix catalog.

Counting TV shows and movies categorized as "Action & Adventure", "TV Comedies", or "Thrillers".

Counting TV shows and movies with "Action & Adventure", "TV Comedies", or "Thrillers" categories released in 2015 or later.
![Complete Quicksight Dashboard](https://github.com/njange/AWS-Quicksight-Netflix-data/assets/128843179/e5635ba4-53a6-438b-9ce9-7919c6f1ab13)


Added titles to the charts for better understanding.

Published and exported the dashboard as a PDF.

## Next Steps

Explore more advanced data manipulation and visualization techniques in Amazon QuickSight.

Integrate findings from this project with other data sources for richer insights.
