# Credit Card Fraud Detection

This project aims to detect **fraudulent credit card transactions** using machine learning models, helping to improve transaction security and reduce financial risks.



##  Table of Contents

1. [Project Description](#project-description)  
2. [Technologies Used](#technologies-used)  
3. [Dataset](#dataset)  
4. [Installation](#installation)  
5. [Workflow](#workflow)  
6. [Results](#results)  
7. [Conclusion](#conclusion)



##  Project Description

Credit card fraud is a serious issue in the financial sector. In this project, a machine learning model is trained to classify transactions as **fraudulent** or **legitimate** based on various features. Since the dataset is highly imbalanced, techniques like resampling are used to improve performance.



## 🛠️ Technologies Used

- Python  
- Jupyter Notebook / PyCharm  
- Pandas, NumPy  
- Matplotlib, Seaborn (for visualization)  
- Scikit-learn (for ML algorithms and evaluation)



##  Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- The dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, with only 492 being frauds.



##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is not available, manually install:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Run the notebook or script in Jupyter Notebook or any IDE (e.g., PyCharm).



##  Workflow

1. Load and preprocess the data  
2. Handle data imbalance using SMOTE or undersampling  
3. Perform Exploratory Data Analysis (EDA)  
4. Train machine learning models (e.g., Logistic Regression, Random Forest)  
5. Evaluate model performance (Accuracy, Precision, Recall, F1-Score)  
6. Predict and classify new transactions



##  Results

The trained model is able to accurately detect fraudulent transactions, achieving high recall and precision despite the class imbalance.



##  Conclusion

This project highlights how machine learning can effectively detect fraudulent credit card transactions, offering a valuable tool for financial institutions to enhance security and prevent financial loss.
