# Credit Card Fraud Detection

This project focuses on building a **Credit Card Fraud Detection System** using various supervised learning algorithms and neural networks. The system aims to accurately detect fraudulent transactions while maintaining high performance. The project also includes robust data preprocessing, modeling, and a dashboard for data visualization and insights.

## Project Highlights

- **Data Cleaning and Preprocessing**:  
  - Removed duplicates, missing values, and outliers.  
  - Performed feature scaling and normalization.  
  - Applied techniques such as PCA for dimensionality reduction.

- **Data Storage**:  
  - Stored processed data in a structured database for easy retrieval and analysis.

- **Machine Learning and Neural Networks**:  
  - Implemented and evaluated multiple supervised learning algorithms such as Logistic Regression, Random Forest, Gradient Boosting, and SVM.  
  - Designed and trained a neural network for enhanced fraud detection.

- **Evaluation**:  
  - Metrics such as precision, recall, F1-score, and ROC-AUC were used to evaluate model performance.  
  - Ensured a balance between minimizing false positives and maximizing fraud detection accuracy.

- **Dashboard Creation**:  
  - Developed an interactive dashboard to visualize transaction trends, fraud patterns, and model predictions.  
  - Dashboard provides real-time insights into transaction anomalies and fraud statistics.

---

## Project Workflow

1. **Data Collection**  
   Collected anonymized credit card transaction data for training and evaluation.

2. **Data Cleaning and Preprocessing**  
   - Addressed missing values, imbalances, and noisy data.  
   - Conducted exploratory data analysis (EDA) to understand data distribution and fraud patterns.

3. **Model Development**  
   - Built supervised learning models and fine-tuned hyperparameters.  
   - Designed a custom neural network architecture for improved fraud detection.

4. **Model Deployment**  
   - Integrated the best-performing model into the fraud detection system.  
   - Stored processed data and predictions for dashboard visualization.

5. **Dashboard Creation**  
   - Used tools such as Power BI/Tableau/Plotly to design the dashboard.  
   - Visualized key metrics, fraud trends, and individual transaction risk scores.

---

## Technologies and Tools Used

- **Languages**: Python  
- **Libraries**:  
  - **Data Preprocessing**: Pandas, NumPy, Scikit-learn  
  - **Machine Learning**: Scikit-learn, XGBoost  
  - **Neural Networks**: TensorFlow, Keras  
  - **Visualization**: Matplotlib, Seaborn, Plotly  
- **Dashboard**: Power BI / Tableau / Dash  
- **Data Storage**: SQL / MongoDB  

---

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/whoisusmanali/Credit-Card-Fraud-Detection-using-AI.git
   cd Credit-Card-Fraud-Detection-using-AI
   ```

2. Install required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

3. Preprocess data:  
   Run the preprocessing script to clean and process the data:  
   ```bash
   python preprocess.py
   ```

4. Train models:  
   Train the machine learning and neural network models:  
   ```bash
   python train_model.py
   ```

5. Launch the dashboard:  
   ```bash
   python app.py
   ```

---

## Results

- Achieved high precision and recall for fraud detection.
- Reduced false positive rates while identifying fraudulent transactions accurately.
- Interactive dashboard enables quick decision-making for anomaly detection.

---

## Future Enhancements

- Integrate real-time fraud detection for live transactions.  
- Add more advanced deep learning models like LSTMs or Transformers.  
- Expand dashboard functionalities for better user insights.

---

## Contributors

- **Usman Ali**  
  [LinkedIn](https://www.linkedin.com/in/usman-ali-datascience/)

Feel free to reach out for questions or collaborations!