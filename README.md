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
- 21/03 - little progress
- 22/03 - no progress
- 23/03 - read 2 chapters
- 24/03 - wrote about correlation
- 25/03 - no progress
- 26/03 - no progress
- 27/03 - no progress
- 28/03 - studied some sql and read a little
- 29/03 - no progress
- 30/03 - reviewed correlation
- 31/03 - made a post about correlation
- 01/04 - read about probability
- 02/04 - read a little
- 03/04 - no progress
- 04/04 - read about the monty hall problem
- 05/04 - no progress
- 06/04 - no progress
- 10/04 - learned about some distributions
- 11/03 - will read
- 13/04 - read a little

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

### 4. Correlation and Regression

#### Correlation

- **Correlation** describes the strength and direction of a linear relationship between two numerical variables (features or attributes).
- It can be:
  - **Positive**: Both variables increase or decrease together.
  - **Negative**: One variable increases while the other decreases.
- The **correlation coefficient** (typically denoted as *r*) ranges from **-1 to 1**:
  - **+1.00**: Perfect positive correlation – both variables move together in exactly the same way.
  - **-1.00**: Perfect negative correlation – one variable increases exactly as the other decreases.
  - **0**: No linear correlation – there is no predictable linear relationship between the variables.

#### Properties of Correlation

- Correlation is **unitless** because it is based on **standardized values**, meaning the actual units of the variables do not affect the correlation value.
- To standardize a value:
  - Subtract the mean of the variable from the value.
  - Divide the result by the standard deviation.
  - This converts the value to a **z-score**, or standard unit.

#### Correlation Coefficient Formula

Let \( x \) and \( y \) be two variables with standardized values:

\[
r = \frac{1}{n} \sum_{i=1}^{n} z_{x_i} \cdot z_{y_i}
\]

Where:
- \( z_{x_i} = \frac{x_i - \bar{x}}{s_x} \) (standardized value of \( x \))
- \( z_{y_i} = \frac{y_i - \bar{y}}{s_y} \) (standardized value of \( y \))
- \( n \) is the number of observations
- The result is the **mean product of the paired standardized values**.


