# 🌾 AI-Driven Soil Fertility Prediction

This project uses machine learning to predict the **fertility level of soil**—Low, Medium, or High—based on key nutrient and chemical properties. It aims to support **smart agriculture** by providing AI-based insights into soil health for better crop planning.

## 📌 Objective

To build a machine learning model that can classify soil fertility using nutrient data and support data-driven decision-making in agriculture.

## 🧪 Dataset

- Contains **1,288 soil samples**
- Features include:
  - Macronutrients: Nitrogen (N), Phosphorus (P), Potassium (K)
  - Chemical properties: pH, Electrical Conductivity (EC), Organic Carbon (OC)
  - Micronutrients: Sulphur (S), Zinc (Zn), Iron (Fe), Copper (Cu), Manganese (Mn), Boron (B)
  - Label: `fertility` (0 = Low, 1 = Medium, 2 = High)

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** for data handling
- **Seaborn**, **Matplotlib** for visualization
- **Scikit-learn** for ML modeling

## 📈 Model Used

- **Logistic Regression** classifier
- Achieved **100% accuracy** on the test data
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score

## 🔍 Workflow

1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature-label separation
4. Train-test split
5. Model training using Logistic Regression
6. Evaluation with classification report and performance metrics
7. Data visualizations (correlation heatmap, distribution plots)

## 📊 Visuals

- Correlation heatmap of all features
- Histogram and KDE plots to show feature distributions

## ✅ Output

The model predicts the fertility class of a given soil sample based on its nutrient values, with excellent performance across all classes.

## 🚀 Future Improvements

- Try other models (Random Forest, SVM)
- Deploy as a web app for farmer access
- Integrate with real-time soil sensors


