# An Accessible Introduction to Multi-level (or Mixed Effects) Models

This repository currently serves as a place for brainstorming about a book for [Ed Tech Books](https://edtechbooks.org/).

## Applications

- network data, with relations nested in groups
- repeated measures within groups
- longitudinal data within groups
- individuals nested in high-level groups (statistically the same as repeated measures within units, but conceptually different)

## Principles

- Multi-level models are *just regressions*, with one important difference: effects associated with groups are weighted (or "regularized") by how much information there is for the effect for each specific group
- See what difference a multi-level approach makes (compare multi-level models to linear model alternatives)
- Thinking creatively and flexibly about the structure of data (groups are not only those due to the nesting of individuals)
- Recognize that every little bit (of data) counts (multi-level models can handle different amounts of information for each group)
- Use modern, freely-available, and open-source software
- Connect to powerful ideas about Bayesian methods of inference

## Ideas for Datasets

- Toddlers
- Fruits
- Reviews on review websites
- Relations *between* students in a class

## Resources

- [Data Science-ish](https://github.com/jrosen48/data-science-ish)
- [Multiple Uses for Multi-Level Models](https://joshuamrosenberg.com/posts/multiple-uses-for-multi-level-models-examples-from-recent-research/)
- [Comparing estimates and their standard errors from mixed effects and linear models
](https://joshuamrosenberg.com/posts/comparing-mixed-effects-and-linear-models/)
- [Finding the top rail-trails in each state using mixed effects models](https://joshuamrosenberg.com/posts/find-the-top-rail-trails-in-each-state/)
- [Explorations in Markov Chain Monte Carlo - comparing results from MCMCglmm and lme4](https://joshuamrosenberg.com/posts/explorations-in-markov-chain-monte-carlo-mcmc/)

## Chapters

### Background

1. Which product should I buy? Developing an intuition for how multi-level models work
2. A buffet of groups: How multi-level models can be used for a variety of data types
3. Introduction to running a multi-level model in R (using the lme4 package)
4. How estimates and their standard errors change: How results from multi-level models differ from those from regression models

### Applications

#### Foundational Applications

5. A two-level model for cases nested within groups
6. A two-level model for repeated measures of observations within groups
7. A three-level model for cases nested within groups nested within higher-level groups

#### Extending Multi-level Models

8. Random slopes for effects of interest
9. Longitudinal analyses
10. Arbitrary numbers of groups

#### Cross-classification

11. Cross-classified network data
12. Cross-classified ESM data
13. Cross-classification within educational games

### Extensions

14. Modeling variability using intra-class correlations
15. "Keep it maximal?": What should be a random effect
16. Arbitrary numbers of groups
17. MCMC estimation and Bayesian methods

### Appendix

- Primer on core statistical concepts
- Primer on RStudio, R, and RMarkdown
- Primer on the tidyverse set of R packages
