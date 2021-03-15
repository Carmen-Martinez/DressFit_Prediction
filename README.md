## Dress Fit Prediction

The purpose of this project is to predict whether a dress will fit. A common problem in e-commerce stores is not being able to try on the clothes.
This will make it easier for the consumer to know whether the dress will fit and ultimately be confident in buying the dress. From a business perspecitve,
the hopes was to increase sales and decrease returns. 


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

