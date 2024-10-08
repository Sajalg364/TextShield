# TextShield

## Overview
**TextShield** is a machine learning-powered tool designed to detect and censor abusive language in real-time. It uses predictive models to classify sentences as hate speech or not and replaces abusive words with stars to maintain respectful communication.

## Features
- **Abusive Language Detection**: Identifies if a sentence contains hate speech.
- **Censorship**: Replaces abusive words with stars to ensure polite communication.

## Files
- `abuse_detect.csv`: Contains sentences with labels indicating whether they are hate speech or not.
- `abusive_words.csv`: Contains a list of abusive words used for star marking in detected hate speech sentences.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- NLTK
- keras

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/TextShield.git
    cd TextShield
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

- Load data
  data = pd.read_csv('abuse_detect.csv')

- Split data

- Train model

- Predict and evaluate

- Detect and Star Mark Abusive Words