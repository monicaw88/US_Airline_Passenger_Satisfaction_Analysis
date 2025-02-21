# US Airline Passenger Satisfaction Analysis

## Project Overview
This project conducts an in-depth analysis of the US airline passenger satisfaction dataset sourced from Kaggle using data science techniques. The primary objective is to identify the key factors influencing passenger satisfaction and build a predictive model.

During the analysis process, several crucial steps are carried out:
- **Data cleaning**: Missing values and outliers are handled to ensure data integrity.
- **Feature engineering**: New features are created from existing data to improve model performance.
- **Model building**: Multiple machine learning models are applied, optimized, and evaluated to predict passenger satisfaction.

The goal is to provide actionable insights for airlines to enhance their services and improve customer satisfaction.

## Dataset
### Source
The dataset used in this project is obtained from Kaggle and contains detailed information about US airline passengers, including flight details (e.g., departure/arrival times, flight routes), service evaluations (e.g., food quality, cabin crew service), and passenger demographics (e.g., age, gender).

### Data Preprocessing
- **Missing Value Handling**: Missing values are handled through imputation (mean, median, mode) or row/column deletion depending on the extent of missing data.
- **Outlier Detection and Treatment**: Outliers are detected using statistical methods (e.g., Z-score, IQR) and treated through removal or capping.
- **Data Encoding**: Categorical variables are transformed into numeric formats using techniques like One-Hot Encoding and Label Encoding.

## Project Structure
US_Airline_Passenger_Satisfaction_Analysis/ │ ├── data/ # Contains raw and processed data │ ├── raw/ # Raw dataset downloaded from Kaggle │ └── processed/ # Processed data after cleaning and preprocessing │ ├── notebooks/ # Jupyter Notebooks for data analysis and modeling │ ├── data_exploration.ipynb # Notebook for initial data exploration and visualization │ ├── data_preprocessing.ipynb # Notebook for data cleaning and preprocessing │ ├── feature_engineering.ipynb # Notebook for feature engineering tasks │ └── model_building.ipynb # Notebook for model construction and evaluation │ ├── src/ # Source code directory │ ├── data/ # Code related to data processing and loading │ ├── features/ # Code for feature engineering operations │ └── models/ # Code for model building and training │ ├── reports/ # Directory for project reports and results │ ├── figures/ # Generated charts and visualizations │ └── reports/ # Analysis reports and summaries │ ├── README.md # Project documentation file └── requirements.txt # List of dependencies required for the project


## Project Steps

### 1. Data Exploration and Visualization
- **Initial Exploration**: Conducted basic exploration to understand data structure, summary statistics, and the relationships between variables.
- **Visualization**: Created visualizations using Matplotlib and Seaborn, including bar charts, box plots, and scatter plots, to highlight trends and outliers.

### 2. Data Preprocessing
- **Handling Missing Data**: Missing values were filled using statistical imputation (e.g., mean for numerical, mode for categorical) or by removing irrelevant rows/columns.
- **Outlier Treatment**: Outliers were detected and handled using statistical methods like Z-score or IQR, ensuring they did not disproportionately affect the model.
- **Feature Encoding**: Categorical data were encoded using One-Hot Encoding for nominal variables and Label Encoding for ordinal variables.

### 3. Feature Engineering
- **Feature Selection**: Correlation analysis and feature importance techniques were used to identify key predictors for passenger satisfaction.
- **Dimensionality Reduction**: Techniques like PCA were applied to reduce the complexity of the data while retaining important features.

### 4. Model Building and Evaluation
- **Dataset Splitting**: The dataset was split into a training set (80%) and a test set (20%) to evaluate model performance.
- **Model Selection**: Various machine learning algorithms were applied, including logistic regression, decision trees, random forests, and support vector machines (SVM).
- **Model Training**: Models were trained on the training set, with hyperparameters optimized for best performance.
- **Model Evaluation**: Models were evaluated using metrics such as accuracy, precision, recall, and F1 score for classification tasks.

## Dependencies
This project relies on the following major Python libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: For machine learning model training and evaluation.

To install the required dependencies, run the following command:
```bash
pip install -r requirements.txt


## How to Run
1. **Clone the Project**:
   ```bash
   git clone <project repository URL>
   cd US_Airline_Passenger_Satisfaction_Analysis
2. **Install Dependencies**:
   ```bash
    pip install -r requirements.txt
3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
4. **Run the Notebooks**:

### Additional Notes:
1. **Accuracy**: Don't forget to replace `[insert accuracy]` with your model's actual performance (e.g., 85% accuracy).
2. **License**: I used the MIT License here, but if you'd prefer a different one (e.g., GPL, CC), you can replace it.
3. **Contributors**: Add any additional contributors if applicable.
4. **Kaggle Dataset**: You might want to mention the specific Kaggle dataset link if you want to provide full transparency.

This should provide a comprehensive and clean README for your project. Let me know if you need more tweaks!
