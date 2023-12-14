# Vignette-Random Forest

# README

> Vignette on implementing Random Forest using [hotel reservation data](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset/code); created as a class project for PSTAT197A in Fall 2023.

Contributors: Mindy Xu, Zoe Zhou, Amy Lyu, Jiashu Huang

### Vignette Abstract

This vignette offers a comprehensive guide to implementing the Random Forest algorithm using R, a powerful and versatile tool for machine learning. Our guide begins with an introduction to the fundamental principles of the Random Forest algorithm, emphasizing its advantages in handling both classification and regression tasks. We explore random forest models through **`parsnip`** and **`tidymodels`** packages in R, detailing installation, data preparation, model training, and parameter tuning to optimize performance. Additionally, we demonstrate the implementation of Random Forest using [hotel reservation data](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset/code). Through clear explanations and code examples, readers will gain hands-on experience and the necessary skills to effectively utilize Random Forest in R for their data analysis and predictive modeling needs.

### Repository Contents

This repository is structured to support the development and presentation of our project, which utilizes a vignette written in Quarto (**`qmd`**). Below is an overview of the main components of the directory structure:

-   **`data`**: This directory houses all datasets used in our project. There is only one dataset in this directory since the dataset that we obtained from kaggle is clean and doesn't need any processing.

    -   **`HotelReservations.csv`**: Contains the raw, unprocessed datasets as originally obtained.

-   **`scripts`**: This directory contains the R scripts used for data processing, analysis, and other computational tasks.

    -   **`drafts`**: Here, you will find draft versions of scripts or experimental code snippets that are under development or testing.

    -   **`vignette-script.R`**: This is the main script file used for the vignette, encapsulating key analyses and methods.

-   **`image`**: In this directory, we store image files used in the vignette or other documentation.

    -   **`img-rfsimplified.png`**, **`img-decisiontree.png`**: These are specific figures (e.g., plots or diagrams) referenced in the vignette or other documentation materials.

-   **`vignette.qmd`**: This is the main Quarto markdown file for the vignette. It contains the source code and narrative text for the vignette, integrating explanations with code snippets and results.

-   **`vignette.html`**: This is the rendered HTML output of the Quarto markdown file, suitable for viewing in a web browser.

-   **`README.md`**: This provides an overview of the project, instructions for setup and usage, and other essential information for users or contributors. It's the first document viewers should read to understand what the project is about and how to navigate the repository.

### Reference List

Sruthi E R (2023, October 26). *Understand random forest algorithms with examples (updated 2023)*. Analytics Vidhya. <https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/>

Manish Saraswat (2023). *Practical Tutorial on Random Forest and Parameter Tuning in R* . R <https://www.hackerearth.com/practice/machine-learning/machine-learning-algorithms/tutorial-random-forest-parameter-tuning-r/tutorial/>
