

# Fake News Detection in Arabic

This project aims to construct a robust dataset for detecting fake news in Arabic. In addition to distinguishing articles as fake or real, each article is categorized by topic to provide a nuanced perspective on the dissemination of fake news across diverse subjects.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Annotation](#data-annotation)
- [Scraping Methodology](#scraping-methodology)
- [Future Work](#future-work)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview
The primary goal of this project is to create a robust dataset for detecting fake news in Arabic. By distinguishing articles as either fake or real and categorizing them by topic, this project aims to offer a comprehensive overview of fake news dissemination across different subjects.

## Data Collection
Arabic news articles are gathered from reputable fact-checking websites, such as [Fatabyyano](https://fatabyyano.net/), to ensure a mix of fake and authentic stories. The articles are collected across various topics, including politics, religion, health, and more.

## Data Annotation
Each article is classified as fake or real and sorted by topic. This categorization helps provide a better understanding of how fake news spreads across different subjects.

## Scraping Methodology
The data is scraped from fact-checking websites using Beautiful Soup, a Python library for web scraping. This method ensures efficient and targeted collection of data from the specified sources.

## Future Work
- Explore the use of Selenium as an alternative scraping method for dynamic content and interactive websites.
- Continue improving the dataset and updating the scraping techniques as necessary.

## Installation and Usage
To get started with this project, follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/hani464/fake-news-detection-arabic.git
    ```

2. Navigate to the project directory:
    ```bash
    cd fake-news-detection-arabic
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the scraping script:
    ```bash
    python scrape_data.py
    ```

5. Review the output data, which will be saved as a CSV file.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please open an issue or pull request. Be sure to follow the code of conduct and contribution guidelines.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements
We acknowledge the work of the fact-checking websites such as [Fatabyyano](https://fatabyyano.net/) for providing valuable data for this project.
