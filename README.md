# SMS-Categorization-using-ML
## Introduction
This project aims to categorize SMS messages into different categories such as promotional, fraud, phishing, ham, and financial. The dataset used in this project contains 1800 SMS messages collected by myself.

## Objectives
- Categorize SMS messages into the predefined categories.
- Develop machine learning models to automate the categorization process.
- Evaluate the performance of different machine learning models.

## Dataset
The dataset used in this project contains 1800 SMS messages categorized into five categories: promotional, fraud, phishing, ham, and financial. Each SMS message is labeled with one of these categories.

## Project Components
- Data Collection: SMS messages were collected and labeled manually.
- Data Preprocessing: Text preprocessing techniques were applied to clean and tokenize the SMS messages.
- Model Development: Machine learning models including LSTM, Dense, and Bidirectional LSTM were developed to categorize SMS messages.
- Model Evaluation: Models were evaluated based on their validation loss and validation accuracy.
- Results Analysis: Results were analyzed to determine the best-performing model for SMS categorization.
  
## Results
### LSTM Model:
- Validation Loss: 0.086
- Validation Accuracy: 0.985
### Dense Model:
- Validation Loss: 0.200
- Validation Accuracy: 0.974
### Bidirectional LSTM Model:
- Validation Loss: 0.080
- Validation Accuracy: 0.981
### Based on the results, the Bidirectional LSTM model performed the best with the lowest validation loss and highest validation accuracy.

## Contributing
To contribute to this project, you're invited to fork the repository and then submit a pull request with your changes. We welcome both contributions and feedback. If you encounter any issues or have feature requests, please don't hesitate to open an issue on the repository.

