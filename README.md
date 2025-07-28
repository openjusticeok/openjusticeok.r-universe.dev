# OpenJustice Oklahoma R-universe

This is the R-universe for [OpenJustice Oklahoma](https://openjusticeok.org/), providing easy access to our collection of R packages for criminal justice data analysis and research.

## About R-universe

[R-universe](https://r-universe.dev/) is a platform that provides CRAN-like repositories for R packages, offering automated package builds and dependency management. This universe hosts OpenJustice Oklahoma's R packages, making them easily installable and discoverable.

## Installation

You can install packages from this universe using:

```r
# Enable this universe
options(repos = c(
  openjusticeok = 'https://openjusticeok.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'
))

# Install packages
install.packages('package_name')
```

## Included Packages

This universe contains the following R packages:

- **[ojoverse](https://github.com/openjusticeok/ojoverse)** - Meta-package that loads the core OpenJustice Oklahoma suite of packages
- **[ojodb](https://github.com/openjusticeok/ojodb)** - Database connection and query utilities for OpenJustice Oklahoma data
- **[ojoutils](https://github.com/openjusticeok/ojoutils)** - General utility functions for data analysis and processing
- **[ojoregex](https://github.com/openjusticeok/ojoregex)** - Regular expression patterns and utilities for parsing legal documents
- **[ojothemes](https://github.com/openjusticeok/ojothemes)** - ggplot2 themes and color palettes for OpenJustice Oklahoma visualizations
- **[ojoslackr](https://github.com/openjusticeok/ojoslackr)** - Slack integration utilities for notifications and reporting

## Learn More

- Visit [OpenJustice Oklahoma](https://openjusticeok.org/) to learn about our mission
- Browse packages at [openjusticeok.r-universe.dev](https://openjusticeok.r-universe.dev)
- View source code and contribute on [GitHub](https://github.com/openjusticeok)