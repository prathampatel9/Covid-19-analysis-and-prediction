# Covid-19-analysis-and-prediction
In this pandemic time everyone wants to know when humanity will be relieved of the crisis. Here we used the data from MOHFW and used it for analysis and prediction for future cases.


 

Shri Vaishnav Vidyapeeth VishwaVidyalaya



Project Topic                                                                             “COVID-19 ANALYSIS AND PREDICTION”







        Submitted by:-
•	Bhavishya Lohia 
•	Hardik Soni
•	Kritika Patidar
•	Pratham Patel
Department of Computer Science
July-August 2020

A PROJECT REPORT OF INDUSTRIAL TRAINING AT
WebTek Labs Pvt. Ltd.
SUBMITTED IN FULFILLMENT OF THE REQUIREMENT FOR THE AWARD
OF THE DEGREE OF BACHELOR OF TECHNOLOGY
COMPUTER SCIENCE & ENGINEERING


 

    Submitted by: -
•	Bhavishya Lohia
•	Hardik Soni
•	Kritika Patidar
•	Hardik Soni


July-August 2020
	 
CANDIDATE'S DECLARATION




We hereby declare that we have undertaken industrial training at “WEBTEK LABS PVT. LTD.” during a period from 26 July 2020 to 16 August 2020 in partial fulfillment of requirements for the award of degree of B.Tech (COMPUTER SCIENCE & ENGINEERING) at SVVV Institute, Indore(M.P.) The work which is being presented in the training report submitted to Department of Information Technology at SVVV Indore, is an authentic record of training work.



  


Student Name’s:-

•	Bhavishya Lohia
•	Hardik Soni
•	Kritika Patidar
•	Pratham Patel













ACKNOWLEDGEMENT


It gives us great pleasure to acknowledge the guidance, assistance and support of Ms. Mousita Dhar in making the Project and this Project report successful, which has been structured under her valued suggestion.
She has helped us to accomplish the challenging task in a very short period of time.
Finally, we express the constant support of our friends, family and professors for inspiring us throughout and encouraging us.


   Student Name’s:-                                                  

•	Bhavishya Lohia
•	Hardik Soni
•	Kritika Patidar
•	Pratham Patel

  
CERTIFICATE OF APPROVAL




The project “COVID-19 ANALYSIS AND PREDICTION” made by the efforts 
of our team members is hereby approved as a creditable study for the Bachelor of 
Technology in COMPUTER SCIENCE ENGINEERING and presented in a 
manner of satisfactory to warrant its acceptance as a prerequisite to the degree for 
which it has been submitted. It is understood that by this approval the undersigned 
this project only for the purpose for which it is submitted.























                


                                                               Ms. Mousita 
                                                          (Project In- charge)



1.INTRODUCTION

1.1 PYTHON


About Python:

•	Python is a high-level, general-purpose, open source, strictly typed programming language. The language provides constructs intended to enable clear programs on both a small and large scale.

•	Python was created By Guido van Rossum.

•	The Python Software Foundation (PSF) is the organization behind Python.

Python versions:

•	First released in 1991.

•	Python 2.0 was released on 16 October 2000

•	Python 3.0 was released on 3 December 2008


Current Versions:

•	3.6.3

•	2.7.14
•	3.7 (we are using this version)

Python features:

Some of the features of python include :-

•	Easy to understand

•	Dynamic

•	Object oriented

•	Multipurpose

•	Strongly typed

•	Open Sourced

 
Python is mainly used in many domains:



•	Web Development

•	Data Analysis

•	Machine Learning

•	Internet Of Things

•	GUI Development

•	Image processing

•	Data visualization

•	Game Development

IDLE:
IDLE is an integrated development environment for Python, which has been bundled with the default implementation of the language.

1.2 Anaconda
Anaconda is a open source Distribution for data science and machine learning using python. It includes hundreds of popular data science packages and the conda package and virtual environment manager for Windows, Linux, and MacOS. Conda makes it quick and easy to install, run, and upgrade complex data science and machine learning environments like scikit-learn, TensorFlow, and SciPy. Anaconda Distribution is the foundation of millions of data science projects as well as Amazon Web Service Machine Learning AMIs and Anaconda for Microsoft on Azure and Windows.




       
                             

 


