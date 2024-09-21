
---

# Resume Screening App

This project is a **Resume Screening Application** that uses machine learning to automatically identify job roles based on textual data from resumes. It performs text preprocessing, feature extraction using **TF-IDF**, and utilizes a **multiclass classification** algorithm for job role prediction. The app is deployed using **Streamlit** to create a user-friendly web interface.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Model and Algorithm](#model-and-algorithm)
- [Deployment](#deployment)
- [Contributing](#contributing)


## Overview

The Resume Screening App is designed to automate the process of identifying job roles from a given resume text. This tool can be used by recruiters and HR teams to streamline the resume screening process. The key components include:
- Text preprocessing (removal of punctuations, hashtags, links, etc.).
- TF-IDF vectorization for feature extraction.
- A multiclass classification model to predict the most likely job role.
- A user interface powered by **Streamlit**.

## Features

- **Text Preprocessing**: Clean up resumes by removing unwanted characters like punctuation, links, and special symbols.
- **TF-IDF Vectorization**: Converts textual data into numerical features.
- **Multiclass Classification**: Predicts job roles from resumes using machine learning.
- **Interactive Web Application**: Allows users to upload resumes and get instant job role predictions.

## Usage

1. Upload a resume in plain text format or type the resume text directly into the app.
2. The application will clean the resume text by removing unwanted characters.
3. The app will then use the trained model to predict the relevant job role based on the resume's content.
4. View the predicted job role and confidence score.

## Model and Algorithm

- **TF-IDF (Term Frequency-Inverse Document Frequency)** is used for text vectorization, transforming the raw text into numerical features.
- **Multiclass Classification**: A machine learning algorithm K-Nearest Neighbors is used to classify the resumes into different job roles.
- The model is trained using labeled resume data and then deployed in the app for real-time predictions.

## Deployment

The app is deployed using **Streamlit**, which allows for easy sharing of the application with others. To run the application locally:
1. Run the Streamlit app with the following command:
   ```bash
   streamlit run app.py
   ```
2. Open the link provided by Streamlit in your browser to access the web interface.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m "Add some feature"`).
4. Push the branch to your fork (`git push origin feature-branch`).
5. Open a Pull Request.

