# Exploratory_Data_Analysis_Hotel_Booking
This dataset was previously used for My Group Final Project in Bootcamp Data Scientist Rakamin Academy. The assessment from the judges, EDA of our group still had many unexplored aspects. Then, I initiative to lesson more and explore more about the dataset.

# Dataset Source
https://www.kaggle.com/datasets/mojtaba142/hotel-booking

# Dataset Preview
This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.

# Analysis Insight
* The data does not contain major issues. There are only some NULL values and the data do not have duplicated rows. I've handled the null values accordingly.
* Most of the columns have asymmetrical distribution.
* There is an outlier in some variables.
* The majority of the guests' original country of origin is from Europe, with a particular emphasis on Portugal, where the hotel is located.
* From correlation heatmap, there is positive correlation between 'stays_in_weekend_nights' and 'stays_in_week_nights'. And there's a noticeable negative correlation between 'arrival_date_year' and 'arrival_date_week_number'.
