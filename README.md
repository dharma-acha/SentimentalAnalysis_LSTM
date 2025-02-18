
## Sentiment Analysis Using LSTM
### Overview
Sentiment analysis is a natural language processing (NLP) task that involves classifying text data into categories such as positive, negative, or neutral sentiment. In this project, we use Long Short-Term Memory (LSTM) networks to perform sentiment analysis on textual datasets. The goal is to achieve an accuracy of more than 75% for the final model.

### Dataset

* Twitter Airline Sentiment Dataset



### Steps


* **Read and Preprocess:** Load the dataset, clean the text data (e.g., remove special characters, convert to lowercase), and print main statistics (e.g., class distribution).

* **Visualization:** Create at least three visualizations (e.g., word clouds, sentiment distribution, most common words) using libraries like matplotlib, seaborn, or plotly.

* **Prepare Data:** Tokenize the text and convert it into numerical sequences. Split the dataset into training, testing, and validation sets.

### Build LSTM Model

* **Architecture:** Construct an LSTM model with at least three LSTM layers. You can use frameworks like TensorFlow or PyTorch.

* **Training:** Train the LSTM model with various setups and hyperparameters (e.g., learning rate, batch size). Save the model weights that yield the best results.
Report Performance: Report the accuracy and loss of the model. Visualize the training and validation loss/accuracy over epochs.

### Improve LSTM Model

**1. Alternative Architectures:** Experiment with improved versions of LSTM architectures, such as Gated Recurrent Unit (GRU), Bidirectional LSTM, or Stacked LSTM. In this project we used Bi-directional LSTM


**2. Training:** Train the improved model and fine-tune hyperparameters. Save the best-performing model weights.


### Data Preprocessing:

**Tokenization:** Convert text into tokens (words or subwords).
**Sequence Conversion:** Convert tokens into numerical sequences.
**Padding:** Ensure all sequences have the same length by padding.

### Model Building:

**Embedding Layer:** Maps words to dense vectors.

**LSTM Layers:** Capture sequential dependencies in the data.

**Dense Layer:** Outputs the final sentiment prediction.

### Training and Evaluation:

1. Use cross-entropy loss for binary or categorical classification.
2. Optimize using algorithms like Adam.
3. Evaluate using accuracy, precision, recall, and F1-score.

### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)
