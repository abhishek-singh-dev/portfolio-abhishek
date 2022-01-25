# Portfolio-S1-2021
Portfolio template repository for COMP6200: Data Science at Macquarie University
This repository will hold your portfolio projects for this semester. You should customise this README.md file to document your own work - add your name and details and describe what you've done. This will be displayed on your Github page.

Student Name: **ABHISHEK KUMAR SINGH**

Portfolio projects:

  ## Portfolio 1 : 
  
An analysis of cycling information got from the applications Strava and GoldenCheetah. The two datasets were joined utilizing the join technique in Pandas to frame one dataset for analysis. This portfolio 1 explores and cover the connections between different variables, 
For example :
* Distance, 
* Average Speed, 
* Heart Rate, 
* Training Stress Score, 
* Avergage Power, 
* Workout Type,
* Elevation Gain.
*Techniques / Functionalities : **

* Combined two frames using inner join method. 
 
* Extracted rides with only measured power (where device_watts is True) along with a count relationship bar graph between three workout types.
 
* Distributions of some key variables using Histogram.
![Histogram of various categories in workout category](/data/Histogram_Port1.png)

* Found relationship between variables using Pair plot.

* Extracted weather data for 2018 and 2019 to explore relationship between rides and weather dataset


  
  ## Portfolio 2 :
  
  Predicting the energy usage of a house based on Internet of Things (IoT) measurements of temperature and humidity and weather observations.
The combined data set is split in training and test validation using CARET’S create data partition function. 75% of the data is used for the training of the models and the rest is used for testing.

Results in the portfolio include:

* Appliances energy consumption distribution :

 a) Histogram
 ![Histogram](/data/Histogram.png)
 
 b) BoxPlot

* Appliances energy consumption measurement :

 a) For the whole period,

 b) A closer look at the first week of data

* Correlation Matrix to visualize the relationship between the energy consumption variables

 a) Between the energy consumption variables of Appliances with lights, T1, RH1, T2, RH2, T3, RH3. T1 and RH1.
 ![Pair Plot](/data/PairPlot_1.png)
 
 b) Between the energy consumption variables of Appliances with T4, RH4, T5, RH5, T6, RH6.
 c) Between the energy consumption variables of Appliances with T7, RH7, T8, RH8, T9, RH9.
 d) Between the energy consumption variables of Appliances with T_out, Pressure, RH_out, Windspeed, Visibility, Tdewpoint, NSM and T6.

* HeatMap plot : It replicates the authors plot of 4 consecutive weeks of data to identify any time trends. 
  ![Heat Map](/data/HeatMap.png)

**Applied Linear regression on train and test**
* Calculated **EVALUATION METRICS** scores.
 
 * Applied **Recursvie Feature estimation (RFE)** to remove features one by one and evaluates the model each time to find the best target      number of features.
 
 * Performance of linear regression model
  ![Recursvie Feature estimation (RFE) Plot](/data/RFE_plot.png)
* Recursvie Feature estimation (RFE) graph
 
  
 
  ## Portfolio 3 :

Portfolio 3 looks at classification. Using MultinomialNB and SVM Model, classification models were produced to see which model works better with the book summary dataset.
 
 Applied following techniques : 
 
 * Data Preparation
 
 * Feature Exaction
 
 * Train model on Book summary dataset
 
 * MultinomialNB Model : Calculated below metrics score for -
 
  1 ) Model Accuracy score
  2 ) Classification report for SVM Model
  3 ) Confusion matrix for SVM Model
  
* SVM  : Calculated below metrics score for -

  1 ) Model Accuracy score
  2 ) Classification report for SVM Model
  3 ) Confusion matrix for SVM Model

  
**Predicting the Genre of Books from Summaries** - Accuracy of MultinomialNB Model is 0.61 and the accuracy of SVM Model is 0.70. Since various calculations and models may discover various scores for the book rundown dataset yet thusly I present my discoveries from the above model expectation dependent on - SVM Model and MultinomialNB Model. As we can see from above exactness score - SVM Model is superior to MultinomialNB Model as the SVM model is powerful and found out about the information accurately. Aside from that, Precision score, Recall score and f1-score for SVM model is high contrasted with MultinomialNB model where we can foresee that our information is works best with SVM Model. Higher the F1, Recall and Precision score, there is higher extent of the information focuses that we anticipated effectively
