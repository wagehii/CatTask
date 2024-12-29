# Statistics Fundamentals

## 1. Mean, Median, and Mode

- **Mean**: The arithmetic average of a dataset, calculated by summing all values and dividing by the number of values.
  - **Example**: In a business, the mean salary of employees helps the HR department understand the overall payroll expense.
- **Median**: The middle value of a dataset when arranged in order. It divides the data into two equal halves.
  - **Example**: When evaluating house prices, the median is better than the mean to represent central tendency if some houses are extremely expensive.
- **Mode**: The most frequently occurring value in a dataset.
  - **Example**: In retail, the mode of shoe sizes helps identify the most commonly sold size.

---

## 2. Variance and Standard Deviation

- **Variance**: Measures the average squared deviation of each data point from the mean, indicating how spread out the data is.
- **Standard Deviation**: The square root of the variance. It gives a measure of spread in the same units as the data.
- **Relationship**: Standard deviation is the square root of variance, making it more interpretable in terms of the original data scale.
  - **Formula**:  
    - Variance (\(\sigma^2\)) = \(\frac{\sum (x_i - \mu)^2}{N}\)  
    - Standard Deviation (\(\sigma\)) = \(\sqrt{\sigma^2}\)

---

## 3. Left and Right Skewness

- **Left Skewness (Negative Skew)**:
  - Tail is longer on the left side.
  - Order: Mean < Median < Mode.
  - **Example**: Age of retirement in a country where most people retire around the same age, but a few retire very early.
- **Right Skewness (Positive Skew)**:
  - Tail is longer on the right side.
  - Order: Mode < Median < Mean.
  - **Example**: Income distribution where a small percentage of people earn significantly more than the majority.

---

## 4. Outliers

- **Definition**: Data points that are significantly different from the majority of the data.
  - **Effects**:
    - Skew mean.
    - Increase standard deviation.
    - Often don’t affect median or mode.
  - **Real-world Example**: A student scoring 100 in a class where most scores are between 60 and 80.

---

## 5. Population vs. Sample

- **Population**: Entire set of data points or subjects of interest.
  - **Example**: All students in a country.
- **Sample**: A subset of the population used to make inferences about the population.
  - **Example**: 500 students selected randomly from a country.
- **Measurements**:
  - Mean, median, and mode are calculated for both.
  - Notation differences:
    - Population mean: \(\mu\), sample mean: \(\bar{x}\).
    - Population variance: \(\sigma^2\), sample variance: \(s^2\).

---

## 6. Discrete vs. Continuous Random Variables

- **Discrete**: Takes specific, countable values.
  - **Example**: Number of cars sold by a dealership in a day.
- **Continuous**: Can take any value within a range.
  - **Example**: Weight of a randomly selected apple.

---

## 7. Probability Mass Function (PMF) vs. Probability Density Function (PDF)

- **PMF**:
  - Used for discrete random variables.
  - Gives the probability of a random variable being exactly equal to a specific value.
  - **Example**: \(P(X = 3)\) for a dice roll.
- **PDF**:
  - Used for continuous random variables.
  - Represents the density of probability at a specific point; probabilities are obtained over intervals.
  - **Example**: \(P(a \leq X \leq b)\) for the height of people in a population.

---

## 8. Normal Distribution and Standard Deviations

- In a normal distribution:
  - Approximately **68%** of data falls within **1 standard deviation** of the mean.
  - Approximately **95%** of data falls within **2 standard deviations** of the mean.
  - Approximately **99.7%** of data falls within **3 standard deviations** of the mean.
