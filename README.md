
# Housing Price Prediction

The California Housing Prices dataset from the StatLib repository, based on the 1990 California census, was chosen for its educational value in learning data science techniques. Although the data isn't recent, it provides a comprehensive set of features and complexities that make it ideal for demonstrating various data analysis and machine learning processes. For instructional purposes, some modifications were made to the dataset, such as adding a categorical attribute and removing a few features. 

## Overview of Analysis and Techniques Used

#### Data Loading and Initial Inspection:

- Loaded the dataset using pandas and performed an initial inspection to understand the structure and contents of the data.
- Displayed the first few rows of the dataset to get a quick overview.
#### Data Description:

- Used the info() method to summarize the dataset, identifying data types, non-null counts, and potential missing values.
#### Feature Engineering:

- Created a custom transformer CombinedAttributesAdder to add new features that might be useful for the analysis.
- Applied the transformer to the dataset to generate additional attributes.
#### Data Preprocessing Pipelines:

Constructed pipelines to handle numerical and categorical features separately:
- Numerical Pipeline: Included steps for selecting attributes, imputing missing values, adding custom attributes, and standardizing the data.
- Categorical Pipeline: Included steps for selecting categorical attributes and encoding them using a custom label binarizer.
Combined the numerical and categorical pipelines into a full preprocessing pipeline using FeatureUnion.
#### Model Training:

- Trained a Linear Regression model to predict housing prices.
- Trained a Decision Tree Regressor model for the same task.
#### Model Evaluation:

- MSE: Helps identify the average squared error between predicted and actual values. It emphasizes larger errors due to the squaring process.
- RMSE: Provides a more interpretable measure of the error magnitude in the same units as the target variable. It is easier to understand and communicate the model's performance using RMSE.

![Python](https://www.bing.com/images/search?view=detailV2&ccid=WwyDwD0%2b&id=420966F7C6B4E66F291579B789E5E0FCB61C8581&thid=OIP.WwyDwD0-nQxu0Cwn5UGz9wHaFM&mediaurl=https%3a%2f%2fbranditechture.agency%2fbrand-logos%2fwp-content%2fuploads%2fwpdm-cache%2fNumpy-900x0.png&exph=632&expw=900&q=Numpy+Python+Logo&simid=608055554779584824&FORM=IRPRST&ck=ECF43FA37D2E53BB407962B5A3E7C177&selectedIndex=0&itb=1)

![Jupyter](https://www.bing.com/images/search?view=detailV2&ccid=0mCiWTcz&id=7B349F0D530868B1961687576CA1C920DC15F54C&thid=OIP.0mCiWTczNAO4uRHiecvftQHaIr&mediaurl=https%3a%2f%2flogos-download.com%2fwp-content%2fuploads%2f2021%2f01%2fJupyter_Logo.png&exph=5000&expw=4267&q=jupyter+Logo.svg&simid=608022036842818584&FORM=IRPRST&ck=2C0D7EC6317BE3032C42D3A9D741F40F&selectedIndex=0&itb=1)

![Pandas](https://www.bing.com/images/search?view=detailV2&ccid=WprfogNZ&id=F77124F45B166A7F6DCDE80A16E799E2B097C75E&thid=OIP.WprfogNZ-C6vwR5Xe02uxgHaFj&mediaurl=https%3a%2f%2flogowik.com%2fcontent%2fuploads%2fimages%2fpandas8580.logowik.com.webp&exph=650&expw=866&q=pandas+Logo.svg&simid=607988935531765319&FORM=IRPRST&ck=7D2B5464D731B6D386CCFF21C217ACC1&selectedIndex=0&itb=0)

![Numpy](https://www.bing.com/images/search?view=detailV2&ccid=WwyDwD0%2b&id=420966F7C6B4E66F291579B789E5E0FCB61C8581&thid=OIP.WwyDwD0-nQxu0Cwn5UGz9wHaFM&mediaurl=https%3a%2f%2fbranditechture.agency%2fbrand-logos%2fwp-content%2fuploads%2fwpdm-cache%2fNumpy-900x0.png&exph=632&expw=900&q=Numpy+Python+Logo&simid=608055554779584824&FORM=IRPRST&ck=ECF43FA37D2E53BB407962B5A3E7C177&selectedIndex=0&itb=1)



