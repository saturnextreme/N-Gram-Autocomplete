# N-Gram Autocomplete

This repository contains a Python implementation of an N-gram autocomplete system. The system suggests completions for partially typed words based on the analysis of historical text data. Notably, no external libraries were utilized, keeping the implementation lightweight and self-contained.

## Features:
- **N-gram Analysis**: Tokenizes and preprocesses input text data, generating n-grams to capture word sequences.
- **Stopword Removal**: Eliminates common stopwords to improve prediction accuracy and efficiency.
- **Confusion Matrix Construction**: Constructs a confusion matrix to analyze the frequency of word sequences and predict the next word.
- **Autocomplete Suggestions**: Predicts and suggests the next word based on the probability distribution generated from the confusion matrix.

## Usage:
```bash
# Ensure you have Python installed on your system.
# Clone this repository to your local machine.
# Navigate to the repository directory.
# Run the `autocomplete.py` script with Python.
python autocomplete.py
```

## Note:
# This implementation relies solely on Python's built-in functionalities, with no external libraries required.
# Input text data can be customized for specific applications or domains.
