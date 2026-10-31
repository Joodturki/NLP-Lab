# English-to-French Translation

An Encoder–Decoder LSTM model that translates English sentences into French.

## Requirements
tensorflow, pandas, numpy, scikit-learn

## Usage
1. Place `eng_-french.csv` in the same folder as the notebook.
2. Run all cells to preprocess the data, train, and evaluate the model.
3. Use `translate_english_to_french()` to translate a sentence.

Training uses 5 epochs and a batch size of 64. Translation quality may be limited by the short training time.
