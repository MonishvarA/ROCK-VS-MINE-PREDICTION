# Mine vs Rock Prediction

This project is a machine learning model that predicts whether an object detected by sonar is a **mine (explosive)** or a **rock (non-explosive)** based on the given sonar signal data.

## Overview

Sonar signals are used to detect objects underwater. Each signal is represented by numerical values that indicate the strength of the reflected signal at different frequencies.  
This project applies **machine learning** to classify these signals into two categories:
- **Mine (M)**
- **Rock (R)**

The project is implemented in a **Jupyter Notebook** (`Mine_vs_Rock_Prediction.ipynb`) using Python and key data science libraries.

## Dataset

The dataset used is the **Sonar Dataset** from the UCI Machine Learning Repository.  
- Each row represents 60 attributes corresponding to the energy within a particular frequency band.  
- The last column contains the class label:
  - `M` → Mine
  - `R` → Rock

## Project Workflow

1. **Import Libraries**  
   Load essential Python libraries such as NumPy, Pandas, and Scikit-learn.

2. **Load and Explore Data**  
   Analyze the structure of the dataset and check for missing values or imbalances.

3. **Data Preprocessing**  
   - Convert categorical labels into numeric form.
   - Split the dataset into training and testing sets.

4. **Model Training**  
   Train a Logistic Regression model (or any other classifier) using the training data.

5. **Evaluation**  
   Measure model performance using accuracy and compare predicted vs actual values.

6. **Prediction System**  
   Create a user input-based prediction system to classify new sonar readings.

## Requirements

Make sure the following libraries are installed:

```bash
pip install numpy pandas scikit-learn
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Mine-vs-Rock-Prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Mine-vs-Rock-Prediction
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Mine_vs_Rock_Prediction.ipynb
   ```

4. Run all cells to train and test the model.

## Result

The trained model successfully classifies sonar signals as either **Mine (M)** or **Rock (R)** with high accuracy, demonstrating the effectiveness of machine learning in real-world detection problems.
