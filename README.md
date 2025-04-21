# Money Laundering Classification Project

## 📌 Project Objective

Develop a machine learning model to accurately detect **online fraudulent transactions** from a large volume of financial data, distinguishing between **legitimate** and **suspicious** activities.

## 🧠 Approach

- **Data Visualization**: Explored key features to understand patterns between legitimate and fraudulent transactions.
- **Data Preprocessing**: 
  - Sampled **500,000 transactions** for faster experimentation and modeling.
  - Handled imbalanced data to improve model performance on minority (fraudulent) class.
- **Model Building**:
  - Built a **Random Forest Classifier** to predict fraudulent transactions.
- **Error Analysis**:
  - **Type-I Error (False Positive)**: 55 transactions wrongly flagged as fraud.
  - **Type-II Error (False Negative)**: 0 transactions missed (i.e., no fraudulent transaction was wrongly classified as legitimate).

## ✅ Conclusion

- The model achieved **100% recall** on the fraudulent transaction class.
- **Random Forest Classifier** demonstrated excellent performance in detecting fraudulent activities without missing any true fraud cases.
- Minimal false positives, ensuring limited disruption for legitimate customers.

## 📊 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (RandomForestClassifier, model evaluation metrics)
- Jupyter Notebook

## 📂 Project Structure

```plaintext
Money_Laundering_Classification_Project/
│
├── Money Laundering Classification Project.ipynb  # Main notebook
├── README.md                                       # Project documentation
└── requirements.txt                                # (Optional) List of dependencies
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/tariquedts/Money_Laundering_Classification_Project.git
   cd Money_Laundering_Classification_Project
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook "Money Laundering Classification Project.ipynb"
   ```

4. Run all cells to reproduce the results.

## 📈 Future Improvements

- Implement deep learning models like LSTM for sequence analysis.
- Use SMOTE or other techniques to better handle class imbalance.
- Deploy the model using Flask or FastAPI for real-time fraud detection.

## ✨ Author

- [Your Name Here] (Feel free to replace with your name or GitHub profile)

---

Would you also like me to generate a `requirements.txt` automatically based on the libraries you used? 🚀  
It'll make your GitHub repo even more complete!