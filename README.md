# Bayesian Hierarchical Models for School Data Analysis

This project explores the use of Bayesian hierarchical models to analyze math scores across U.S. schools. The hierarchical approach allows us to estimate both global and school-specific effects, which is particularly valuable when dealing with datasets that have imbalanced or sparse group data.

## Project Highlights
1. **Hierarchical Normal Model without Covariates**: Focuses on analyzing school-level math scores, capturing both within-school and between-school variability.
2. **Hierarchical Normal Model with Covariates**: Incorporates predictor variables to explore relationships within the data, providing more detailed insights.

## Methodology
Parameters are estimated using **Gibbs Sampling**, a Markov Chain Monte Carlo (MCMC) method that allows for the approximation of complex posterior distributions. This project employs standard semi-conjugate priors, following Hoff's (2009) approach to Bayesian methods.

## Goal
The aim is to estimate both global and school-specific effects, yielding insights into school performance across varying sample sizes.

**Reference**: Hoff, P. D. (2009). *A First Course in Bayesian Statistical Methods*. Springer Publishing.
