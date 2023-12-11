# Spam Detection System with Streamlit

This project implements a simple Spam Detection System using the Naive Bayes algorithm. It utilizes the SMS Spam Collection dataset and provides a Streamlit web application for user interaction.

## Prerequisites

Make sure you have the following libraries installed:

```bash
pip install pandas numpy scikit-learn streamlit
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

2. Run the Streamlit app:

```bash
streamlit run spam_detection_app.py
```

3. Open your web browser and go to `http://localhost:8501`.

4. Enter any message or email in the provided text area, and the system will predict whether it's spam or not.

## Project Structure

- **`spam.csv`:** CSV file containing the SMS Spam Collection dataset.
- **`spam_detection_app.py`:** The main Streamlit application file.
- **`README.md`:** Documentation for the project.
