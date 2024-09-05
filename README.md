## Book Text Prediction Using LSTM

## Project Description

This project uses an LSTM (Long Short-Term Memory) neural network to predict the next word in a sequence of text from a book. The model is trained on a dataset containing a large amount of text, allowing it to learn patterns, grammar, and context to predict subsequent words.

## Steps in the Project

1. **Load Data and Libraries**: Load necessary Python libraries and the text dataset.
2. **Clean the Data**: Perform data cleaning to remove unwanted characters, punctuation, and format the text properly.
3. **Tokenize the Data**: Split the text into tokens (words) for processing.
4. **Convert to Sequences**: Convert the tokens into sequences suitable for input to the LSTM model.
5. **Create Input and Output Sequences**: Define the input and output sequences used for training.
6. **Build the Sequential Model**: Construct a sequential model with LSTM layers.
7. **Compile the Model**: Configure the model with an optimizer, loss function, and metrics.
8. **Fit the Model**: Train the model on the input data.
9. **Evaluate the Model**: Assess the model's performance and adjust parameters as necessary.

## Installation and Usage

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
3. Run the notebook using Jupyter:
    ```sh
    jupyter notebook Book_Text_prediction_using_LSTM.ipynb
    ```

## Dataset

The dataset used for training the LSTM model is a text file from a book. It is fetched from a public repository:
- **URL**: [Text Dataset](https://raw.githubusercontent.com/insaid2018/DeepLearning/master/Data/republic_clean.txt?_sm_au_=iVV10f0f2kPt2J07)

## Model Architecture

- **Embedding Layer**: Converts words into vectors of fixed size.
- **LSTM Layer**: Long Short-Term Memory network to capture sequence dependencies.
- **Dropout Layer**: Regularization to prevent overfitting.
- **Dense Layer**: Fully connected layer for final output.

## Results

The trained model can predict the next word in a sequence with reasonable accuracy, and its performance improves with more epochs and larger datasets.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
