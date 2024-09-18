# A/B Testing with Cookie Cats
![image](https://github.com/user-attachments/assets/15a36464-5f89-4c94-b511-1f4ae48f1ff7)

## Overview
Cookie Cats is a popular mobile game where players engage in various levels to earn points and advance through the game. Understanding player retention and engagement is crucial for optimizing game features and improving user experience. This project focuses on analyzing retention rates and the number of game rounds played by users to determine if there are significant differences between two different game versions (`gate_30` and `gate_40`).

## Methodology
To evaluate the performance of different game versions, we performed statistical significance testing to compare user retention rates and the number of game rounds between two groups:

- Gate 30: Version 30 of the game.
- Gate 40: Version 40 of the game.
We applied hypothesis testing to assess whether the differences observed in player retention rates and the number of game rounds are statistically significant. For each feature that we are assessing, we will determine the type of data and choose the appropriate statistical test to complete our tasks.

## Hypotheses

### Retention Rate after Day 1
- Null Hypothesis (H0): The proportion of retained users after Day 1 is the same for Gate 30 and Gate 40.
- Alternative Hypothesis (H1): The proportion of retained users after Day 1 differs between Gate 30 and Gate 40.

### Retention Rate after Day 7
- Null Hypothesis (H0): The proportion of retained users after Day 7 is the same for Gate 30 and Gate 40.
- Alternative Hypothesis (H1): The proportion of retained users after Day 7 differs between Gate 30 and Gate 40.

### Number of Game Rounds
- Null Hypothesis (H0): The average number of game rounds played is the same for Gate 30 and Gate 40.
- Alternative Hypothesis (H1): The average number of game rounds played differs between Gate 30 and Gate 40.

## Data Preprocessing
The dataset used for this analysis includes the following columns:

- `userid`: Unique identifier for each user.
- `version`: The game version used by the user (`gate_30` or `gate_40`).
- `sum_gamerounds`: Total number of game rounds played by the user.
- `retention_1`: Retention status after Day 1 (True/False).
- `retention_7`: Retention status after Day 7 (True/False).

The data was cleaned and transformed as follows:

- Filtered the dataset to include only relevant records for Gate 30 and Gate 40.
- Calculated retention rates and average number of game rounds for each version.
- Prepared data for statistical tests by aggregating counts and proportions.

## Test the Hypotheses and Conclusion
After all the data have been processed, we're ready to perform appropriate statistical tests for each hypothesis and conclude our result, whether it's statistically or practically significant. Finally, we will use those results to come up with recommendations to enhance player retention on the Cookie Cats game.
