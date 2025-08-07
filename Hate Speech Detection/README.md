# Hate Speech Detection

This project implements a machine learning pipeline to detect hate speech and offensive language in tweets using Python and scikit-learn.

## Features

- Loads and preprocesses a labeled dataset of tweets.
- Cleans and normalizes text data (removes punctuation, stopwords, URLs, etc.).
- Uses stemming to reduce words to their root form.
- Vectorizes text using `CountVectorizer`.
- Trains a `DecisionTreeClassifier` to classify tweets into:
  - Hate Speech
  - Offensive Language
  - No Hate and Offensive
- Evaluates model performance with a classification report.
- Allows user input for real-time prediction.

## Usage

1. **Install dependencies**  
   Run the following command to install required packages:
   ```sh
   pip install -r requirements.txt
   ```

2. **Run the notebook**  
   Open `hate_speech_detection.ipynb` in Jupyter Notebook or VS Code and execute the cells sequentially.

3. **Test with your own comment**  
   Enter a comment when prompted to see its predicted label.

## Dataset

The project uses a public dataset from [this source](https://raw.githubusercontent.com/amankharwal/Website-data/master/twitter.csv).

## File Structure

- `hate_speech_detection.ipynb` — Main notebook with all code.
- `requirements.txt` — List of required Python packages.
- `.gitignore` — Standard ignore file for Python/Jupyter projects.

## License

This project is licensed under the MIT License - see the LICENSE file for details.