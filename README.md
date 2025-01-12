# ChatGPT Review Analysis

ChatGPT Review Analysis is a comprehensive Python project aimed at understanding user sentiments towards ChatGPT. By analyzing user reviews, this project categorizes sentiments into positive, negative, and neutral, identifies frequently mentioned phrases, and visualizes the data to provide meaningful insights.

## Installation

To get started with the ChatGPT Review Analysis project, follow these steps:

1. Clone the repository from GitHub:

    ```bash
    git clone https://github.com/rajatgupta3121/Data_analysis_projects.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Data_analysis_projects
    ```

3. Install the required dependencies using [pip](https://pip.pypa.io/en/stable/):

    ```bash
    pip install -r requirements.txt
    ```

## Usage

This project utilizes a Jupyter Notebook for interactive analysis. Follow the steps below to run the analysis:

1. Open the Jupyter Notebook in your preferred environment:

    ```bash
    jupyter notebook Chatgpt_review_analysis.ipynb
    ```

2. Execute the cells in the notebook to perform the following tasks:
   - Load and preprocess the dataset.
   - Conduct sentiment analysis using the `TextBlob` library.
   - Visualize sentiment distribution using `Plotly`.
   - Extract and analyze common phrases from positive and negative reviews.
   - Identify and categorize common user issues.
   - Analyze sentiment trends over time.
   - Calculate the Net Promoter Score (NPS) based on user ratings.

## Features

The ChatGPT Review Analysis project offers the following features:

### Sentiment Analysis

- **Categorization**: Reviews are classified into positive, negative, and neutral sentiments based on their polarity.
- **Sentiment Distribution**: Visual representation of sentiment distribution using bar charts for an easy overview.

### Common Phrase Extraction

- **Positive Reviews**: Identification of frequent phrases in positive reviews to understand what users appreciate about ChatGPT.
- **Negative Reviews**: Extraction of common phrases from negative reviews to pinpoint areas of dissatisfaction.

### Problem Identification

- **User Issues**: Grouping of similar phrases into broader categories such as incorrect answers, app performance issues, user interface concerns, and more.

### Trend Analysis

- **Sentiment Trends**: Analysis of how user sentiments have changed over time, providing insights into ChatGPT's performance improvements or issues over different periods.

### Net Promoter Score (NPS)

- **NPS Calculation**: Calculation of the Net Promoter Score to gauge user loyalty and the likelihood of recommendations.

## Contributing

Contributions to the ChatGPT Review Analysis project are welcome. If you wish to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

For major changes, please open an issue first to discuss your ideas and ensure alignment with the project goals.

## Testing

To maintain code quality, please ensure that you update and run tests after making any changes. Automated testing scripts will be added in future updates to streamline this process.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/). Feel free to use, modify, and distribute this project in accordance with the license terms.

---

By providing valuable insights into user feedback, the ChatGPT Review Analysis project helps improve the overall user experience, making it a crucial tool for continuous improvement. Happy analyzing!
