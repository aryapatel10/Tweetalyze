# Tweetalyze
A sentiment analysis project that uses Twitter data to assess public sentiments through Natural Language Processing (NLP). It features text cleaning, feature extraction, and data visualization, employing a Random Forest classifier to accurately classify tweet sentiments. Gain insights into Twitter trends with this comprehensive analysis tool.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Data Visualization](#data-visualization)
- [Data Cleaning](#data-cleaning)
- [Model Building](#model-building)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with Tweetalyze, clone the repository and install the required dependencies:

```bash
git clone https://github.com/aryapatel10/Tweetalyze.git
cd Tweetalyze
pip install -r requirements.txt
python -m spacy download en_core_web_sm
pip install beautifulsoup4 textblob wordcloud
pip install git+https://github.com/laxmimerit/preprocess_kgptalkie.git --upgrade --force-reinstall
```

## Usage

To run the project, execute the following command in your terminal: 
```bash
python app.py
```

## Features

+ Data Loading: Loads Twitter sentiment data for analysis.
+ Feature Extraction: Extracts basic features from tweet text.
+ Data Visualization: Creates histograms, pie charts, and word clouds to visualize sentiment distribution.
+ Data Cleaning: Cleans tweet text by removing URLs, HTML tags, special characters, and retweets.
+ Model Building: Builds a Random Forest classifier for sentiment analysis.
+ Model Evaluation: Evaluates model performance using classification metrics.

## Data Visualization
The project includes several visualizations, such as:

- Histograms for numerical features
- Pie charts to show sentiment distribution
- Word clouds representing the most common words in each sentiment category

  
## Data Cleaning
The text data is preprocessed to ensure accurate sentiment analysis by:

- Converting text to lowercase
Removing URLs, HTML tags, special characters, and retweets

## Model Building
The project uses a Random Forest classifier to perform sentiment analysis on the cleaned text data. The model is evaluated using a classification report that includes precision, recall, and F1-score.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or suggestions.

## LICENSE
This project is licensed under the MIT [LICENSE](https://github.com/aryapatel10/Tweetalyze/blob/main/LICENSE ) - see the LICENSE file for details.