1.3 Packages


1.3.1 NumPy

NumPy is the fundamental package for scientific computing with Python.

It contains among other things:

•	a powerful N-dimensional array object

•	sophisticated (broadcasting) functions

•	tools for integrating C/C++ and Fortran code

•	useful linear algebra, Fourier transform, and random number capabilities

Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

                 







1.3.2 Matplotlib

Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shell, the jupyter notebook, web application servers, and four graphical user interface toolkits.

Matplotlib has a procedural interface named the Pylab, which is designed to resemble MATLAB, a proprietary programming language developed by MathWorks. Matplotlib along with NumPy can be considered as the open source equivalent of MATLAB.

                                          



















 






               





 
Matplotlib tries to make easy things easy and hard things possible. You can generate plots, histograms, power spectra, bar charts, error charts, scatterplots, etc., with just a few lines of code.

For simple plotting the pyplot module provides a MATLAB-like interface, particularly when combined with IPython. For the power user, you have full control of line styles, font properties, axes properties, etc, via an object oriented interface or via a set of functions familiar to MATLAB users.

1.3.3 Scikit-learn

Scikit-learn provides machine learning libraries for python.Some of the features of Scikit-learn includes:

•	Simple and efficient tools for data mining and data analysis

•	Accessible to everybody, and reusable in various contexts

•	Built on NumPy, SciPy, and matplotlib

•	Open source, commercially usable - BSD license

             







1.3.4 Pandas

Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

Pandas library is well suited for data manipulation and analysis using

python.  In  particular,  it  offers  data  structures  and  operations  for

manipulating numerical tables and time series.

        

1.3.5 Seaborn

Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics. E.g:-































Heatmap(above) & Violinplot(below)






































 
1.3.6  Folium
 The Folium library in Python helps us analyze the location and geospatial data with ease and lets us create interactive maps.
Folium makes it easy to visualize data that’s been manipulated in Python on an interactive leaflet map. It enables both the binding of data to a map for choropleth visualizations as well as passing rich vector/raster/HTML visualizations as markers on the map.
The library has a number of built-in tilesets from OpenStreetMap, Mapbox, and Stamen, and supports custom tilesets with Mapbox or Cloudmade API keys. folium supports both Image, Video, GeoJSON and TopoJSON  overlays.
 
        





1.3.7 Plotly

Plotly Python Open Source Graphing Library.Plotly's Python graphing library makes interactive, publication-quality graphs. Examples of how to make line plots, scatter plots, area charts, bar charts, error bars, box plots, histograms, heatmaps, subplots, multiple-axes, polar charts, and bubble charts. Plotly is one of the highly important python libraries to master for data visualization which is interactive and easier to export to the cloud. 
Ex of pie chart-
  
1.3.8 Plotly.Express

The plotly.express module (usually imported as px) contains functions that can create entire figures at once, and is referred to as Plotly Express or PX. Plotly Express is a built-in part of the plotly library, and is the recommended starting point for creating most common figures. Every Plotly Express function uses graph objects internally and returns a plotly.graph_objects.     
1.3.9 Plotly Graph Objects

The figures created, manipulated and rendered by the plotly Python library are represented by tree-like data structures which are automatically serialized to JSON for rendering by the Plotly.js JavaScript library. These trees are composed of named nodes called "attributes", with their structure defined by the Plotly.js figure schema, which is available in machine-readable form. The plotly.graph_objects module (typically imported as go) contains an automatically-generated hierarchy of Python classes which represent non-leaf nodes in this figure schema. The term "graph objects" refers to instances of these classes.

1.3.10 Cufflinks

Cufflinks is another library that connects the Pandas data frame with Plotly enabling users to create visualizations directly from Pandas. The library binds the power of Plotly with the flexibility of Pandas for easy plotting.
 



2. TRAINING WORK UNDERTAKEN



ABOUT PROJECT

