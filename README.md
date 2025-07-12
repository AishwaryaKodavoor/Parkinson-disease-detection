# Parkinson-disease-detection
This project focuses on using machine learning to help detect Parkinson’s Disease by analyzing biomedical voice measurements. Built using Python and popular data science libraries, the code is structured to run easily in Jupyter Notebook or Google Colab.

About the Project

Parkinson’s Disease is a progressive nervous system disorder that affects movement and speech. Early detection can make a significant difference in managing the disease. In this project, we use a Support Vector Machine (SVM) model to classify whether a person has Parkinson’s based on vocal features from a provided dataset.
Dataset Information


Source Code: Kaggle
Target Column: status (1 = Parkinson’s, 0 = Healthy)
Features: A range of voice-related metrics such as frequency, jitter, shimmer, and more

Tools and Libraries

The project is implemented in Python and uses:

pandas and numpy for data handling

matplotlib and seaborn for data visualization

scikit-learn for building and evaluating the machine learning model

To install the required libraries, use:

pip install pandas numpy matplotlib seaborn scikit-learn

Project Structure

parkinson's_project.ipynb - The main Jupyter Notebook with step-by-step code
parkinsons (1).csv - The dataset file (ensure it's uploaded or accessible before running the notebook)
