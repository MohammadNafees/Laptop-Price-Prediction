# Laptop-Price-Prediction
A machine learning project that predicts the price of a laptop based on its specifications. This project involves comprehensive data analysis, feature engineering, model training, and deployment of the model using Hugging Face Spaces.

## 🚀 Demo

Check out the live demo here: [🔗 Laptop Price Predictor on Hugging Face][(https://huggingface.co/spaces/MohammadNafees/LaptopPricePrediction)]

---

## 📊 Project Overview

The goal of this project is to build a regression model that accurately predicts the price of a laptop using features such as:

- Brand
- Processor type
- RAM size and type
- Storage (HDD/SSD)
- Screen size and resolution
- Operating System
- Graphics Card

The application is particularly useful for consumers, retailers, and market analysts interested in understanding laptop pricing trends and factors.

---

## 📁 Dataset

The dataset was collected from e-commerce websites and contains the following key features:

- `Company`
- `TypeName`
- `Inches`
- `ScreenResolution`
- `Cpu`
- `Ram`
- `Memory`
- `Gpu`
- `OpSys`
- `Weight`
- `Price` 

---

## 🧪 Exploratory Data Analysis

- Handled missing and inconsistent values
- Converted categorical variables into numerical representations
- Engineered features like:
  - CPU brand extraction
  - SSD/HDD breakdown from "Memory" column
  - Touchscreen detection
- Identified feature correlations and distribution of target variable
- Visualized key insights using `matplotlib` and `seaborn`

---

## 🛠️ Model Development

- **Preprocessing**: Label Encoding, One-Hot Encoding, Standard Scaling
- **Modeling Techniques**: 
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- **Evaluation Metrics**:
  - R² Score
  - MAE, MSE, RMSE

Final model: **Random Forest Regressor** (selected for best performance)

---

## 🧾 Requirements

To run the project locally:

```bash
pip install -r requirements.txt
```


``` Main libraries used:

pandas

numpy

scikit-learn

matplotlib

seaborn

gradio

joblib

```
🌐 Deployment
The model is deployed using Streamlit and hosted on Hugging Face Spaces.

Files:
app.py: Contains the Gradio interface code

pipe.pkl: Trained Random Forest model

df.pkl: Preprocessing pipeline

requirements.txt: Dependencies for Hugging Face

🖼️ UI Preview
<img width="1158" height="2030" alt="Untitled" src="https://github.com/user-attachments/assets/a05691e3-9609-4bb3-955f-8e5205e84fb1" />


🤝 Contributing
Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License
This project is licensed under the Apache 2.0 License.

🙏 Acknowledgements
scikit-learn for modeling

Streamlit for UI

Hugging Face for deployment
