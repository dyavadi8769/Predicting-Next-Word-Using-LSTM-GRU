# Predicting-Next-Word-Using-LSTM-GRU


### Project Description: Next Word Prediction Using LSTM

#### Project Overview:

This project aims to develop a deep learning model for predicting the next word in a given sequence of words. The model is built using Long Short-Term Memory (LSTM) networks, which are well-suited for sequence prediction tasks. The project includes the following steps:

1. **Data Collection:** We use the text of Shakespeare's "Hamlet" as our dataset. This rich, complex text provides a good challenge for our model.

2. **Data Preprocessing:** The text data is tokenized, converted into sequences, and padded to ensure uniform input lengths. The sequences are then split into training and testing sets.

3.  **Model Building:** An LSTM model is constructed with an embedding layer, two LSTM layers, and a dense output layer with a softmax activation function to predict the probability of the next word.

4. **Model Training:** The model is trained using the prepared sequences, with early stopping implemented to prevent overfitting. Early stopping monitors the validation loss and stops training when the loss stops improving.

5.  **Model Evaluation:** The model is evaluated using a set of example sentences to test its ability to predict the next word accurately.

6. **Deployment:** A Streamlit web application is developed to allow users to input a sequence of words and get the predicted next word in real-time.


## Commands to Setup Project on Local Machine

1. *Clone the repository:*

   ```bash
   git clone https://github.com/dyavadi8769/Predicting-Next-Word-Using-LSTM-GRU.git
   cd Predicting-Next-Word-Using-LSTM-GR

2.  **Create a virtual environment and activate it:**
    ```bash
    conda create -p env python==3.11 -y
    conda activate env/ 

3.  *Install the Required Dependecies:*
    ```bash
    pip install -r requirements.txt

## Contributing

1. Contributions are welcome! Please fork the repository and create a pull request with your changes. 
2. Ensure that your code adheres to the project's coding standards.