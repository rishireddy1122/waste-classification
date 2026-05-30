# Waste Classification Using Deep Learning

## Project Description

This project implements an image classification system for waste management using Deep Learning. A Convolutional Neural Network (CNN) is used to classify waste images into predefined categories. The trained model is integrated into a Flask-based web application that allows users to upload an image and receive a predicted waste category.

The objective of the project is to demonstrate the application of Deep Learning techniques for automated waste sorting and environmental sustainability.

---

## Technologies Used

* Python
* TensorFlow / Keras
* Flask
* HTML
* CSS
* JavaScript
* Bootstrap
* Jupyter Notebook
* Anaconda

---

## Waste Categories

The model classifies images into the following categories:

* Cardboard
* Glass
* Metal
* Paper
* Plastic
* Trash

---

## Project Structure

```text
waste-classification/
│
├── app.py
├── run.py
├── requirements.txt
├── waste_classification.ipynb
│
├── templates/
│   ├── home.html
│   ├── index.html
│   ├── login.html
│   ├── prediction.html
│   ├── performance.html
│   ├── charts.html
│   └── result2.html
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── uploads/
│
└── data/
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/rishireddy1122/waste-classification.git
cd waste-classification
```

### Create and Activate an Anaconda Environment

```bash
conda create -n waste-classification python=3.10
conda activate waste-classification
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the Flask application:

```bash
python app.py
```

or

```bash
python run.py
```

Open the application in a browser:

```text
http://127.0.0.1:5000
```

---

## Methodology

1. Collect and preprocess waste image data.
2. Train a Convolutional Neural Network (CNN) using TensorFlow/Keras.
3. Evaluate model performance on validation data.
4. Integrate the trained model into a Flask web application.
5. Perform image classification through a user interface.

---

## Results

The application accepts an uploaded image and predicts its corresponding waste category. The prediction result is displayed through the web interface.

Performance metrics and visualizations can be accessed through the application's analysis pages.

---

## Learning Outcomes

This project demonstrates practical experience in:

* Image Classification
* Deep Learning with CNNs
* TensorFlow/Keras
* Data Preprocessing
* Model Deployment
* Flask Web Development
* Machine Learning Project Integration

---

## Author

**Rishi Reddy**

Bachelor of Technology in Computer Science and Engineering

GitHub: https://github.com/rishireddy1122/waste-classification

---

## Disclaimer

This project was developed for academic and educational purposes.
