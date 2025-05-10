# Kidney Disease Classification System (KDCS)

The Kidney Disease Classification System (KDCS) is a web-based application designed to support early detection and classification of Chronic Kidney Disease (CKD) and related kidney conditions. It combines machine learning (Gradient Boosting Classifier) for analyzing clinical data and deep learning (MobileNet) for processing ultrasound images, all integrated into a Django-based platform.

## Project Overview

- **Objective**: Provide an AI-powered tool for accurate and timely CKD diagnosis using clinical metrics and medical imaging.
- **Technologies Used**: Python, Django, Scikit-learn, TensorFlow, Joblib, PIL, Matplotlib, Seaborn.
- **Datasets**: 
  - Numerical: UCI CKD dataset (KIDNEY.csv) with 400 records.
  - Image: Custom dataset with 4,000 ultrasound images (Normal, Tumor, Stone, Cyst).
- **Performance**: Achieves 99% accuracy for numerical predictions and 92.4% for image classification.

## Features

- Predicts CKD presence based on clinical inputs (e.g., blood pressure, hemoglobin).
- Classifies ultrasound images into four categories: Normal, Tumor, Stone, Cyst.
- Offers a responsive web interface for data entry and result display.
- Stores predictions in an SQLite database with admin management.
- Includes audio narration for image classification results.

## Installation and Setup

### Prerequisites
- Python 3.8 or higher.
- Git (for cloning the repository).

### Steps to Set Up

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/kdcs.git
   cd kdcs

2. Create and Activate Virtual Environment:
python -m venv venv
venv\Scripts\activate

3. Install Required Dependencies:
   pip install -r requirements.txt

4.Configure the Project:
  python manage.py migrate

5.Apply Migrations:
  python manage.py migrate

6.Create a Superuser:
  python manage.py createsuperuser

7.Run the Development Server:
  python manage.py runserver

File Structure
kidney_project/: Core Django project files.
APP/: Contains models (models.py), views (views.py), templates, and pre-trained models.
DATASET/TRAIN/: Ultrasound image dataset directory.
KIDNEY.csv: Tabular dataset file.
requirements.txt: Dependency list (if included).
README.md: This file.
Contributing
Contributions are encouraged! Fork the repository, create a feature branch, commit your changes, and submit a pull request.

License
Distributed under the MIT License. See LICENSE file for more details.

Contact
Abdul Bashith J: bashithabdul01@gmail.com
Dhowfeek Hasan S: dhowfeekhasan@gmail.com
Syed Yaheya S I: syedyaheya16@gmail.com
Acknowledgments
This project was developed with support from B.S. Abdur Rahman Crescent Institute of Science and Technology.