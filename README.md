# Data Analysis: Exploring Hacker News Posts

## Project Overview
This project focuses on analyzing a dataset of submissions to **Hacker News**, a popular technology-oriented social news website. The goal is to apply Python's data manipulation and string processing capabilities to determine which types of posts generate the highest user engagement.

Specifically, we compare two types of submissions:
- **Ask HN**: Posts where users ask the community a specific question.
- **Show HN**: Posts where users showcase a project or product.

## Objectives
*   **Engagement Analysis**: Determine whether `Ask HN` or `Show HN` posts receive more comments on average.
*   **Temporal Analysis**: Identify if the time of day a post is created influences the average number of comments received.

## Dataset
The dataset (hacker_news.csv) consists of approximately **20,000 rows**, downsampled from the original Hacker News dataset to include only posts that received comments.

**Key Columns:**
- `id`: Unique identifier for the post.
- `title`: Title of the post.
- `num_points`: Total points (upvotes minus downvotes).
- `num_comments`: Number of comments on the post.
- `created_at`: Date and time of submission.

## Skills Demonstrated
*   **Data Cleaning**: Removing headers and handling non-numeric data.
*   **String Manipulation**: Using methods like `startswith()` and `lower()` to categorize data.
*   **Object-Oriented Programming**: Working with Python lists and list of lists.
*   **Date & Time Engineering**: Utilizing the `datetime` module to perform time-series analysis.

## How to Run
1. Ensure you have Python and Jupyter Notebook installed.
2. Clone this repository.
3. Download the `hacker_news.csv` file.
4. Run the `Exploring_Hacker_News_Posts.ipynb` notebook.
