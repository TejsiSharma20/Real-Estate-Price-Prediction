# Real Estate Price Prediction

## Project Overview
This project focuses on predicting the median value of houses in a given area using machine learning techniques. The dataset includes various features such as crime rate, land zoning, proximity to the Charles River, air quality, and socioeconomic factors, which influence the real estate market. The goal is to build an efficient and accurate predictive model that can be used for housing price estimation, a key task in real estate investment and analysis.

## Dataset Features
- **Area_Code:** A measure representing the crime rate per capita in the area.
- **Land_Zoning:** Proportion of residential land zoned for lots over 25,000 sq. ft.
- **Business_Acreage:** Proportion of non-retail business acres per town.
- **River_Proximity:** A binary indicator showing whether the area is near the Charles River (1 = near the river, 0 = not near).
- **Pollution_Level:** Concentration of nitric oxides in the air (an indicator of air quality).
- **Rooms_Avg:** Average number of rooms per dwelling in the area.
- **Old_Units_Rate:** Percentage of owner-occupied units built before 1940, indicating the area's age.
- **Distance_Centers:** Weighted distances to five major employment centers.
- **Highway_Access:** Accessibility index to radial highways.
- **Tax_Rate:** Property tax rate per $10,000 in the area.
- **Student_Teacher_Ratio:** Ratio of students to teachers in the area, representing school density.
- **Demographic_Index:** A demographic proportion index for the area.
- **Low_Status_Pop:** Percentage of the population considered lower status, based on socioeconomic factors.
- **Median_House_Value:** Median value of owner-occupied homes in $1000s (target variable)
  

## Libraries Used
- **Python** (for data manipulation, model building, and evaluation)
- **Pandas** (for data processing)
- **NumPy** (for numerical operations)
- **Scikit-learn** (for machine learning algorithms and evaluation metrics)
- **Joblib** (for saving and loading the trained model)
- **Matplotlib** (for data visualization)
- **Seaborn** (for statistical data visualization)

## Steps Taken
1. **Data Preprocessing:**
   - Handled missing values using **SimpleImputer**.
   - Scaled the features using **StandardScaler** for better model performance.
   - Split the dataset into training and testing sets.
2. **Model Building:**
   - Tried several models, including **Linear Regression** and **Decision Tree Regressor**.
   - Chose **Random Forest Regressor** for its superior accuracy and generalization.
3. **Model Evaluation:**
   - Used **cross-validation** and **RMSE** to evaluate model performance.
4. **Model Saving:**
   - Saved the trained model using **Joblib** to make future predictions more efficient.
   - 

  ## How to Install and Run the Project
1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-price-prediction.git
   pip install -r requirements.txt
   python real_estate_prediction.py



## Conclusion
In this project, I utilized **Python** to apply machine learning techniques for predicting house prices. The focus was on **data preprocessing**, **model selection**, and **model evaluation**.By working with a simulated or publicly available dataset, I was able to enhance the prediction accuracy and ensure the model’s reliability. 

This project showcases my skills in:
- **Machine Learning** 
- **Python Programming** 
- **Model Deployment**





  
   

