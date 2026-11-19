| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# The Hidden Taste
*Do our movie habits really reflect our preferences?*

# Outline

## High-level Summary
For this final project, I plan to explore the relationship between users' movie rating habits and their preferences, with a particular interest in how these insights can inform movie recommendation systems. The movie genres users interact with most frequently may not necessarily be the ones they enjoy the most. For example, in my preliminary analysis of the MovieLens 32M dataset, one user rated 102 drama movies with an average rating of 3.55, while rating only 19 action movies with a higher average rating of 4.11. This example raises an interesting question: if recommendation systems rely heavily on interaction frequency, could some of a user's interests be overlooked?

Using the MovieLens 32M dataset, I plan to examine how common this gap is among users by identifying users whose most frequently rated genres differ from their highest-rated genres. I also want to identify potential hidden tastes, which I define as genres that users rate relatively infrequently but more positively than their personal average. Through this project, I hope to encourage recommendation system designers to consider both established preferences and less-explored interests when developing personalized movie recommendations.

## Project Structure
**One-line Summary**: The movie genres we engage with most frequently may not always be the ones we enjoy the most.

**Target Audience**: Product managers, data analysts, and movie recommendation system designers.

**Reader's Perspective**: As a designer of movie recommendation systems, I want to understand whether users' most frequently rated movie genres differ from the genres they rate most highly on average so that I can identify potential hidden interests and explore ways to make personalized recommendations more responsive to users' preferences.

**Call to Action**: Consider both frequently rated genres and less-explored but highly rated genres when designing personalized movie recommendations.

### An Outline

- **Introduction of the Topic**
  - Introduce the role of user interactions in movie recommendations.
  - Highlight how rating frequency and average rating may reveal different preferences.
  - Raise the central question: Do our movie habits really reflect our preferences?

- **Explore the Preference Gap at the Individual Level**
  - Visualization 1: Show an individual user's rating frequency by genre.
  - Visualization 2: Compare the same user's average ratings across genres.
  - Highlight gaps between frequently rated and highly rated genres.

- **Expand the Analysis to a Broader Group of Users**
  - Visualization 3: Show the proportion of eligible users whose most frequently rated genres differ from their highest-rated genres.
  - Examine how common this preference gap is.

- **Discover Potential Hidden Tastes**
  - Define hidden tastes as less frequently rated genres with above-personal-average ratings, subject to a minimum rating count.
  - Visualization 4: Plot relative rating frequency against average rating to highlight potential hidden tastes.
  - Visualization 5: Show the distribution of eligible users by the number of potential hidden tastes they have.

- **Call to Action**
  - Encourage recommendation designers to consider both established preferences and potential hidden tastes.
  - Discuss implications for more diverse and personalized recommendations.

## Initial sketches

### Sketch 1: Exploring the Preference Gap at the Individual Level

![Comparison of rating frequency and average rating by genre](sketch1.png)

These two bar charts compare an individual user's rating frequency and average rating across selected movie genres. I plan to use blue to highlight Drama, the user's most frequently rated genre, and orange to highlight Action, a less frequently rated but highly rated genre. Placing the charts side by side allows readers to easily identify the gap between rating habits and preferences.

### Sketch 2: How Common Is the Preference Gap?

![Proportion of users with a preference gap](sketch2.png)

This waffle chart will show the proportion of users whose most frequently rated genres differ from their highest-rated genres. I plan to use orange to represent users with a preference gap and gray to represent those without one. This visualization will help readers understand whether the preference gap is an isolated case or a common pattern among users.

### Sketch 3: Discovering Hidden Tastes

![Relationship between relative rating frequency and average rating](sketch3.png)

This scatter plot will explore the relationship between relative rating frequency and average rating. I plan to use orange to highlight genres that users rate less frequently but more positively than their personal average. The two reference lines will help readers identify potential hidden tastes.

### Sketch 4: Which Genres Are Hidden Tastes?

![Movie genres most commonly identified as hidden tastes](sketch4.png)

This horizontal bar chart will show the percentage of eligible users who have each movie genre as a potential hidden taste. I plan to arrange the genres in descending order and use orange to highlight the most common one, while keeping the remaining genres gray. This visualization will help recommendation system designers identify opportunities to introduce users to less-explored movie genres.

*Note: The genre rankings and percentages shown are illustrative and do not represent actual analysis results.*

# The data

For this project, I will use the MovieLens 32M dataset, provided by the GroupLens Research Group at the University of Minnesota. The dataset contains 32,000,204 ratings across 87,585 movies from 200,948 users, collected between January 1995 and October 2023. I will primarily use two files: `movies.csv`, which contains movie IDs, titles, and genres, and `ratings.csv`, which contains user IDs, movie IDs, ratings, and timestamps.

I plan to combine these two files using movie IDs and calculate the rating frequency and average rating for each genre at the individual user level. Since a movie can belong to multiple genres, I will associate each rating with all its listed genres and exclude movies without genre information. To identify potential hidden tastes, I plan to focus on genres with at least five ratings, a rating frequency no more than 50% of the user's most frequently rated genre, and an average rating above the user's personal average. These criteria will help me identify less frequently rated but positively rated genres while reducing the influence of limited rating observations.

One limitation of this dataset is that it captures rating behavior rather than actual viewing history. Therefore, I will use rating frequency and average ratings as indicators of users' habits and preferences rather than direct measures of their viewing behavior.

## Data Source

| Name | URL | Description |
|------|-----|-------------|
| MovieLens 32M Dataset | [GroupLens](https://grouplens.org/datasets/movielens/32m/) | Official dataset containing movie ratings and genre information. |
| MovieLens 32M Data Files | [Download Dataset](https://files.grouplens.org/datasets/movielens/ml-32m.zip) | Downloadable ZIP file containing movies.csv, ratings.csv, and other supporting files. |
| MovieLens 32M Documentation | [README](https://files.grouplens.org/datasets/movielens/ml-32m-README.html) | Documentation of the dataset structure, collection process, and usage conditions. |

# Method and medium

I plan to use Python (Pandas) to clean, combine, and analyze the MovieLens 32M dataset. I will use Tableau to create interactive visualizations that allow readers to explore the relationship between users' rating habits and preferences. For the final presentation, I plan to use Shorthand to combine visualizations and narrative text into a interactive data story. I will also use GitHub to document my project development process and share the final project.

## References

- GroupLens Research. (2024). [MovieLens 32M Dataset](https://grouplens.org/datasets/movielens/32m/). University of Minnesota.
- Harper, F. M., & Konstan, J. A. (2015). The MovieLens Datasets: History and Context. *ACM Transactions on Interactive Intelligent Systems, 5*(4), 19:1–19:19. [https://doi.org/10.1145/2827872](https://doi.org/10.1145/2827872)

## AI acknowledgements

I used ChatGPT to help refine my research questions, organize the story structure, and develop Python code for preliminary data analysis. I also used ChatGPT to improve the clarity, wording, and grammar of my written content.
