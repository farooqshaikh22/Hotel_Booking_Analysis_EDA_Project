# Hotel Booking Analysis EDA
The success factoring a profitable hotel industry has been changing over time, driven by global competition and increasingly high customer expectations. Hotels focus on customer satisfaction and to exceed customer expectations. We have a hotel booking dataset containing information for city and resort hotels. This dataset has 32 variables with around 1,19,390 entries. It is collected in order to predict hotel bookings and its probability of cancellation. Some attributes here are to understand what factors do bring in the revenue for the business. Some attributes show the customers preference for booking whereas some attributes show the factors leading to cancellations. We have a hotel booking dataset. We are using our Python skills to perform EDA and gain informative insights about factors in hotel bookings and how they affect hotel booking
In our data study we have 2 types of hotels- the resort type and city hotel type. There are factors in the study which affect the business of the hotels. Factors such as location, ADR, Deposits charged, wait time, etc. We also have channels like distribution channel, Market segment to focus on to get more revenue.
# Project Goal
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. Purpose of our study is to find the best time to book a hotel room. The optimal length of stay in order to get the best daily rate. Study on special requests.We explore and analyze the data to discover important factors that govern the bookings.
# Exploratory Data Analysis:-
In this study we have sample data about the hotel industry that is not processed for use. Unprocessed data gives inaccurate results. To process this data is called data cleaning. We have cleaned the data by handling null values, outliers and dropping unwanted columns.
## Data Cleaning
Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.

Country: - This has null values less than 5% thus the null values are filled with the mode value.

Children and babies: - There are only 4 null values so the null value is filled with mean

## Handling Outliers
An outlier is an extremely high or extremely low data point relative to the nearest data point and the rest of the neighboring co-existing values in a data graph or dataset we work with. We have used the Interquartile range method to handle outliers. To find the interquartile range (IQR), ​we first find the median (middle value) of the lower and upper half of the data. These values are quartile 1 (Q1) and quartile 3 (Q3). The IQR is the difference between Q3 and Q1.

## Data study
i) UNIVARIATE ANALYSIS: Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

ii) BIVARIATE ANALYSIS: Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

iii) MULTIVARIATE ANALYSIS Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.
# Data Visualization :-
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. The graphs used here for study are: -

Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.
# Conclusion :-
* City hotel is most preffered hotel among both hotels.
* 27.5 % bookings got cancelled for both hotels.
* Only 3.9% people are repeated guests.Rest 96.1% are new guests.Thus,we can say that retention rate is very low.
* 82.4% guests were transient type.13.4% were transient party,3.6% contract type and 0.6% were party type.
* Most of the customers (91.6%) do not require car parking space.
* 98.7% guests preffer 'No Deposit' type while booking the hotel.
* Majority of guests(around 28%) coming from portugal. After portugal,Great Britain,France,Spain and Germany are the countries with from which most number of guests comes.
* The percentage of 0 changes made in booking was 81%.
* Waiting time period is high for City hotel.Therefor City hotel is much busier than Resort hotel.
* Most of the bookings happened in 2016 for both hotels.City hotel has more bookings than Resort hotel in 2016.
* August month has highest number of booking cancellation for both hotels as in this month most of the bookings happened. July month has second highest booking cancellation.
* Avg.ADR for City hotel is higher than resort hotel during the year,only in july and august,resort hotel has higher ADR than City hotel.We can say that,City hotel generates more revenue.
* Optimal stay length for both hotel is 7 days.Usually people stays for a week.
* Average lead time for Resort hotel is higher than City hotel.
* Resort hotel has slightly more repeated guest from City hotel.Though the difference is very less.
* 19% guests didn't cancelled their bookings even not getting the same room as per their reservation.Only 2.5% people cancelled their bookings.
