# Distribution Toolbox

An interactive web application for exploring probability distributions through numerical calculations, visualizations, and statistical approximations.

## Open the application

<a href="https://dt-magentakoncept.pythonanywhere.com/" target="_blank" rel="noopener noreferrer"><strong>Launch Distribution Toolbox</strong></a>

To keep this GitHub page open, Command-click (macOS) or Ctrl-click (Windows/Linux) the link to open the application in a new tab.

The application is hosted online and opens as a standalone web app.

## About

Distribution Toolbox provides an interactive interface for working with common probability distributions. Users can:

- Calculate probability density and mass values.
- Calculate cumulative and survival probabilities.
- Compute means, variances, standard deviations, skewness, and kurtosis.
- Calculate quartiles and custom quantiles.
- Visualize probability density, mass, and cumulative distribution functions.
- Explore normal, Poisson, Binomial, and Hypergeometric approximations where appropriate.
- Experiment with distribution parameters through validated interactive controls.

## Available distributions

### Continuous distributions

- Beta
- Chi-Square
- Exponential
- Gamma
- Generalized Extreme Value
- Logistic
- Lognormal
- Normal
- Pareto
- Uniform
- Weibull

### Discrete distributions

- Binomial
- Geometric
- Hypergeometric
- Negative Binomial
- Poisson
- Discrete Uniform

## Documentation

The application includes a formulary with parameter definitions, formulas, and distribution information:

[**Open the Distribution Toolbox Formulary**](https://dt-magentakoncept.pythonanywhere.com/static/docs/Distribution_Toolbox_Formulary.pdf)

## Approximation support

Depending on the distribution parameters, the application may display:

- Normal approximations for Binomial distributions.
- Poisson approximations for Binomial distributions.
- Binomial approximations for Hypergeometric distributions.
- Poisson approximations for Hypergeometric distributions.
- Normal approximations for Chi-Square distributions.

Approximation panels are shown only when the configured validity conditions are satisfied.

## Ownership and implementation

This repository is a public presentation repository for the deployed Distribution Toolbox application.

The application source code and implementation repository are maintained separately and are not included here.

## License

Copyright © 2026 MagentaKoncept. All rights reserved.