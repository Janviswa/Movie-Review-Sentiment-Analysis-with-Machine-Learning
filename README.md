# Movie Review Sentiment Analysis with ML - AICTE Internship Project

This project is part of a 6-week AICTE internship focused on Sentiment Analysis. The goal is to develop a machine learning model that classifies movie reviews as either positive or negative based on textual data.

## Features

- **Data Preprocessing**: Cleans text data, removes special characters, and converts text to lowercase.
- **Sentiment Labeling**: Classifies reviews based on IMDB ratings (>= 7 as positive, < 7 as negative).
- **Feature Extraction**: Uses TF-IDF vectorization for text representation.
- **Handling Imbalanced Data**: Utilizes SMOTE for oversampling minority classes when needed.
- **Machine Learning Model**: Implements a Random Forest classifier for sentiment prediction.
- **Model Evaluation**: Analyzes performance using accuracy, classification reports, and confusion matrices.
- **Visualization**: Generates word clouds and displays data distributions.
- **Model Persistence**: Saves trained models and vectorizers for future inference.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)

## Getting Started

Follow the instructions below to set up the project and run the models on your system.

### Prerequisites

- Python 3.8+
- pip package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   cd sentiment-analysis
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset by placing it in the `data/` directory. Ensure it matches the expected format.
2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
3. Train the machine learning model:
   ```bash
   python train.py
   ```
4. Evaluate the model and visualize results:
   ```bash
   python evaluate.py
   ```
5. Generate predictions for new data:
   ```bash
   python predict.py --input new_data.csv
   ```

## Dataset

The dataset used is the **IMDB Top 1000 Movies Dataset**, containing movie reviews and ratings. The dataset includes:

- **Overview**: Movie descriptions used as review texts.
- **IMDB Rating**: Used to classify sentiment labels.

## Models

This project supports various machine learning models, including:

- Random Forest Classifier
- Decision Trees
- Support Vector Machines (SVM)
- Gradient Boosting (XGBoost, LightGBM)

Hyperparameter tuning and model optimization are included to enhance accuracy.

## Results

Evaluation metrics used to assess model performance:

- Accuracy
- Precision
- Recall
- F1-score
- AUC-ROC

Visualization tools display confusion matrices, word clouds, and feature importance for better interpretation.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## Contact

For questions, feedback, or contributions, please contact Janani at jananiviswa05@gmail.com.