According to the World Health Organization (WHO),a new variant of corona virus has caused pneumonia outbreak in Wuhan, China. 
Everyone is aware about the Corona Virus as whole the world is going through this pandemic. So in this situation, many countries suffered a lot, many people died and there’s a huge loss in economy throughout the world. Of course, one has to take safety measures to prevent from this virus .
In this project, we have analyzed the total corona cases till latest dates, death rates, active cases, and recovered cases of countries and with a brief details about India. Also using libraries and modules, we have tried to show the situation using graphs and maps.
         
             
2.1 COLLECTING DATA FROM KAGGLE

Kaggle is a platform for predictive modelling and analytics competitions in which statisticians and data miners compete to produce the best models for predicting and describing the datasets uploaded by companies and users. This crowd sourcing approach relies on the fact that there are countless strategies that can be applied to any predictive modelling task and it is impossible to know beforehand which technique or analyst will be most effective. On 8 March 2017, Google announced that they were acquiring Kaggle. They will join the Google Cloud team and continue to be a distinct brand. In January 2018, Booz Allen and Kaggle launched Data Science Bowl, a machine learning competition to analyze cell images and identify nuclei.



2.2 DATA SCIENCE


Data science is an interdisciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from data in various forms, both structured and unstructured, similar to data mining. Data science is a "concept to unify statistics, data analysis, machine learning and their related methods" in order to "understand and analyze actual phenomena" with data. It employs techniques and theories drawn from many fields within the context of mathematics, statistics, information science, and computer science.




Turing award winner JiGray imagined data science as a "fourth paradigm" of science (empirical, theoretical, computational and now data-driven) and asserted that "everything about science is changing because of the impact of information technology" and the data deluge. When Harvard Business Review called it "The Sexiest Job of the 21st Century" the term became a buzzword, and is now often applied to business analytics, business intelligence, predictive modeling, or any arbitrary use of data, or used as a glamorized term for statistics. In many cases, earlier approaches and solutions are now simply rebranded as "data science" to be more attractive, which can cause the term to become "dilute[d] beyond usefulness." While many university programs now offer a data science degree, there exists no consensus on a definition or suitable curriculum contents. Because of the current popularity of this term, there are many "advocacy efforts" surrounding the field. To its discredit, however, many data science and big data projects fail to deliver useful results, often as a result of poor management and utilization of resources.











2.3 SOURCE CODE & OUTPUT



1. IMPORT PACKAGES
import pandas as pd
import matplotlib.pyplot as plt
from matplotlib import style
style.use('ggplot')
%matplotlib inline
import plotly
import plotly.express as px
import plotly.graph_objects as go
plt.rcParams['figure.figsize']=17,8
import cufflinks as cf
import plotly.offline as pyo
from plotly.offline import init_notebook_mode,plot,iplot
import folium

2. LOAD THE DATASET

df = pd.read_csv(r"C:\Users\bhavi\Desktop\New folder\covid_19_data.csv")

 

DATA PRE-PROCESSING AND DATA ANALYSIS

1.Counting missing values for different columns

df.isnull().sum()

 

2. Since two columns SNo & Last Update are of no use so we are dropping them.

  
3.Collecting the data of latest date i.e max date among all the dates.

 

4. Now, we have grouped country region and cases . Total confirmed cases of countries

 


5.	Grouping total Recovered cases

 

6.	Grouping from 22/01/2020 till 12/08/2020

 




7.	Renaming Observation Date as Date

 

8.	Summing up values of total confirmed cases according to particular date

 


9.	Summing up values of total Deaths according to a particular date

 

10.	 Summing up  values of total Recovered  according to particular date

 






11.Plotting graphs

•	Treemap of all the Cases

  
 



•	Covid-19 CDR Graph


 













12.Reading new file for getting Longitude and Latittude for folium

 

13. Merging two files with the help of common column latitude

 




14.Plotting graph 

fig=px.density_mapbox(df_latlong,lat="Lat",lon="Long",hover_name="Country/Region",animation_frame='Date',color_continuous_scale='Portland',radius=7,zoom=0,height=700)
fig.update_layout(title='WorldWide Corona Cases')
fig.update_layout(mapbox_style="open-street-map",mapbox_center_lon=0)
fig.update_layout(margin={'r':0,'t':0,'l':0,'b':0})



 









