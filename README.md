

# **Classification of Poverty Levels in Indonesia Using Machine Learning**

## **Project Description**
This project aims to build the best classification model for predicting poverty levels in Indonesia based on socio-economic and demographic features of each region. The dataset consists of 514 entries representing provinces and districts/cities in Indonesia with 12 features. These features include economic indicators, education levels, health metrics, and other key socio-economic statistics. The data is preprocessed and analyzed to ensure robust model development and evaluation.
data source:https://www.kaggle.com/datasets/ermila/klasifikasi-tingkat-kemiskinan-di-indonesia

## **Project Goals**
1. Develop multiple classification models to predict poverty levels in Indonesia.
2. Evaluate and compare the models based on their accuracy to identify the best-performing model.
3. Analyze the relationships between socio-economic features and their impact on poverty prediction.

## **Methodology**
1. **Load Data**: The dataset was imported and cleaned, containing features such as education levels, sanitation access, unemployment rates, and regional economic performance.
2. **Exploratory Data Analysis (EDA)**: Insights were extracted using descriptive statistics and visualizations, such as heatmaps, to identify patterns and correlations among features.
3. **Data Preprocessing**:
   - Missing values were handled by imputing numerical values with the mean and encoding categorical features with LabelEncoder.
   - Features were standardized using StandardScaler.
4. **Data Visualization**:
   - Correlation heatmaps were generated to highlight the relationships between socio-economic features.
5. **Splitting and Scaling Data**:
   - The dataset was split into training and test sets (80:20 ratio), ensuring balanced representation.
6. **Modeling**:
   - Three classification models were developed: Random Forest, Logistic Regression, and K-Nearest Neighbors (KNN).
   - The Random Forest model achieved the highest accuracy of **99.03%**.
7. **Evaluation**:
   - Classification reports and confusion matrices were generated to assess model performance.

## **Project Key Insights**
1. The features `P0 Persen` (percentage of poor population) and `Mean Lama Sekolah 15+` (average years of schooling) are highly significant in classifying poverty levels.
2. Visualizing the dataset through correlation heatmaps reveals strong relationships between poverty and access to education, health metrics, and sanitation.
3. The Random Forest model demonstrated superior accuracy and generalization ability, making it the most reliable choice for this classification task.

## **Best Model**
- **Random Forest Classifier**
  - **Accuracy**: 99.03%
  - **F1-Score**: 0.99
  - This model excels in balancing precision and recall, ensuring stable performance for unseen data.

## **Contact**
If you have suggestions or want to collaborate, feel free to reach out:
- **Email**: mochhabibibier@gmail.com  
- **LinkedIn**: https://www.linkedin.com/in/mhabibierobbi12/
