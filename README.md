
# The OpenData Package Developer’s Guide

The **OpenData Package Developer’s Guide** is a step-by-step handbook
for creating R packages that provide convenient access to
Socrata-powered Open Data portals.

Originally developed from the architecture behind **nycOpenData**, this
guide walks developers through adapting the framework to new cities,
documenting functions, testing packages, building pkgdown websites, and
preparing packages for CRAN.

## What You’ll Learn

This guide covers:

- Creating a new R package
- Connecting your project to GitHub
- Customizing the OpenData template
- Working with the core package functions
  - `city_list_datasets()`
  - `city_pull_dataset()`
  - `city_any_dataset()`
  - `utils_request.R`
- Building documentation and vignettes
- Creating a pkgdown website
- Preparing a package for CRAN submission

The appendices also include complete template files that can be copied
directly into a new package, making it possible to build an OpenData
package without starting from scratch.

## Read the Guide

The complete guide is available online at:

**<https://YOUR-BOOK-URL>**

## OpenData Ecosystem

This guide accompanies a growing ecosystem of OpenData packages,
including:

- **nycOpenData**
- **nysOpenData**
- **chiOpenData**
- **laOpenData**
- **mtaOpenData**

Additional city packages are currently under development.

## Contributing

Suggestions, corrections, and improvements are welcome. Please open an
issue or submit a pull request if you find an error or would like to
improve the guide.

## Author

**Christian Martinez**

Brooklyn College, City University of New York (CUNY)

Developer of the OpenData package framework and the `nycOpenData`
package.
