# Introduction

## Purpose

A quarto-based static website used to hold guidance, helpful links and code examples for doing survey analysis in R. The source repository is hosted in GitHub and deployed via GitHub pages.

## Overview

The website is split up into multiple files:

-   **index.qmd:** Home page that includes introduction and user guide
-   **setting_up_workspace.qmd:** A guide on how to set up the workspace in R so users are able to run the code in this guide.
-   **reading_labelling_data.qmd:** A guide on how to read and label SPSS and CSV survey data.
-   **formatting_filtering.qmd:** A guide on how to format and filter survey data.
-   **freq_tables.qmd:** A guide on how to use custom functions to create frequency tables.
-   **crosstabs.qmd:** A guide on how to use custom functions to create cross tabulations.
-   **summary_tables_and_avgs.qmd:** A guide on how to use custom functions to create summary tables and weighted averages.
-   **testing_sig.qmd:** A guide on how to test for significance.
-   **testing_corr.qmd:** A guide on how to test for correlation.
-   **working_directory.qmd**: A guide on how to check and change working directory. 
-   **git.qmd**: A collection of resources on how to use Git. 
-   **custom_functions.qmd:** A reference page that lists all the custom functions used in the guide. It also includes a description of each function and its arguments along with examples of how to use it.
-   **help.qmd:** A page to provide users solutions for the most common issue they may encounter while using this guide. There is also guidance on how to approach issues not mentioned in the help page.

# Requirements

## Software requirements

-   R version 4.4 or higher

-   RStudio

-   [See getting started with Quarto](https://quarto.org/docs/get-started/)

## Access

## Skills and knowledge

-   Basic knowledge of [Quarto](https://quarto.org/docs/tools/rstudio.html) and [markdown](https://rmarkdown.rstudio.com/articles_intro.html)

-   Understanding of [Quarto websites](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html)

## Version control

-   Version control is managed through [renv](https://rstudio.github.io/renv/articles/renv.html).

-   To use renv for version control in this project follow these steps:

    -   Install the renv package by typing this in the console: `install.packages("renv")`
    -   Then type this in the console: `renv::restore()`
    -   Then type `y` in the console and press "Enter" on the keyboard

# Contribute

If you have suggestions for survey analysis in R guide, you can create an issue on GitHub or create your own branch with your suggested changes and raised a pull request.

## Creating an issue:

Use [this guide to help you create an issue on GitHub to raise your suggested changes](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-an-issue).

## Create your own branch and raise a pull request

-   [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
-   [Set up Git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git)
-   [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
-   [Collaborating with pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)
-   [Quarto Guide](https://r4ds.hadley.nz/quarto.html)

# Contact details

-   Statistics and development team: [Statistics.DEVELOPMENT\@education.gov.uk](mailto:Statistics.DEVELOPMENT@education.gov.uk)
