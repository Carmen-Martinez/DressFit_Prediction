## Dress Fit Prediction

The goal of this project is to develop a predictive model that determines whether a dress will fit a customer. One of the main challenges in e-commerce is the inability to try on clothing before purchase. This solution aims to give consumers greater confidence in their sizing, making it easier to make informed buying decisions. From a business standpoint, this initiative is designed to boost sales and reduce return rates, ultimately improving customer satisfaction and operational efficiency.

### Methods Used:
<ul>
<li>Data Cleaning</li>
<li>Descriptive and Inferential Statistics</li>
<li>Data Visualization (matplotlib/seaborn)</li>
<li>Machine Learning Models (logistic regression, random forest, knn)</li>
</ul>
 

### Technologies:
<ul>
<li>Python</li>
<li>Jupyter Notebook</li>
<li>Pandas</li>
<li>Matplotlib/Seaborn</li>
<li>Sklearn</li>
<li>and other relevant libraries</li>
</ul>

### Project Description:
The project was retrieved from kaggle: https://www.kaggle.com/rmisra/clothing-fit-dataset-for-size-recommendation. I specifically used
"Rent the Runways" dataset because it had more to offer in terms of variables. I used pandas for data manipulation and data analysis along
with Matplotlib, Seaborn, Numpy, Scikit-Learn, and Scipy. The most challenging aspect of this dataset was the class imbalance. Originally there
was 3 classes (small, large, fit), most of the observations were under the fit class. To overcome this issue, I merged the small and large classes to
make a 'not fit' class. This improved the class imbalance but it still affected my metrics. Once I finished the notebook I created a separate notebook
using SMOTE. This helped predict the 'not fit' class.

