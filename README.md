# Capstone-Project-1

🎮 Video Game Sales Analysis – Capstone Project
📘 Project Description
You work for the online store Ice, which sells video games worldwide. User and expert reviews, genres, platforms (e.g., Xbox or PlayStation), and historical sales data are available from open sources. Your task is to identify patterns that determine whether a game is successful or not. This will help detect potential hits and plan advertising campaigns.

The available data goes back to 2016. Imagine it’s December 2016 and you're preparing a campaign for 2017.

The primary goal is to gain experience working with data. It doesn’t matter whether you're predicting sales for 2017 using 2016 data or projecting 2027 sales from 2026.

The dataset includes a rating column with ESRB (Entertainment Software Rating Board) classifications like Teen or Mature.

🧭 Instructions for Completing the Project
Step 1 – Explore General Information
Open the dataset at /datasets/games.csv

Review its structure and contents.

Step 2 – Prepare the Data
Rename all column headers to lowercase.

Convert data to appropriate types.

Describe changes made and explain why.

Handle missing values:

Explain your strategy (fill or keep as NaN).

Discuss potential causes for missing data.

Pay attention to TBD (To Be Determined) values and define your approach.

Calculate total global sales (sum of all region sales) for each game in a new column.

Step 3 – Analyze the Data
Count the number of games released per year. Are all periods equally represented?

Examine platform sales:

Identify platforms with the highest total sales.

Build yearly distribution plots.

Find platforms that were popular but are now outdated.

Determine how quickly platforms rise and fall.

Choose a time period suitable for modeling 2017.

Filter the dataset to only include relevant years.

Identify platforms:

Which ones are leading?

Which are growing or declining?

Select promising platforms.

Create a box plot of global sales by platform.

Are sales differences statistically meaningful?

Discuss average sales by platform.

Analyze the effect of user and critic scores on sales:

Choose a popular platform.

Build scatter plots and compute correlations.

Compare sales of the same games across different platforms.

Study genre distribution:

Which are the most profitable?

Generalize high/low sales trends by genre.

Step 4 – Regional User Profiles
For each region (NA, EU, JP):

Identify top 5 platforms and compare market shares.

Identify top 5 genres and discuss the differences.

Evaluate if ESRB ratings affect regional sales.

Step 5 – Hypothesis Testing
Test the following:

H1: The average user ratings for Xbox One and PC are the same.

H2: The average user ratings for Action and Sports genres are different.

Include:

Your chosen significance level (α).

Null and alternative hypothesis formulation.

Reasoning behind statistical test choice.

Interpretation of results.

Step 6 – Write a General Conclusion
Complete the project using Jupyter Notebook.

Place code in code cells and explanations in markdown cells.

Use titles, subtitles, and formatting to organize the notebook.

📊 Data Description
Column	Description
Name	Game title
Platform	Platform (e.g., PS4, Xbox One)
Year_of_Release	Release year
Genre	Game genre
NA_sales	Sales in North America (in millions USD)
EU_sales	Sales in Europe (in millions USD)
JP_sales	Sales in Japan (in millions USD)
Other_sales	Sales in other regions (in millions USD)
Critic_Score	Critic rating (max 100)
User_Score	User rating (max 10)
Rating	ESRB rating (e.g., E, T, M)

⚠️ Note: Data from 2016 may be incomplete.

✅ Project Evaluation Criteria
Your project will be assessed based on:

Problem identification and handling of data issues

Data cleaning and preprocessing techniques

Quality and clarity of visualizations

Use of statistical measures (mean, std, variance)

Hypothesis formulation and testing

Explanation and interpretation of test results

Logical structure and clean, readable code

Clarity of conclusions

Relevant and clear comments/documentation throughout

Everything you need is covered in previous chapter summaries and conclusion sheets.

🚀 Good Luck!
You're now ready to dive into the dataset, explore, visualize, test, and uncover insights in the world of video game sales! 🎮📈
