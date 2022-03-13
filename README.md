## <h2 align="center"> <hr/>World Wide Covid-19 Analysis , Visualization and Prediction Using ML Model vs pandemic Model<hr/> </h2>

<h2 align= "center">Introduction</h2>
 
> <p align="justify"> COVID-19 has essentially spread over the world and thinks of new difficulties to the examination local area. Despite the fact that legislatures forcing various control and social separating measures, the requirement for the medical services frameworks has significantly expanded and the powerful administration of contaminated patients turns into a difficult issue for emergency clinics.</p>

<h2 align= "center">Problem Statement </h2>
 
> <p align="justify"> The need for the healthcare systems has increased and the effective management of infected patients becomes a challenging problem for hospitals. In this manner, Forecasting of the number of the quantity of new polluted and recuperated cases is pivotal for advancing the accessible assets and capturing or hindering the movement of such diseases.</p>

> <p align="justify">Machine learning models showed significant upgrades when dealing with time - arrangement information in various applications. Near investigation of Three Machine learning techniques to figure the quantity of new cases and death cases.</p>

<h2 align= "center">Solution Approach</h2>
 
> **<p align="justify"> inear Regression(LR), Polynomial Regression, Support Vector Machine(SVM) and Pandemic Model.** calculations have been applied for estimating of COVID-19 cases dependent on a little volume of information. This investigation depends on 48 weeks affirmed and demise cases gathered.</p>

<h2 align= "center"> Flow Diagram of purposed solution:</h2>
<img src="./Image/flow Chat.png" alt="iagrammatic Approch for the workflow of proposed methodology" width="100%" height="350px"/>

> _Diagrammatic Approch for the workflow of proposed methodology._

> <p align="justify">The Dataset consisted of .csv file and lots of Unkown and Missing values so first step to Pre-processing our data then transform our data into input format and split the data into two parts ,20% data for testing and 80% data for training. Trained our Model using 80% of data and Four Machine Learning Algorithms which Algorithms are Linear Regression (LR) , Support Vector Machin (SVM) ,Polynomial Regression(PR), Ridge and Based on the Model We are evaluating some Parameters then our model Predict the next 10 days Data and compaire with Prebuild models.</p>

<h2 align= "center">DataSet</h2>

> <p align="justify">We are collecting datasets from Github website Link: <a href="https://github.com/CSSEGISandData/COVID-19" >https://github.com/CSSEGISandData/COVID-19 </a> which have four CSV file thats include confirmed,deaths and recovery cases in first three files. Last file which have cover all recent data of covid cases world wide that have 3983 rows and 14 features.</p>

<h2 align= "center">Result</h2>

> <p align="justify"> I have applied various algorithms like: Linear Regression , Support vector machine ,Polynomial regression and Ridge but i got best result in Polynomial and Ridge by comapairing Mean Square Eror and Mean Absolute Error then compute the next 10 days covid19 cases. After that i have applied SIR and SEIR model. In SEIR model which is based on some conditions like Lockdown in Regions , population in region, number of hospitals and availability in hospitals, number of chambers in ICU and based on the Age groups calculating the number of cases , number of deaths and number of hospitalized people in particular region. In SIR model which is based on some parameters like : Beta and Gamma . First i have to predict beta and gamma values based on previous data,population in region. Beta and gamma predicted value calculated through machine learning algorithm which is best results in previouse case then forcating future values.</p>

<h2 align= "center">Conclusion</h2>

> <p align="justify">I have applied both Pandemic model and machine learning models. If we are going through machine learning model then we may be need to apply four to five machine learning algorithms then compaire with each other and find the best one. Other case we have to go pandeemic model and easily find the forcating values for futures.</p>

---

 <h2 align="center"> ** Thank YOU ** </h2> 
 
 ***
