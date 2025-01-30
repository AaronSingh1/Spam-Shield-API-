#Aaron Singh 
Spam Detecation API
Overview
This project implements an email spam classifier using machine learning. It includes an end-to-end solution for detecting spam messages, with the backend powered by Python and a trained machine learning model. The API provides functionality to classify messages as spam or not spam.

Features
Pre-trained machine learning model for spam classification.
API endpoints to classify messages in real-time.
Dataset preprocessing and training pipeline included.
Easily deployable using Flask.
Project Structure
graphql
Copy
Edit
Spam-Shield-API--main/
│
├── README.md               # Project documentation
├── app.py                  # Main application file for running the API
├── api_running.py          # Script for API execution
├── api_test.py             # API testing script
├── sms-spam-detection.ipynb# Jupyter Notebook for model training and evaluation
├── spam.csv                # Dataset used for training the model
├── model.pkl               # Pre-trained machine learning model
├── vectorizer.pkl          # Serialized text vectorizer
└── requirements.txt        # Python dependencies
Getting Started
Prerequisites
Ensure you have Python 3.7+ installed on your system.

Installation
Clone this repository:
bash
Copy
Edit
git clone <repository-url>
cd Spam-Shield-API--main
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Running the API
Start the API using:
bash
Copy
Edit
python app.py
Access the API at http://127.0.0.1:5000.
Testing the API
Use the provided api_test.py script to test the API:

bash
Copy
Edit
python api_test.py
Dataset
The dataset spam.csv contains labeled messages as spam or not spam, used for training and evaluating the model.

Model
The classifier is built using machine learning and is trained on vectorized text data using techniques such as TF-IDF.
The serialized model (model.pkl) and vectorizer (vectorizer.pkl) are included for inference.
Contributing
Feel free to contribute by forking the repository, making changes, and submitting a pull request.

