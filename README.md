# 🤖 House Rent Prediction in Machine Learning Using Python
This project, developed for a 3rd-semester Machine Learning course, tackles the challenge of predicting house rent prices. The goal is to build a robust regression model that can accurately estimate rent based on a variety of property features.
For landlords, this tool can help in setting competitive and fair rental prices. For tenants, it provides a benchmark to gauge if a property is priced appropriately. By leveraging machine learning, this project aims to uncover hidden patterns and complex relationships within a large real estate dataset to make reliable predictions.

---

### 📊 Dataset Description
The dataset selected is the **House Rent Dataset** obtained from Kaggle, created from a real estate website in India.
* **Source:** **[House Rent Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset)**
* **Size:** 4,746 entries with 12 features.
* **Target Variable:** `Rent`
  
---

### ⚙️ Modeling & Evaluation
The purpose of modeling is to predict the rental price of a property based on its features. This will produce an output that is fair, unbiased, and in accordance with the property's characteristics. With reasonable rental prices, the system can reach more people and help them live properly.
#### 1. Baseline Model: Linear Regression
* **Reasoning:** Chosen for its simplicity, ease of interpretation, and low computational cost.
#### 2. Proposed Model: Random Forest Regressor
* **Reasoning:** A more complex ensemble model capable of handling non-linear relationships and being less sensitive to outliers. It also provides powerful built-in functionalities like feature importance.
* **Fine-Tuning:** A **Grid Search** was performed to find the optimal hyperparameters.

#### Evaluation & Analysis
| Model                  | R²    | RMSE    | MAE     |
| ---------------------- | ----- | ------- | ------- |
| Linear Regression      | 0.746 | 0.468   | 0.358   |
| **Fine-tuned Random Forest** | **0.842** | **0.370** | **0.283** |
The **Fine-tuned Random Forest** model was the clear winner, explaining more variance in rent prices (higher R²) and making more accurate predictions (lower RMSE and MAE).

---

## 🏆 Conclusion
The **Random Forest Regressor** significantly outperformed the baseline Linear Regression model. After fine-tuning, the final model was able to explain **84.2%** of the variance in house rent prices. The project successfully shows that fair and unbiased rent predictions are achievable, providing a valuable tool for both landlords and tenants.

---

## 🛠️ Concepts
* **Language:** Python 
* **Core Concepts:**
    * Exploratory Data Analysis (EDA)
    * Feature Engineering & Scaling
    * Model Training (Linear Regression & Random Forest Regressor)
    * Evaluation (MAE, RMSE, R^2)
    * Hyperparameter Tuning (Grid Search)
      
---

### 🖋 Author
* Aquila Kyne Sudiro 
* Caroline Ang 
* Laurel Evelina Widjaja 
* Liliana Djaja Witama 
