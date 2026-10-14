# LSTM Next-Word Prediction

## Project Overview

This project uses a Long Short-Term Memory (LSTM) neural network to predict the next word in a sentence based on a text dataset.

## Technologies Used

* Python
* Google Colab
* TensorFlow and Keras
* NumPy
* Natural Language Processing (NLP)
* IPywidgets

## Project Workflow

1. Load and clean the text dataset.
2. Tokenize the text and build a vocabulary.
3. Generate input-target sequences.
4. Apply padding to the sequences.
5. Build and train an LSTM model.
6. Evaluate the model using Top-1 and Top-5 accuracy.
7. Display next-word suggestions through an interactive interface.

## Model Architecture

* Embedding Layer
* LSTM Layer
* Dropout Layer
* Dense Layer with Softmax Activation

## Initial Results

* Top-1 Accuracy: 11.67%
* Top-5 Accuracy: 27.16%

These are the initial results from the experiment. Actual performance depends on the dataset, model configuration, and evaluation method.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the required text dataset.
3. Run the notebook cells in order.
4. Train the model and evaluate its performance.
5. Use the interactive interface to test next-word predictions.

## Future Improvements

* Train using a larger and more diverse dataset.
* Tune model parameters and sequence length.
* Improve evaluation methodology.
* Experiment with alternative language models.
