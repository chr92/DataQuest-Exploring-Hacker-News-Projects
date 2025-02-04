# DataQuest-Exploring-Hacker-News-Projects

This project explores posts from Hacker News, a popular site where technology-related stories are voted and commented upon. The analysis focuses on comparing two types of posts: Ask HN and Show HN.

## Project Overview

In this project, we aim to answer the following questions:
1. Do Ask HN or Show HN receive more comments on average?
2. Do posts created at a certain time receive more comments on average?

The dataset used in this project was reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments and then randomly sampling from the remaining submissions.

## Dataset Structure

The dataset contains the following columns:
- `id`: The unique identifier from Hacker News for the post
- `title`: The title of the post
- `url`: The URL that the post links to, if the post has a URL
- `num_points`: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
- `num_comments`: The number of comments on the post
- `author`: The username of the person who submitted the post
- `created_at`: The date and time of the post's submission

## Files in the Repository

- `HackerNews.ipynb`: Jupyter Notebook containing the analysis of the Hacker News posts.
- `hacker_news.csv`: CSV file containing the dataset used for the analysis.
- `LICENSE`: The MIT License file for the project.
- `README.md`: This file, providing an overview of the project.

## How to Run the Project

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd DataQuest-Exploring-Hacker-News-Projects
    ```
3. Open the Jupyter Notebook:
    ```sh
    jupyter notebook HackerNews.ipynb
    ```
4. Run the cells in the notebook to perform the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.