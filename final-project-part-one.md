| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# The Hidden Taste
*Do our movie habits really reflect our preferences?*

# Outline

## High-level Summary
For this final project, I plan to explore the relationship between users' movie rating habits and their preferences, with a particular interest in how these insights can inform movie recommendation systems. The movie genres users interact with most frequently may not necessarily be the ones they enjoy the most. For example, in my preliminary analysis of the MovieLens 32M dataset, one user rated 102 drama movies with an average rating of 3.55, while rating only 19 action movies with a higher average rating of 4.11. This example raises an interesting question: if recommendations rely heavily on interaction frequency, could some of a user's interests be overlooked?

Using the MovieLens 32M dataset, I plan to examine how common this gap is among users by comparing their rating frequency and average rating across movie genres. I also want to identify potential hidden tastes, which I define as genres that users rate relatively infrequently but more positively than their personal average. Through this project, I hope to show recommendation system designers why it may be valuable to consider both established preferences and less-explored interests when developing personalized movie recommendations.

## Project Structure
**One-line Summary**: The movie genres we engage with most frequently may not always be the ones we enjoy the most.

**Target Audience**: Product managers, data analysts, and movie recommendation system designers.

**Reader's Perspective**: As a designer of movie recommendation systems, I want to understand how users' most frequently rated movie genres differ from their highest-rated genres so that I can identify overlooked interests and improve personalized recommendations.

**Call to Action**: Consider both frequently rated genres and less-explored but highly rated genres when designing personalized movie recommendations.

### An Outline

- **Introduction of the Topic**
  - Introduce the role of user interactions in movie recommendation systems.
  - Explain the difference between rating frequency and average rating.
  - Introduce the central question: Do our movie habits really reflect our preferences?

- **Explore the Preference Gap at the Individual Level**
  - Visualization 1: Show the number of ratings across movie genres for an individual user to identify their most frequently rated genres.
  - Visualization 2: Show the average rating of each genre for the same user and compare it with their rating frequency.
  - Highlight the differences between frequently rated genres and highly rated genres.

- **Expand the Analysis to a Broader Group of Users**
  - Visualization 3: Show the proportion of eligible users whose most frequently rated genres differ from their highest-rated genres.
  - Examine whether the preference gap is an isolated case or a common pattern among users.

- **Discover Potential Hidden Tastes**
  - Define hidden tastes as relatively infrequently rated genres with average ratings above a user's personal average, subject to a minimum number of ratings.
  - Visualization 4: Explore the relationship between relative rating frequency and average rating, highlighting potential hidden tastes.
  - Visualization 5: Identify which movie genres are most commonly associated with users' hidden tastes.
  - Discuss how these findings relate to the reader's perspective.

- **Call to Action**
  - Encourage movie recommendation system designers to consider less frequently rated but highly rated genres alongside users' established interests.
  - Discuss the potential for more diverse and personalized movie recommendations.
  - Conclude the story.

## Initial sketches

### Sketch 1: Exploring the Preference Gap at the Individual Level

![Comparison of rating frequency and average rating by genre](sketch1.png)

These two bar charts compare an individual user's rating frequency and average rating across selected movie genres. I plan to use blue to highlight Drama, the user's most frequently rated genre, and orange to highlight Action, a less frequently rated but highly rated genre. Placing the charts side by side allows readers to easily identify the gap between rating habits and preferences.

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Text here...

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|      |     |             |
|      |     |             |
|      |     |             |

# Method and medium
> In a few sentences, you should document how you plan on completing your final project. 

Text here...

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._
