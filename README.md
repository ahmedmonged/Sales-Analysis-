# Sales-Analysis-
Set of real world data science tasks completed using the Python Pandas library

## Setup

To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html 

## Background Information:

In this project we use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

After we analyzed the data and reached findings we used Power BI to visualize the data and our findings with taking into consideration the following:
- Plotting different types of charts and choosing the appropriate one based on the type and the nature of the data we want to illustrate
- making sure to select suitable and easy-to-understand plot 
- make sure to use non-distracting colors or too many of them to keep the attention focused
- creating a dashboard that contains all necessary plots to make a connection between findings 

The final step is to create a full analysis report that is easy to read and understand for any non-technical reader, which contains the following:
- Description of the project and data
- Stating key points and Questions we are answering
- Answering in detail each question in addition to adding the necessary plots
- Stating our findings and important information found
- Add recommendations and suggestions based on the data and our findings to improve 
