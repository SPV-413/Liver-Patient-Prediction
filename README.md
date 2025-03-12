# Liver Patient Prediction
This project focuses on predicting liver disease using machine learning models trained on the **Indian Liver Patient Dataset (ILPD)**,assisting doctors in early diagnosis and intervention. The dataset contains clinical parameters such as **bilirubin levels, enzyme levels, protein concentrations**, and more. The objective is to classify patients into two categories: **liver disease present (1) or absent (2)**.

## Dataset Overview
- **Source**: Indian Liver Patient Dataset (ILPD)
- **Rows**: 583
- **Columns**: 11 (including the target variable)
- **Target Variable**: 
  - `1` - Liver disease present
  - `2` - No liver disease
- **Features**:
  - Age
  - Gender
  - Total Bilirubin
  - Direct Bilirubin
  - Alkaline Phosphotase
  - Alamine Aminotransferase
  - Aspartate Aminotransferase
  - Total Proteins
  - Albumin
  - Albumin & Globulin Ratio
## Project Workflow
### 1. **Exploratory Data Analysis (EDA)**
- Data loading
- Data visualization using **Matplotlib & Seaborn**
### 2. **Feature Engineering**
- Handling missing values
- Removing duplicates
- Checking corrupted values
- Identifying & Handling the outliers
- Encoding categorical features(`OneHotEncoder`)
- Feature scaling (`MinMaxScaler`)
- Feature selection
- Splitting dataset into training & testing sets (`train_test_split`)
  
### 3. **Machine Learning Models**
The project implements multiple machine learning algorithms & one deep learning algorithm for classification:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**
- **K-Neighbors Classifier(KNN)**
- **Support Vector Classifier(SVC)**
- **Multi-layer Perceptron (MLP) Classifier**

### 4. **Hyperparameter Tuning**
- **RandomizedSearchCV** is used to optimize model parameters.

### 5. **Model Evaluation**
- **F1 Score**
- **Confusion Matrix**
- **Classification Report**

## Installation & Usage

### Prerequisites
Ensure you have the following installed:
- Python 3.10 and above
- Jupyter Notebook
- Required libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`)

### Running the Notebook
1. Clone the repository:
   git clone https://github.com/SPV-413/Liver-Disease-Prediction.git
2. Navigate to the project folder:
   cd Liver-Disease-Prediction
3. Open the Jupyter Notebook:
   jupyter notebook PRCP-1007-LiverPatientPred.ipynb

## Results
- **Logistic Regression** achieved the highest F1 Score.
- The project successfully demonstrates data preprocessing, model training, evaluation, and hyperparameter tuning.

## License
This project is open-source!

## Contact
For any inquiries, reach out via GitHub or email.