15.Top 10 Worst Affected Countries By Corona

Grouping the countries on the basis of their region and names and summing up total values of Deaths, Recovered, and Confirmed cases of top 10  countries that are worst affected.

 

From here it is analyzed that US is the most affected country followed by  BRAZIL and INDIA.












16. Pie-Chart Representation

16.1 CONFIRMED CASES OF TOP 10 AFFECTED COUNTRIES

fig=px.pie(df_countries, values='Confirmed', names='Country/Region', title='Top 10 Countries:- Confirmed Cases')
fig.show()


 








16.2 DEATHS   OF TOP 10 AFFECTED COUNTRIES


fig=px.pie(df_countries, values='Deaths', names='Country/Region', title='Top 10 Countries:- Death Cases')
fig.show()



 










16.3  RECOVERD CASES  OF TOP 10 AFFECTED COUNTRIES

fig=px.pie(df_countries, values='Recovered', names='Country/Region', title='Top 10 Countries:- Recovered Cases')
fig.show()



 














17. LinePlot

17.1 Getting ploting trend for 10 top countries

 
Renaming column ‘confirmed_x’ as ‘confirmed, ‘Deaths_x’ as ‘Deaths’,’Recovered_x’ as Recovered.

 

17.2 COVID19 Confirmed Cases growth for top 10 worst affected countries

fig = px.line(df_trend, x='Date', y='Confirmed', color='Country/Region', title='COVID19 Confirmed Cases growth for top 10 worst affected countries')
fig.update_layout(hovermode='closest',template='seaborn',width=700,xaxis=dict(mirror=True,linewidth=2,linecolor='black',showgrid=False),
                 yaxis=dict(mirror=True,linewidth=2,linecolor='black'))
fig.show()


 










17.3 COVID19 Death Rate growth for top 10 worst affected countries


fig = px.line(df_trend, x='Date', y='Deaths', color='Country/Region', title='COVID19 Death Rate growth for top 10 worst affected countries')
fig.update_layout(hovermode='closest',template='seaborn',width=700,xaxis=dict(mirror=True,linewidth=2,linecolor='black',showgrid=False),
                 yaxis=dict(mirror=True,linewidth=2,linecolor='black'))
fig.show()


 










17.4 COVID-19 Recovery growth for top 10 worst affected countries

fig = px.line(df_trend, x='Date', y='Recovered', color='Country/Region', title='COVID19 Recovery growth for top 10 worst affected countries')
fig.update_layout(hovermode='closest',template='seaborn',width=700,xaxis=dict(mirror=True,linewidth=2,linecolor='black',showgrid=False),
                 yaxis=dict(mirror=True,linewidth=2,linecolor='black'))
fig.show()

 












Analysis Of India Over Covid19 Pandemic

Reading new file 

 

Data Preprocessing and Data Analysis

1. Checking missing values

 

2. Dropping column SNo and Time

 







3. State wise representation according  to last observed date


 


             

4. Grouping Total cases observed in particular state according to Confirmed,Active,Cured,Deaths  

Total_Cases=df1_Obser.groupby('State/UnionTerritory')['Confirmed','Cured','Deaths','Active Cases'].sum().sort_values('Confirmed',ascending=False).reset_index()

            
                       















•	Plotting the graphs:-

 

 









 


 








Top 12 Worst Affected States of India

df1_states = Total_Cases.reset_index().groupby('State/UnionTerritory', as_index=False)['Confirmed','Deaths',"Cured","Active Cases"].sum()
df1_states = df_states.nlargest(12,'Confirmed')
df1_states.style.background_gradient(cmap="Purples")

                     

Here it is seen that Maharashtra is the most affected state followed by Tamil Nadu and Delhi

•	Renaming column name 

Indian_Cord.rename(columns={ 'Name of State / UT':'State/UnionTerritory'}, inplace=True)



•	Merging two files 

 


Here, the files are merged to get latitude and longitude of the map of India so as to plot the reflected cases with it.


















•	Plotting map

