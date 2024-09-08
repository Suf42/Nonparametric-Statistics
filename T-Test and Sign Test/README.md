# T-Test and Sign Test

In short, we use the t-test to compare means across sample(s) and the sign test to compare medians across sample(s).

## Comparison

### T-Test
- determines whether there is a **mean** difference between paired samples or tests the **mean** of a single sample against a null hypothesis
- **parametric**, assumes data distribution follows a normal distribution
- use cases:
    * compare means of two independent samples (independent t-test)
    * compare mean of a sample against a specific value (one-sample t-test)
    * compare means of a sample measured before and after a treatment (paired t-test)

### Sign Test
- determines whether there is a **median** difference between paired samples or tests the **median** of a single sample against a null hypothesis
- **nonparametric**, assumes data distribution is continuous at best
- use cases:
    * compare median of a sample against a specific value
    * compare medians of two related samples
