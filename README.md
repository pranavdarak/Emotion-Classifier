
# Emotion Classifier App

## Overview

This Emotion Classifier App predicts the emotional content of text inputs. It utilizes a machine learning model trained to classify text into various emotions such as anger, disgust, fear, happiness, sadness, surprise, etc. The predictions are displayed along with their confidence levels, providing users with insights into the emotional tone of their input text.

## Features

- **Input Text Area:** Users can input text in the provided text area.
- **Prediction Display:** Displays the predicted emotion along with an emoji representation and confidence level.
- **Prediction Probability Visualization:** Visualizes the probability distribution of predicted emotions using a bar chart.

## Usage

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your_username/emotion-classifier-app.git
   ```

2. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app.
   ```bash
   streamlit run app.py
   ```

4. Input text in the provided text area and click on the "Submit" button to see the emotion prediction and probability visualization.

## Technologies Used

- Python
- Streamlit: For building the web application.
- Altair and Plotly Express: For data visualization.
- Joblib: For loading the trained machine learning model.

## Model Training

The emotion classifier model used in this app was trained on a labeled dataset containing text samples annotated with corresponding emotions. The training pipeline involved preprocessing the text data, extracting relevant features, and training a machine learning classifier (in this case, logistic regression). The trained model was then serialized using joblib for deployment.

## Author

- Pranav Darak (https://github.com/pranavdarak)

## Acknowledgments

- Inspired by the need to understand the emotional content of text for various applications such as sentiment analysis, customer feedback analysis, and more.

