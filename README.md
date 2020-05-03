# Road Accidents in Austin
Thid repository contains all components of the end-to-end capstone project predicting
the number of auto accidents in specified time and space in Austin city. The repository includes four ipynb files for each sections and two pdf files for each of
final report and final presentation. 

The project includes generating project idea, data collection, statistical inferential
analysis, exploratory data analysis, accident forecast using time series analysis, and
predictive modeling using machine learning algorithms. Number of accidents in particular
time and space was forecasted using auto-regressive integrated moving average (ARIMA).
Supervised machine learning algorithms were also used to predict the number of auto
accidents in city of Austin. Two decision tree based algorithms, Random Forest (RF) and
eXtreme Gradient Boosting (XGB), were implemented. XGB was found to perform the best
with upto 90% accuracy (based on mean absolute error).   


<br>
<br>
Data were collected from different sources:
<li>Traffic report:<br> https://data.austintexas.gov/Transportation-and-Mobility/Real-Time-Traffic-Incident-Reports: 
</li>
<li>Traffic Signals, School Zones and historical landmarks:<br>
    https://data.austin.gov</li>
<li>US holidays: <br> 
    https://kaggle.com</li>
<li> Weather related data: <br> https://api.darksky.net. </li>


<br>
<br>

Files:
<li> data_wrangling_project1.ipynb: --> Data wrangling and cleaning</li>
<li> statistical_inference_project1.ipynb --> Statistical Analysis</li>
<li> exploratory_data_analysis_project1.ipynb --> Data Story telling and Explorary Data Analysis</li>
<li> Time_Series_and_Predictive_Models.ipynb: --> Time series analysis and Machine Learning models</li>




Deliverables:
<li> Report_Road-Accident-Austin.pdf: --> Final report for the project includes all details and outcomes
<li> Slides.pdf: --> Presentation slides
<br>
<br>   
 
Conclusion: 
Auto accident counts in the city of Austin at various spatiotemporal resolutions were predicted using two different machine learning models and time series analysis. Extreme gradient boosting (XGB) model outperformed the other models. Random forest (RF) model performs far better than the autoregressive time series model ARIMA. All models predicted the spatial accidents better than temporal accident data. 
