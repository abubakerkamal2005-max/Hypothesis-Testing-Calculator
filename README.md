# Hypothesis Testing Calculator

An interactive, step-by-step calculator for statistical hypothesis testing and confidence intervals.
It is a single HTML file with no dependencies: no installation, no build step, and no internet connection required.

## Quick start

1. Download `hypothesis-testing-calculator.html`.
2. Open it in any modern browser.

To host it with GitHub Pages, rename the file to `index.html` and enable Pages in the repository settings.

## Features

- **Z and T tests for one population mean** (right-, left-, and two-tailed)
- **Tests for two population means:** known variances, pooled variance, and Welch's method
- **Confidence intervals** for one mean and for the difference between two means
- **P-value method** from a test statistic or from raw inputs
- **Summary statistics or raw data** input
- **Distribution graphs** showing the rejection region and the test statistic
- **Two modes:** *Learning* shows every step; *Calculator* shows only the essentials
- **Adjustable decimal precision** (2, 3, 4, or 6 decimals)
- **Hypothesis builder** and **"Which test should I use?"** helper
- **Glossary** and **formula reference** with worked examples
- **Results report** that can be printed or copied as text
- **Built-in examples** with hypothetical data for every calculator

## How each test is carried out

Every test follows the same five steps:

1. State H₀ and H₁
2. Compute the test statistic
3. Find the critical value / rejection region (or the P-value)
4. Make the decision
5. Write the conclusion

## Notes

- Welch–Satterthwaite degrees of freedom are rounded **down** to the nearest integer.
- The confidence interval method is equivalent to a hypothesis test for **two-tailed** tests only.
- Distribution functions (normal and Student's t) are implemented in plain JavaScript, so results are accurate to roughly 6–7 decimal places.
- All example data in the app is invented for illustration.

## Project structure

```
hypothesis-testing-calculator.html   # the whole app: HTML, CSS, and JavaScript

