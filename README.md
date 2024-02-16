# Behaviour-Simulation-Challenge
# nlp_adobe

# Tweet Likes Prediction

This repository contains code for predicting the number of likes on tweets based on various features such as content, date, username, inferred company, and image description. The prediction is made using a BERT-based regression model.

It also contains the code for content generation.

## Installation

### Prerequisites

- Python 3.x
- Hugging face

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/team79interiit/nlp.git
    cd tweet-likes-prediction
    ```

2. Download the pre-trained BERT model:

    - The code uses the `bert-base-uncased` model by default. You can change this in the code if needed.

3. Prepare the data:

    - Make sure to have the required training and testing datasets in the specified format.

## Usage

1. Training the Model:

    - Run the training script `BERT_Predictions.ipynb` to train the regression model.


2. Model Evaluation:

    - Evaluate the trained model using the testing dataset.

3. Prediction:

    - Use the trained model to predict likes on new data.


4. Results:

    - The predictions will be saved in a CSV file named `behavior_test_company_results.csv`.

## Additional Notes

- The code includes functionalities for data preprocessing, model training, evaluation, and prediction.
- Customize hyperparameters, model architecture, or preprocessing steps by modifying the respective sections in the code.
- Ensure the data for prediction follows the required format specified in the code comments.



