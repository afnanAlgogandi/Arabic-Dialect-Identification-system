# Arabic Dialect Identification System

## CCAI-413: Natural Language Processing Project

This repository contains code for an Arabic Dialect Identification system, a project developed as part of the CCAI-413 Natural Language Processing course. The system is designed to identify the dialect of the Arabic language within a given text format. Due to the high variability of Arabic dialects and the lack of large-scale annotated datasets, dialect identification poses a challenging task.

### Important Libraries

The following Python libraries are used in this project:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `re`: For regular expression operations
- `nltk`: For natural language processing tasks
- `sklearn`: For machine learning algorithms and evaluation metrics

### About the Data

The project uses the "Arabic Dialect Identification" dataset, which includes messages in different Arabic dialects. The dataset is split into two parts: messages and dialect labels.

### Data Processing Steps

1. Load the messages and dialect datasets.
2. Merge the datasets using the 'id' column as a common identifier.
3. Convert dialectal Arabic names to full country names.
4. Preprocess the text data by removing URLs, mentions, hashtags, and stopwords. Also, reduce words to their stems using stemming techniques.
5. Split the data into training and testing sets.

### Model Training and Evaluation

1. Train a Linear Support Vector Machine (SVM) model using the training data.
2. Preprocess the test data in a similar manner to the training data.
3. Use the trained model to predict dialect labels for the test data.
4. Calculate the accuracy of the model on the test data.

### User Interaction

1. The system allows users to input an Arabic text.
2. The provided text is preprocessed and encoded.
3. The trained model predicts the dialect of the input text.
4. The system displays the identified dialect.

### Usage

1. Clone this repository to your local machine.
2. Install the required libraries using the provided requirements file.
3. Run the code in your preferred Python environment.
4. Follow the prompts to input Arabic text and observe the identified dialect.

Please note that this project requires a good understanding of Arabic linguistics, natural language processing concepts, and machine learning techniques. The accuracy of the dialect identification may vary depending on the dataset and model parameters.

**Note**: The dataset and code provided in this repository are for educational purposes. Make sure you have the necessary permissions to use the dataset and understand the terms of use.

For any inquiries or issues related to this project, feel free to contact the project contributors.

