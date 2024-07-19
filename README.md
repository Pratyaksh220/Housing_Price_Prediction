# Housing_Price_Prediction
### Project Description

#### Clone or Fork the Project
1. **Clone or Fork the Project**: To get started, clone or fork this repository.

#### Create a Virtual Environment
2. **Create a Virtual Environment**: Set up a virtual environment for the project.

#### Install Dependencies
3. **Install Dependencies**: Navigate to the virtual environment and execute the following command to install all required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Project Highlights
- **Research Paper**: Included
- **User Friendly**: Yes
- **Accuracy**: High
- **Open Source**: Yes

### Table Of Contents
1. **Project Description**
2. **Data Collection**
3. **Generic Flow Of Project**
4. **EDA**
5. **Choosing Best ML Model**
6. **Model Creation**
7. **Model Deployment**
8. **Model Conclusion**
9. **Project Innovation**
10. **Limitation And Next Step**
11. **Working Project Video**

### Project Description

#### A. Problem Statement
Thousands of houses are sold every day. Common questions arise for buyers: What is the actual price this house deserves? Am I paying a fair price?

#### B. Best Possible Solutions
a. Housing Expert  
b. Intuition About House  
c. Using Machine Learning  

#### C. Introduction About Project
Predicting house prices is a complex task due to various factors like structure, rooms, kitchen, parking space, and gardens. Many factors influencing house prices are often unknown. Machine learning helps identify the perfect house and predict prices accurately.

#### D. Tools and Libraries
**Tools**
- Python
- Jupyter Notebook
- Flask
- HTML
- CSS
- JS
- Heroku
- GitHub

**Libraries**
- Pandas
- Scikit Learn
- Numpy
- Seaborn
- Matplotlib

### 2. Data Collection
For this project, data from Kaggle was utilized (click [here](#) for data). The dataset comprises 26 columns and 318,851 rows, focusing on key features:
- `url`, `id`, `cid`: Identifiers
- `Lng`, `Lat`: Coordinates
- `tradeTime`: Transaction time
- `DOM`: Days on market
- `followers`: Transaction followers
- `totalPrice`, `price`, `square`: Pricing and size details
- `livingRoom`, `drawingRoom`, `kitchen`, `bathroom`: Room counts
- `floor`: Building height
- `buildingType`, `constructionTime`, `renovationCondition`, `buildingStructure`: Property details
- `ladderRatio`, `elevator`, `fiveYearsProperty`: Accessibility and property age

### 3. Generic Flow Of Project

### 4. EDA

#### A. Data Cleaning
We started with 26 columns and removed unnecessary ones (`url`, `id`, `cid`). Data cleaning steps included:
- Handling missing values (`NaN`)
- Eliminating corrupted data
- Parsing dates/texts as needed

#### B. Feature Engineering
Identified outliers and used the IQR method for cleaning. Top 30 features related to `totalPrice` were selected for model use.

#### C. Data Normalization
Applied min-max normalization to scale features between 0 to 1, focusing on numerical columns.

### 5. Choosing Best ML Model
Explored various models:
- Linear Regression
- KNN
- Decision Tree
- Random Forest

Random Forest yielded the best results with 98% train and 89% test accuracy.

### 6. Model Creation
Further refined using Hyperparameter tuning techniques like GridSearchCV and RandomizedSearchCV, achieving 90% test and 94% train accuracy.

### 7. Model Deployment
Integrated the model into a user-friendly UI using HTML, CSS, JS, and Flask.

### 8. Model Conclusion
The model predicts with 90% accuracy on test data and 94% accuracy on train data.

### 9. Project Innovation
- Easy to use
- Open source
- High accuracy
- GUI Based Application

### 10. Limitation And Next Step
**Limitations**:
- Mobile Application
- Potential accuracy improvements
- Heavy model size (~310 MB)
- Limited features

**Next Steps**:
- Develop a mobile application
- Reduce model size using PCA

### 11. Working Project Video

This modified content for GitHub is structured and detailed, making it easier for users to understand the project's scope, methodology, and outcomes. Adjust URLs and specific details as needed for your project.
