# Introduction

There are 3 types of statistical models:
- parametric models
- nonparametric models
- semiparametric models

## Types of Models

### Parametric models
- make strong underlying assumptions regarding data distribution defined by a finite number of **parameters**
- for example, X ~ N($\mu$, ${\sigma}^{2}$)
- $\mu$ and $\sigma$ are parameters, hence the normal distribution above is a parametric model

### Nonparametric models
- make minimal assumptions about the underlying data distribution
- for example, we may just assume that X is continuous and symmetric (data is distributed evenly about the median)

### Semiparametric models
- has a finite-dimensional component (parametric)
- has an infinite-dimensional component (nonparametric)

## Implications

- parametric models perform better than nonparametric models **IF** the underlying assumptions made about the distribution are correct
- but in general perform worse if no such assumptions can be made
