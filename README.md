# ML Linear Regression Assignment - Boombike bikesharing Anaysis - for Productivity Improvement
>Bike sharing system is available for the users in such a way they can carry the bike by paying the amount, take it, traveled with this and return to their destination. **BoomBikes** , US=based bike sharing provider uses such system and wanted to analyse the production data from the above system using the third party who analyse this data and give their feedback towards  more productivity of the system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Provide general information about your project here.**
  As described above, the third party analyze the data uses a ML Linear Regression model to asses the productivity of bike usage and means identify the identifiers which impact the bike share usage of a customer
- **What is the background of your project?**
- Analyse the bikeshare system data with different parameters using ML Linear Regression. Total of Casual and registered which is mentioned in 'Cnt' in the data is used as Target variable in this project.
  - It consists of Data cleaning, mapping, single Linear model testing. Supervised ML model is created and used the Linear regression method for model building.
  - Dummy are variables created (n-1) for season parameter (fall, spring, winter and summer).Casual and registered columns removed since cnt showing the total of these 2 variables. Explained the EDA (Univariate, Bivariate Analysis). Training and test model developed for both single linear model and multi linear model as well.
  - Feature selection done based RFE (Automated) and Manual (p-value, VIF).  
  - R-square, Adjusted R-square are identified for this model
- **What is the business probem that your project is trying to solve?**
  Idenfying the parameters that impact the business productivity is such a complex and using python ML Linear regression model, the third party can show the model parameters and their co-efficient impact the business productivity 
- **What is the dataset that is being used?**
   2018, 2019 Sales data combining the weather report during time taken used in this project. The data of bikeshare counts including registered users and consumed users at different season time is taken for target variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Conclusion 1 from the analysis**
- Multi Linear regression done and variable parameters identified are
- Automated & Manual feature selection worth and gave signficiant improvement for building the model.
- **Conclusion 2 from the analysis**
-  Expression for the model is cnt = 0.2061 + 0.2378 * yr -0.0596 * holiday + 0.0193 * weekday + 0.0193 * workingday -0.1965 * weathersit  + 0.4640 * atemp -0.1498 * windspeed -0.0989 * spring + 0.0282 * summer + 0.0582 * winter
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas version: 2.0.3
NumPy version: 1.24.4
Matplotlib version: 3.7.4
Seaborn version: 0.13.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
The project done based on upgrad lecture and materials

## Contact
Created by [@srinisprojects77] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
