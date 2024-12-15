# Heart-Disease-Detection

A machine learning-based system for predicting the likelihood of heart disease by analyzing patient health data, helping healthcare professionals make early and informed decisions.

## Overview

This project utilizes machine learning algorithms to predict heart disease risks by analyzing various health parameters such as:
- Age
- Blood Pressure
- Cholesterol Levels
- Lifestyle Factors

Using advanced classification algorithms, the system identifies patterns and risk factors in patient data, assisting healthcare professionals in early diagnosis and timely intervention.

## Features

- **Multiple Algorithms**: Implements Logistic Regression, Decision Trees, Random Forest, and Neural Networks.
- **Data-Driven Insights**: Processes health data to highlight key risk factors.
- **User-Centric Design**: Supports healthcare professionals in making accurate predictions and personalized treatment plans.
- **Improved Outcomes**: Aims to reduce the risk of severe heart conditions through early detection.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib/Seaborn
- **Data**: [Heart Disease Dataset](heart-disease.csv)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directorty>

2. Create a Virtual Environment (Optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate #on windows use `venv\scripts\activate`

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Download the dataset:
   Ensure that the heart-disease.csv file is placed in the project's root directory. You can 
   download the dataset from here.
   
  
5. Run the jupyter Notebook or script:
   To analyze the data and train models, launch the Jupyter Notebook:
   ```bash
    jupyter notebook Heart_Disease_Analysis.ipynb
   

## Contribution
   Contributions to this project are welcome! If you have suggestions for improvements or features,    feel free to open an issue or submit a pull request.

## Usage
   Preprocess the dataset using the provided code.
   Visualize data using Seaborn and Matplotlib.
   Train the KNN model and predict the presence of heart disease.
   Evaluate the model using accuracy, confusion matrix, and classification report.


## License
   This project is licensed under the MIT License.See the [MIT LICENSE](LICENSE) file for details.
   


