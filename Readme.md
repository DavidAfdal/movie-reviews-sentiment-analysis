# Moview Reviews Sentiment Analysis using Google Colab

This project demonstrates how to build a sentiment analysis model using the IMDB dataset in Google Colab.

## Steps to Run the Sentiment Analysis Program

1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on "File" > "Upload Notebook" and upload the notebook file (e.g., `sentiment_analysis.ipynb`).

3. **Download the Dataset**:
   You can download the dataset directly from the link below using the `wget` command in Colab:
   
   ```python
   !wget https://thecleverprogrammer.com/wp-content/uploads/2020/05/IMDB-Dataset.csv -O IMDB-Dataset.csv
   ```
4. **Run All Cells** : Once you have uploaded the notebook and downloaded the dataset, run all cells in the notebook. This will:

    - Load the IMDB dataset.

    - Preprocess the text data for model training.

    - Train a sentiment analysis model.

    - Evaluate the model's performance.

    - Make predictions on new reviews.
