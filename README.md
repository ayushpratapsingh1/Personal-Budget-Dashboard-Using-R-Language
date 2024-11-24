# Personal Budget Dashboard Using R Language

## Project Overview

The **Personal Budget Dashboard** project aims to help individuals track and manage their finances by providing an interactive dashboard built using R. It allows users to input income, expenses, and categorize them to monitor monthly budget trends. The dashboard visualizes spending habits, highlights areas for improvement, and tracks financial goals using various charts and graphs, making it easier for users to stay within their budget.

## Key Features
- **Income and Expense Tracking**: Allows users to input and track their income and expenses over time.
- **Budget Category Breakdown**: Categorizes expenses (e.g., groceries, utilities, entertainment) for better visualization.
- **Visualization**: Displays financial trends using bar charts, pie charts, and line graphs.
- **Monthly Comparison**: Compare current month spending with previous months to analyze spending patterns.
- **Goal Tracking**: Track savings and financial goals over time.

## Tech Stack
- **R**: For data manipulation, analysis, and dashboard creation.
- **shinydashboard**: For creating the interactive dashboard.
- **ggplot2**: For visualizations (bar charts, pie charts, line graphs).
- **dplyr**: For data preprocessing and manipulation.
- **lubridate**: For handling date-related functions.

## Setup Instructions

To set up and run the Personal Budget Dashboard locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/ayushpratapsingh1/Personal-Budget-Dashboard.git
    cd Personal-Budget-Dashboard
    ```

2. **Install Dependencies**: Ensure you have R installed and required libraries using the following commands:

    ```r
    install.packages(c("shinydashboard", "ggplot2", "dplyr", "lubridate"))
    ```

3. **Run the Dashboard**:

    Open the `app.R` file in RStudio or another R environment and run the script:

    ```r
    shiny::runApp('app.R')
    ```

    The dashboard will be accessible locally in your browser at `http://127.0.0.1:xxxx`.

## Features in Detail
- **Income and Expense Inputs**: Users can enter their income and expenses through text inputs.
- **Budget Visualization**: Interactive charts update as users add their data to display how much they’ve spent and where.
- **Spending Categorization**: Expenses are categorized for better insight into where money is going (e.g., food, rent, entertainment).
- **Monthly Comparison**: A line graph showing the comparison of expenses over multiple months.
- **Savings Goal Tracking**: Users can set savings goals and track their progress with visual feedback.

## How to Contribute
Contributions are welcome! Here's how you can help:
1. **Fork the repository**.
2. **Create a branch** for your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
3. **Commit your changes**:
    ```bash
    git commit -m 'Add feature or fix bug'
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature-name
    ```
5. **Submit a pull request**.

