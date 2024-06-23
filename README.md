# PolPredikt

PolPredikt is a web application for predicting election outcomes and visualizing voting data. It uses machine learning to forecast win/loss probabilities for political candidates based on voting statistics.

## Live Demo

You can access the live application at: [https://polpredikt.streamlit.app](https://polpredikt.streamlit.app)

## Features

- **User Authentication**: Secure login system to protect access to the application.
- **File Upload**: Users can upload election data files in CSV format.
- **Data Encryption**: Uploaded files are encrypted for security.
- **Machine Learning Predictions**: Predict election outcomes using a RandomForestClassifier.
- **Data Visualization**: Visualize win/loss distribution by party.

## Installation

To run PolPredikt locally, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/Prakalya898/PolPredikt.git
   cd PolPredikt
   ```
2. **Install the required packages using the requirements.txt file**:

    ```sh
   pip install -r requirements.txt
   ```
3. **Run the Streamlit app**:
   ```sh
   streamlit run app.py
   ```
