# Vignette-Random Forest

# README

> Vignette on implementing Random Forest using mushroom data; created as a class project for PSTAT197A in Fall 2023.

Contributors: Mindy Xu, Zoe Zhou, Amy Lyu, Jerry Huang

### Vignette Abstract

This vignette offers a comprehensive guide to implementing the Random Forest algorithm using R, a powerful and versatile tool for machine learning. Our guide begins with an introduction to the fundamental principles of the Random Forest algorithm, emphasizing its advantages in handling both classification and regression tasks. We explore the **`randomForest`** package in R, detailing installation, data preparation, model training, and parameter tuning to optimize performance. Additionally, we demonstrate the implementation of Random Forest using mushroom data. Through clear explanations and code examples, readers will gain hands-on experience and the necessary skills to effectively utilize Random Forest in R for their data analysis and predictive modeling needs.

### Repository Contents

This repository is structured to support the development and presentation of our project, which utilizes a vignette written in Quarto (**`qmd`**). Below is an overview of the main components of the directory structure:

-   **`data`**: This directory houses all datasets used in our project. There is only one dataset in this directory since the dataset that we obtained from kaggle is clean and doesn't need any processing.

    -   **`mushroom.csv`**: Contains the raw, unprocessed datasets as originally obtained.

-   **`scripts`**: This directory contains the R scripts used for data processing, analysis, and other computational tasks.

    -   **`drafts`**: Here, you will find draft versions of scripts or experimental code snippets that are under development or testing.

    -   **`vignette-script.R`**: This is the main script file used for the vignette, encapsulating key analyses and methods.

-   **`img`**: In this directory, we store image files used in the vignette or other documentation.

    -   **`fig1.png`**, **`fig2.png`**: These are specific figures (e.g., plots or diagrams) referenced in the vignette or other documentation materials.

-   **`vignette.qmd`**: The main Quarto markdown file for the vignette. It contains the source code and narrative text for the vignette, integrating explanations with code snippets and results.

-   **`vignette.html`**: This is the rendered HTML output of the Quarto markdown file, suitable for viewing in a web browser.

-   **`README.md`**: Provides an overview of the project, instructions for setup and usage, and other essential information for users or contributors. It's the first document viewers should read to understand what the project is about and how to navigate the repository.

### Reference List

R, S. E. (2023, October 26). *Understand random forest algorithms with examples (updated 2023)*. Analytics Vidhya. <https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/>

Finnstats. (2021, April 13). *Random Forest in R: R-bloggers*. R. <https://www.r-bloggers.com/2021/04/random-forest-in-r/>

*This structure is designed to keep the project organized and ensure that all components, from data to scripts to documentation, are easily accessible and understandable. Feel free to explore the directories for a more in-depth understanding of the project, and refer to **`README.md`** for additional guidance.*