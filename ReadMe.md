# Contract Review and Analysis
In this project, artificial intelligence was used to enhance and simplify the contract review process. By utilizing advanced algorithms, the system identifies key phrases, clauses, rights, and obligations within contracts. This automated analysis assists lawyers in identifying potential issues and improves the overall efficiency of the review process.

## Introduction 
The model has been trained to automatically extract and identify crucial clauses from contracts, significantly reducing the need for manual labor and associated costs. To accomplish this, the CUAD Dataset (Contract Understanding Atticus Dataset) was utilized, which consists of over 500 contracts meticulously annotated by legal experts. Through this dataset, 41 different types of significant clauses were identified.

To make accurate predictions, the pretrained model provided by the Atticus Project was utilized. This model has been integrated a user-friendly frontend system using Flask, allowing users to interact with the model seamlessly.

## Files
- **static**: This directory contains all the necessary style files required for the Flask application.
- **templates**: Within this directory, you will find the HTML files responsible for the frontend of our Flask application.
- **contract_review.ipynb**: This notebook file executes the pretrained model using the provided contract and questions.
- **index.py**: The main file responsible for running the Flask application. Please ensure that you define the path to the CUAD MODEL.
- **predict.py**: This file includes the function necessary for making predictions using the pretrained model.
- **questions.txt**: A text file containing all 41 questions the model has been trained on.
- **requirements.txt**: This file lists the Python libraries required for this project.