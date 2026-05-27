# News Article Prediction App

A simple **Streamlit** web app that predicts the category of a news article from user-entered text using a pre-trained machine learning model.

## Features

- Enter news text in a text box.
- Predict the article category with one click.
- Shows a warning if no text is entered.
- Easy-to-use Streamlit interface.

## Project Structure

```bash
.
├── app.py
├── news_model.pkl
└── README.md
```

## Requirements

Make sure you have the following installed:

- Python 3.8+
- Streamlit
- pickle (built-in with Python)
- A trained model file named `news_model.pkl`

## Installation

1. Clone the repository or download the project files.
2. Install the required Python package:

```bash
pip install streamlit
```

## How to Run

Run the app using:

```bash
streamlit run app.py
```

## Usage

1. Open the app in your browser.
2. Paste or type a news article in the text area.
3. Click the **Predict** button.
4. View the predicted category.

## Model File

The app expects a trained model saved as:

```bash
news_model.pkl
```

This file should be present in the same directory as `app.py`.

## Notes

- The model must support prediction on raw text input.
- If the text box is empty, the app will display a warning message.
- Make sure `news_model.pkl` was trained and saved correctly using `pickle`.

## Example

Input:
```text
The government announced new economic reforms today.
```

Output:
```text
Predicted Category: business
```

## License

Add your preferred license here.
