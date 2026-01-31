# pytorch-heart-disease

# Heart Disease Prediction with Logistic Regression (PyTorch)

This project is a beginner-friendly machine learning implementation of **logistic regression using PyTorch** to predict the presence of heart disease based on clinical features.

The goal of this project is **learning**, not claiming clinical accuracy. It serves as an introduction to:
- Data cleaning with Pandas
- Feature scaling
- Binary classification
- Building and training models in PyTorch
- Connecting machine learning concepts to healthcare data

---

## Dataset

This project uses the **UCI Cleveland Heart Disease dataset**, which contains:
- 303 patient records
- 13 clinical features (age, cholesterol, blood pressure, etc.)
- A binary target indicating presence or absence of heart disease

The target variable is processed so that:
- `0` = no heart disease  
- `1` = presence of heart disease (original values 1–4 combined)

---

## Dataset Features

This project uses 14 features from the UCI Cleveland Heart Disease dataset:

- `age`: age in years  
- `sex`: male = 1, female = 0  
- `cp`: chest pain type (1–4)  
- `trestbps`: resting blood pressure (mm Hg)  
- `chol`: serum cholesterol (mg/dl)  
- `fbs`: fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- `restecg`: resting electrocardiographic results (0–2)  
- `thalach`: maximum heart rate achieved  
- `exang`: exercise induced angina (1 = yes, 0 = no)  
- `oldpeak`: ST depression induced by exercise relative to rest  
- `slope`: slope of the peak exercise ST segment (1–3)  
- `ca`: number of major vessels colored by fluoroscopy (0–3)  
- `thal`: heart defect type (3 = normal, 6 = fixed defect, 7 = reversible defect)  
- `num`: diagnosis of heart disease (0 = <50% narrowing, 1 = >50% narrowing)

---

## Project Structure


- All modeling and experimentation is done in the `notebooks/` folder.
- Datasets are **not uploaded** to GitHub and are ignored via `.gitignore`.

---

## Methods

The workflow for this project includes:
1. Loading and cleaning the dataset using Pandas
2. Handling missing values in selected columns
3. Normalizing features using `StandardScaler`
4. Splitting the data into training and testing sets (80/20)
5. Implementing logistic regression in PyTorch
6. Training the model using an appropriate loss function
7. Evaluating model accuracy on the test set

---

## Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- PyTorch
- Google Colab
- Git & GitHub

---

## Motivation

As a student interested in both **computer science and medicine**, this project explores how machine learning can be applied to real-world healthcare data.

It also serves as a foundation for more advanced work in:
- Medical machine learning
- Deep learning with PyTorch
- Clinical data analysis

---

## Disclaimer

This project is for **educational purposes only**.  
It is **not intended for medical diagnosis or clinical use**.
