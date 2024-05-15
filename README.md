# Chatbot with Translation Functionality

## Introduction
This repository contains a chatbot implementation with translation functionality. The chatbot is trained on intents from a JSON file and utilizes the NLTK library for text preprocessing. The model is built using Keras Sequential API and trained using a neural network.

## Files
- `chatbot.ipynb`: This notebook contains the code for training the chatbot model and implementing the chatbot.
- `intents.json`: This JSON file contains the intents and patterns used for training the chatbot.
- `translation_functionality.ipynb`: This notebook integrates translation functionality into the chatbot application.

## Usage
1. **Training the Model**: Run the code in `chatbot.ipynb` to train the chatbot model using the intents from `intents.json`.
2. **Implementing the Chatbot**: Once the model is trained, run the code to implement the chatbot. Users can interact with the chatbot by inputting text messages.
3. **Translation Functionality**: If you want to enable translation functionality, run the code in `translation_functionality.ipynb`. This notebook integrates a translation API into the chatbot application, allowing the chatbot to translate its responses into different languages.

## Dependencies
- NLTK
- NumPy
- Keras
- TensorFlow
- JSON
- Pickle
- Translation API (integrated in `translation_functionality.ipynb`)

## Notes
- Make sure to install the required libraries and dependencies before running the notebooks.
- Ensure that the file paths for `intents.json` and any other files are correctly specified in the code.