map = folium.Map(location=[20,70],zoom_start=4,tiles='cartodbdark_matter')
for lat,long,value,name in zip(df1_full['Latitude'],df1_full['Longitude'],df1_full['Confirmed'],df1_full['State/UnionTerritory']):
    folium.CircleMarker([lat,long],radius=value*0.0009,popup=('<strong>State<strong>:'+str(name).capitalize()+'<br>''<strong>Total Cases</strong>:'+str(value)+'<br>'),color='red',fill_color='red',fill_opacity=0.3).add_to(map)


 








•	Pie-Charts

 

 



•	Tree-Maps

 
 







 
From the Above Data , We can Conclude that :-
1)Maharashtra failed to contain the spread of virus, and is the worst affected state of India.
2)Although Tamil-Nadu is 2nd worst affected state of India,still it has least amount of Deaths.
3)Gujurat on the other hand,has 2nd highest death rate and also one of the top 5 worst States.
4)Delhi has the Second Highest Active Cases regarding other states.
5)Lockdown has Prevented the increase in the no of cases in different states, but still Maharashtra is the grip of Covid-19 virus firmly.














Machine Learning Models Used In Project:

1. Linear Regression 
Linear regression is one of the easiest and most popular Machine Learning algorithms. It is a statistical method that is used for predictive analysis. Linear regression makes predictions for continuous/real or numeric variables such as sales, salary, age, product price, etc.
Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (y) variables, hence called as linear regression. Since linear regression shows the linear relationship, which means it finds how the value of the dependent variable is changing according to the value of the independent variable.

Graph of linear regression looks like-
 




2. Polynomial Regression

o	Polynomial Regression is a regression algorithm that models the relationship between a dependent(y) and independent variable(x) as nth degree polynomial. The Polynomial Regression equation is given below:
y= b0+b1x1+ b2x12+ b2x13+...... bnx1n
o	It is also called the special case of Multiple Linear Regression in ML. Because we add some polynomial terms to the Multiple Linear regression equation to convert it into Polynomial Regression.
o	It is a linear model with some modification in order to increase the accuracy.
o	The dataset used in Polynomial regression for training is of non-linear nature.
o	It makes use of a linear regression model to fit the complicated and non-linear functions and datasets.
o	Hence, "In Polynomial regression, the original features are converted into Polynomial features of required degree (2,3,..,n) and then modeled using a linear model."
o	 







3. Support Vector Machine
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.
The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.
SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine. Consider the below diagram in which there are two different categories that are classified using a decision boundary or hyperplane:
Graph of svm:-
 








Conclusion :-


 For World Analysis of Covid-19

1)China was the first country to experience the onset of virus and it failed to contain it .
2)US,Brazil,India and Italy, which are the worst affected countries currently didn't record many cases in January. This shows that how fast the virus spreads.
3)Brazil may have the second highest amount of confirmed cases, but the recovery rate of Brazil is far more better than any
country.
4)US is the worst affected country by Covid-19, and has recorded highest amount of deaths.
5)Lockdown in China has Able to eradicate the Covid-19 Cases,Although India was able to control the cases through lockdown till june , but after that there is spike in cases and now it is the 3rd worst affected Country

For Indian Analysis of Covid-19

1)Maharashtra failed to contain the spread of virus, and is the worst affected state of India.
2)Although Tamil-Nadu is 2nd worst affected state of India,still it has least amount of Deaths.
3)Gujarat on the other hand,has 2nd highest death rate and also one of the top 5 worst States.
4)Delhi has the Second Highest Active Cases regarding other states.
5)Lockdown has Prevented the increase in the no of cases in different states, but still Maharashtra is the grip of Covid-19 virus firmly.

Prediction of Covid19

This project involved three supervised learning algorithms i.e. Linear Regression, polynomial Regression and SVM. All of them have different accuracy score. I got most score in SVM but it may vary depending upon datasets.

I concluded that my prediction was most accurate using SVM.







REFERENCES

https://www.kaggle.com/
https://www.python.org/
https://anaconda.org/anaconda/python/
http://www.numpy.org/
https://matplotlib.org/
http://scikit-learn.org/
https://pandas.pydata.org/
https://pyplot.com
https://folium.org
