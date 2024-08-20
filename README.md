## Project Overview
This project focuses on developing a machine learning model to predict fraudulent transactions for a financial company. The dataset used for this project consists of 6,362,620 rows and 10 columns, providing substantial data to build a robust fraud detection model. The project includes data cleaning, model development using XGBoost, and performance evaluation.

### Project Structure
#### **Data Preprocessing:**

 - Checked for missing values and ensured all features were numeric.
 - Handled constant columns and multicollinearity issues using Variance Inflation Factor (VIF).
 - Processed categorical data appropriately for model compatibility.
   
#### **Model Development:**

- Used the XGBoost algorithm, which is known for its performance and efficiency in dealing with large datasets.
- Employed RandomizedSearchCV to optimize the hyperparameters for the model.
- Evaluated the model’s performance using accuracy metrics on the test dataset.
#### **Model Interpretation:**

- Used SHAP (SHapley Additive exPlanations) values to interpret the model’s predictions and identify the key factors contributing to fraudulent transactions.



### How to Run the Project
1. **Clone the Repository:**
  First, clone the repository to your local machine and navigate into the project directory:

    ```sh
    git clone [your-repository-link]
    cd [your-repository-directory]
    ```
    
2. **Download the Dataset:**
    - Manually download the dataset file (Fraud.csv) from Google Drive link provided in folder **Data** ---> **Data_Source.txt**.
    - Save the Fraud.csv file in the same directory where your Jupyter notebook (FraudDetection.ipynb) is located.
    
3. **Install Required Libraries:**
  Ensure you have Python installed, then install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook:**
   Open the FraudDetection.ipynb notebook and run the cells sequentially to reproduce the analysis and results:

    ```sh
    jupyter notebook FraudDetection.ipynb
    ```


### Future Plans
We plan to enhance this project by integrating a PowerBI dashboard to visualize the model's findings. This dashboard will offer interactive charts, maps, and timelines, making it easier for stakeholders to grasp key insights and trends in fraudulent activities. By translating data into clear visuals, the PowerBI integration will improve decision-making and provide a deeper understanding of the model's predictions.
