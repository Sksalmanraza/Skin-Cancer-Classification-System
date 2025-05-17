Skin Cancer Classification System

This repository contains the Skin Cancer Classification System, a deep learning-based project designed to classify skin lesions using the HAM10000 dataset. It provides a web-based interface for users to upload images and get diagnostic predictions.

Features ::
1) Interactive Web Application: Upload and analyze skin lesion images through an intuitive interface.
2) Deep Learning Model: A robust model trained to classify images into skin cancer categories.
3) User Authentication: Secure login and registration functionality.
4) Real-Time Results: Instant prediction and confidence score for uploaded images.

File Overview ::
Notebook.ipynb: Contains data preprocessing, model training, and evaluation code.
app.py: Flask-based Python script for serving the web application.
model.h5: Trained deep learning model file saved in Keras format.
requirements.txt: List of dependencies required for the project.
signup.db: SQLite database for managing user registration and authentication.
static/: Directory containing static assets such as CSS, JavaScript, and images.
templates/: HTML templates for the web application.
run.bat: Batch script for running the application on Windows.

Data Sources ::
The project uses the HAM10000 dataset, which contains labeled skin lesion images, including:
Melanocytic nevi
Melanomas etc..

Key Metrics and Insights ::
Model Accuracy: Classification accuracy of the trained deep learning model.
Loss Trends: Visualization of training and validation loss curves.
Prediction Confidence: Confidence scores provided for each classification.

Custom Features ::
The project includes custom features such as:
Data Augmentation: Techniques like flipping, rotation, and scaling for robust training.
Model Evaluation: Metrics including accuracy, precision, recall, and F1-score.
User-Friendly Interface: Simple and interactive UI for end-users.

How to Use ::
Clone the repository and navigate to the project directory:

git clone https://github.com/Sksalmanraza/Skin-Cancer-Classification-System.git
cd Skin-Cancer-Classification-System

Set up a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

Run the application:
python app.py
Open your browser and navigate to http://127.0.0.1:5000 to use the application.
