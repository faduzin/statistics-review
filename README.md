# Statistics Review

## Log
- 03/03 - no progress
- 04/03 - no progress but tomorrow I'll pick up the pace
- 05/03 - little progress, but it is a start
- 06/03 - learned some basic concepts by watching Teo Calvo and reading Naked Statistics
- 07/03 - added yesterday notes
- 08/03 - no progress
- 09/03 - no progress but this next week will be focused on this project
- 10/03 - little progress
- 11/03 - using a new book calles introduction to statistical learning with python
- 12/03 - little progress
- 13/03 - little progress, participated in an not related event
- 14/03 - no progress
- 15/03 - learned about variance and standard deviation
- 16/03 - read 10 pages of the book naked statistics
- 17/03 - little progress
- 18/03 - wrote about standard deviation, mean and median
- 19/03 - no progress
- 20/03 - reviewed notes

## Introduction
This document serves as a structured review of key statistical concepts essential for data analysis and data science. Each section will be filled with notes, definitions, examples, and insights as I progress through my studies. The goal is to build a strong foundation in statistics to enhance analytical and problem-solving skills.

## Topics Covered

### 1. Introduction to Statistics

#### What is Statistics?
- **Data** is the raw material of knowledge.
- **Statistics** is a set of tools used to calculate, summarize, and understand data.
- Statistics helps process data, ranging from trivial cases (e.g., sports statistics) to profound insights (e.g., the Gini index, which measures income inequality).
- It is one of the most powerful tools for transforming information into meaningful conclusions.

#### The Role and Limitations of Statistics
- **Descriptive statistics** exist to simplify data, but simplification always implies some loss of nuance or detail.
- Overreliance on any single descriptive statistic can lead to misleading conclusions.
- Statistics are present in every profession and are applied in various fields, such as research, finance, polling, healthcare, and technology.
- Most phenomena can be described in multiple ways, and the choice of descriptive statistics profoundly impacts the impression conveyed.
- Even precise and accurate descriptive statistics can suffer from a fundamental issue: lack of clarity about what exactly is being defined, described, or explained.

### 2. Populations, Samples, and Statistical Inference

#### Key Definitions
- **Population**: The entire set of individuals or elements under study, defined by specific rules or filters.
- **Sample**: A subset of the population selected for analysis.
- **Inference**: The process of using sample data to draw conclusions about the population.
- **Unit of analysis**: The entity being studied, compared, or described by statistics.

#### The Importance of Sampling
- In most cases, studying the entire population is impractical or impossible.
- **Random Sampling**: A sampling method where all members of the population have an equal chance of being selected.
- A sample should be **representative** and **unbiased** to provide accurate inferences.
- However, it is impossible to absolutely guarantee that a selected sample is perfectly representative or free of bias.

#### Parameters vs. Estimators
- **True Value (Parameter)**: The actual value that describes a characteristic of the population.
- **Estimated Value (Estimator)**: The value calculated from the sample, which serves as an approximation of the parameter.
- Precision and accuracy play crucial roles in estimation:
  - **Precision** is the exactness or detail with which an estimate can be expressed.
  - **Accuracy** indicates how close an estimate is to the true value.
  - Precision can mask inaccuracy by giving a false sense of certainty; thus, even precise estimates should be checked against common sense.

#### Trust in Statistical Inference
- **Confidence (Trust) is never 100%**, as there is always uncertainty in sampling.
- Confidence levels express the probability that the chosen sample accurately represents the population.
- Honest motivation is critical because valid data can still be used to support misleading or disputable conclusions if motivation is biased.

### 3. Measures of Central Tendency and Dispersion

#### Central Tendency
- **Mean** and **median** are both measures of central tendency.
  - **Mean** is the arithmetic average (the sum of values divided by the number of values).
  - **Median** is the midpoint of the distribution (the value separating the upper half from the lower half of the data).
- The discrepancy between mean and median indicates how the data distribution is skewed.

#### Dispersion
- **Variance** measures how spread out the data points are around the mean. It is calculated as the sum of squared differences between each term and the mean, divided by the number of terms.
- **Standard deviation** is the square root of variance, reflecting average distance of data points from the mean.
