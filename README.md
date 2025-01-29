# Movie Review Sentiment Analysis with Machine Learning - AICTE Internship Project

This project is part of a 6-week AICTE internship focused on Sentiment Analysis. The goal is to develop a machine learning model that classifies movie reviews as either positive or negative based on textual data.

## Features

- **Data Preprocessing**: Clean and prepare textual data by removing noise and tokenizing.
- **Exploratory Data Analysis (EDA)**: Analyze word frequency, sentiment distribution, and feature correlations.
- **Machine Learning Models**: Implement classifiers such as Random Forest, Naive Bayes, and Deep Learning models.
- **Evaluation Metrics**: Assess model performance using accuracy, precision, recall, F1-score, and confusion matrix.
- **Visualization**: Display classification results and model insights with charts and graphs.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [Contact Information](#contact-information)

## Getting Started

Follow the instructions below to set up the project and run sentiment analysis models on your system.

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

3. Train the machine learning models:

   ```bash
   python train.py
   ```

4. Evaluate the models and visualize results:

   ```bash
   python evaluate.py
   ```

5. Generate predictions for new data:

   ```bash
   python predict.py --input new_data.csv
   ```

## Dataset

Supported dataset:

- **IMDB Reviews**: Sentiment-labeled dataset for movie reviews analysis.

## Models

This project supports various machine learning models, including but not limited to:

- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks

Hyperparameter tuning and optimization are included to enhance accuracy.

## Results

Evaluation metrics used to assess model performance:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Visualization tools display sentiment trends and model evaluation.

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

## Contact Information

For questions, feedback, or contributions, please contact Janani at jananiviswa05@gmail.com.

