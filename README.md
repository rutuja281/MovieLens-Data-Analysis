# MovieLens Exploratory Data Analysis (EDA)

## Project Overview

This project involves performing exploratory data analysis on the [MovieLens 1M Dataset](https://grouplens.org/datasets/movielens/) to uncover user behavior, rating patterns, and potential relationships between demographics and movie preferences. The dataset consists of **1 million ratings** from **6,000 users** on **4,000 movies**, including metadata like user age, gender, and movie genres.

The analysis was done as part of Case Study 3 for the Datapreneurs program, focusing on real-world applications and storytelling through data.

---

## Motivation

- **Size and Variety**: With over a million ratings across thousands of movies, the dataset offers rich opportunities for statistical analysis and modeling.
- **Real-World Relevance**: Movie preferences are universally relatable, making the findings engaging and interpretable to a broad audience.
- **Educational Value**: The dataset is widely used for learning and demonstration purposes in data science and recommendation systems.

---

## Key Exploratory Insights

### General Rating Behavior
- Analysis of rating distribution and number of ratings per movie
- Identification of movies with high average and median ratings

### Demographic-Based Analysis
- **Children** gave more extreme ratings (1s and 5s), supporting Conjecture 2
- **Men over 30** tended to give slightly lower ratings than their younger counterparts
- **Women over 30** had higher median ratings for more movies than men of the same age group

### High-Rating Movies
- 21 movies had an average rating over 4.5
- 51 such movies among women; 23 among men
- Notable top-rated and most-rated movies included:
  - *American Beauty (1999)* – 3428 ratings
  - *Star Wars: Episode IV* – 2990 ratings
  - *Saving Private Ryan (1998)* – 2652 ratings

---

## Conjectures Explored

1. **Older people (age > 30)** are harder to please — do they give lower average ratings?
2. **Children (ages 1–10)** are more likely to give extreme ratings (1 or 5).
3. **Men’s ratings** reflect distinct genre preferences.
4. **Women’s ratings** show unique patterns and possible genre alignment.
5. **Age & Gender Interactions** – Can younger men predict younger women’s ratings more closely than older users?
6. **Gender Correlation** – Do men and women rate certain genres (like action or drama) similarly?

These hypotheses were tested through group-wise aggregation, correlation plots, and comparative rating distributions.

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Statistical aggregation and group-by operations
- Visualization of distributions and cross-demographic comparisons

---

## Business/Application Context

Understanding user behavior in the MovieLens dataset helps lay the groundwork for:
- **Recommendation Systems**
- **User segmentation and targeting**
- **Improved content curation strategies**

These techniques are transferable to platforms like Netflix, Prime Video, or Spotify, where tailored content is key to engagement and retention.

---

## Folder Structure

