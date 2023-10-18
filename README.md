# EDA-Hotel-Booking-Analysis

**Business Objective**
Main objective is to identify key trends and patterns in the data that can be used to improve business strategies in the hotel industry
Understanding the travel patterns and preferences of their guests is important for hotels in order to make informed decisions about things like peak seasons, common reasons for cancellations, demand for amenities such as parking, and the number of children staying at the property. For many people, traveling is a thrilling and meaningful experience.

**Project Summary -**
This project is related to Hotel Booking having two hotel description i.e City Hotel and Resort Hotel. In this dataset contains total rows 119390 and 32 columns.In this we divide data manipulation workflow in three category Data Collection Data cleaning and manipulation and EDA(Exploratory Data Analysis). As Further moved i.e Data collections first step to find different columns which is done by coding Head(), tail(), info(), describe(), columns() and some others method used for data collections, some of the columns name is updated here i.e hotel,is_canceled,lead_time,arrival_date_year,arrival_date_month,arrival_date_week_number_arrival_date_day_of_month stays_in_weekend_night .As we further moved we find the unique value of each columns and generate a list in tabular form and also checa k the dataset type of each columns' find some columns not inaccurate data types which correct it later done in Data cleaning part and as well as duplicates data items must be removed as we find duplicates items equal to 87396 which is dropped frchecktaset

Before visualize any data from the data set we have to do data wrangling. For that, we have checked the null value of all the columns. After checking, when we are getting a column which has more number of null values, dropped that column by using the 'drop' method. In this way, we are dropped the company' column. When we are find minimal number of null values, filling the null values with necesary values as per requirement by using fillna() Different charts are used for data visualization so that better insights and Business

we used different charts to represent the data set, Bar chart, Pie chart, Count plot, Box and Wishker plot, Density plot, line chart, Coorelation Heat map ect.
