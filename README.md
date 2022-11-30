<h1> Appliances Energy Prediction </h1>

![image](https://user-images.githubusercontent.com/98526274/204726225-cdd17f12-10c5-485b-970d-16d71a3e56ee.png)

<h2> :floppy_disk: Problem statement </h2>
The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters.Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Random Forest Regressor </h2>
Random forest Regressor is Supervised Machine learning Algorithm. It is uses the Bagging Technique. This algorithm gives the best result using hyper parameter tuning on this dataset.  It is a set of decision tree randomly selected subset of training set and then for regression, It is collect all the output from the number of decision tree and find the mean of all the decision tree output, that is the output of rendom forest regressor.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
Appliances energy Prediction.ipynb file is Google colab file that can be run directly on google colab and this file can also be download and run on localy usinf VS code or Jupyter notebook.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Steps performed On dataset and Conclusion </h2>

As first step Performed data Preprocessing and clean the data, handled the missing values.

Performed EDA on different features in dataset, to observe trend and relation between features.

By using VIF removed multicollinearity of features.

After the EDA part, for model prediction split the data in train and test.

Train the data on some algorithms as Linear regression, Lasso and Ridge regression, Support vector machine, and Random forest Regressor, among all the Rendom forest regressor gives the best performence on data.

Rendom forest regressor gives the r2 score of 0.54 on test data.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2 id="credits"> :scroll: Credits</h2>

Milan Ajudiya | Data Scientist | Machine Learning Engineer | Data Science enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/milan-ajudiya)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/milanajudiya)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/me/stories/public)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1SQH0Hi2GxmWMB2ia-IDDtpIV2cZzvRL2/view?usp=sharing)
