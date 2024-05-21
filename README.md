# Project Give Life: Predict Blood Donations

## Project Description

"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ World Health Organization

Forecasting blood supply is a critical and recurrent issue for blood collection managers. For instance, in January 2019, the American Red Cross reported 27,000 fewer blood donations over the holidays compared to other times of the year. Utilizing machine learning to identify patterns in historical donation data can help predict future blood donations, potentially saving more lives.

This project utilizes data from the donor database of the Blood Transfusion Service Center in Hsin-Chu City, Taiwan. The center regularly gathers blood donations from a university in Hsin-Chu City approximately every three months. The dataset, obtained from the UCI Machine Learning Repository, consists of a random sample of 748 donors. The goal is to predict whether a blood donor will donate within a given time window. This project involves the full model-building process, from data inspection to using the TPOT library to automate the machine learning pipeline.

## Prerequisites

To complete this project, familiarity with the following is recommended:
- Python programming
- Pandas library
- Logistic regression

It is also beneficial to have completed the following DataCamp courses:
- Manipulating DataFrames with pandas
- Preprocessing for Machine Learning in Python
- Foundations of Predictive Analytics in Python (Part 1)

## Project Tasks

1. **Inspecting `transfusion.data` file**
   - Understand the structure and content of the dataset.
   
2. **Loading the blood donations data**
   - Import the dataset into a Pandas DataFrame.

3. **Inspecting transfusion DataFrame**
   - Examine the DataFrame for initial understanding and data cleaning.

4. **Creating target column**
   - Define the target variable for the prediction task.

5. **Checking target incidence**
   - Analyze the distribution of the target variable.

6. **Splitting transfusion into train and test datasets**
   - Divide the data into training and testing sets to evaluate model performance.

7. **Selecting model using TPOT**
   - Utilize the TPOT library to automate the machine learning pipeline and select the best model.

8. **Checking the variance**
   - Ensure the model's predictions are not overly dependent on specific features.

9. **Log normalization**
   - Apply log normalization to stabilize the variance and improve model performance.

10. **Training the linear regression model**
    - Train a linear regression model on the processed data.

11. **Conclusion**
    - Summarize the findings and discuss potential improvements or next steps.

## Repository Structure

```plaintext
|-- data
|   |-- transfusion.data
|-- notebooks
|   |-- 01_inspecting_data.ipynb
|   |-- 02_loading_data.ipynb
|   |-- 03_inspecting_dataframe.ipynb
|   |-- 04_creating_target_column.ipynb
|   |-- 05_checking_target_incidence.ipynb
|   |-- 06_splitting_datasets.ipynb
|   |-- 07_selecting_model_using_tpot.ipynb
|   |-- 08_checking_variance.ipynb
|   |-- 09_log_normalization.ipynb
|   |-- 10_training_linear_regression_model.ipynb
|-- src
|   |-- data_processing.py
|   |-- model_training.py
|-- README.md
|-- requirements.txt
```

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kowshik-04/Give-Life-Predict-Blood-Donations.git
   cd Give-Life-Predict-Blood-Donations
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebooks in sequence:**
   Open the notebooks in the `notebooks` directory and run them step by step to reproduce the project workflow.

## Conclusion

This project demonstrates the use of machine learning to predict blood donations. By following the steps outlined, you can replicate the analysis and build a model to forecast blood donations, contributing to more efficient blood supply management.

For any questions or contributions, please feel free to open an issue or submit a pull request.

---

**License:** This project is licensed under the MIT License. See the LICENSE file for more details.

**Contact:** For further information, you can reach out to [kowshik.mente2004@gmail.com].

Happy Coding!
