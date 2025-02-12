# Flower Family Classification System

## Overview

The **Flower Family Classification System** is a machine learning-based project designed to classify different flower families accurately. It uses deep learning models to analyze flower's petal width, petal lenth, sepal width, sepal length and predict their respective families. This system is implemented with Django for the backend and provides a user-friendly web interface.

## Features

- **Automated Classification**: Uses a pre-trained deep learning model to classify flower.
- **Web-Based Interface**: Allows users to provide flower's petal width, petal lenth, sepal width, sepal length for classification via a simple UI.
- **Scalable Model**: Can be extended to support more flower families.
- **Database Integration**: Stores classification results for analysis.
- **Lightweight Deployment**: Built using Django, making it easy to deploy.

## Project Structure

```
├── FlowerDetection/         # Flower detection scripts
├── Notebooks/              # Jupyter Notebooks for model training and evaluation
├── djangoMLDeployment/     # Django backend for the classification system
├── static/images/          # Static images used in the web app
├── templates/              # HTML templates for the web app
├── trainedModel/           # Folder containing the trained model
├── db.sqlite3              # SQLite database file
├── manage.py               # Django management script
└── requirements.txt        # Dependencies for the project
```

## Installation

### Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- Django
- TensorFlow/Keras
- OpenCV (for image processing)

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/nitssa/Flower-Family-Classification-System.git
   cd Flower-Family-Classification-System
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run database migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the Django development server:
   ```bash
   python manage.py runserver
   ```
6. Open your browser and visit `http://127.0.0.1:8000/` to use the application.

## Usage

1. Upload a flower's petal width, petal lenth, sepal width, sepal length using the web interface.
2. The system will analyze the image and classify it into a flower family.
3. View the classification results and related information.

## Model Details

- The classification model is built using TensorFlow and trained on a dataset of flower's petal width, petal lenth, sepal width, sepal length.
- The model architecture includes convolutional layers for feature extraction and a fully connected layer for classification.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them.
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or support, contact Me!
