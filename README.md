# Hotel Reservation Cancellation Data Analysis
## About the project
In recent years, City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result, including fewer revenues and less than ideal hotel room use. Consequently, lowering cancellation rates is both hotels’ primary goal in order to increase their efficiency in generating revenue, and for us to offer thorough business advice to address this problem. The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this report.
## About the dataset
The dataset contains booking information for a City Hotel and a Resort Hotel from July 1,2015 to august 31,2017. There are 31 variables that include information such as when the booking was made, whether booking cancelled or not, length of stay, ADR of hotel etc. These variables describe 40,060 observations for the resort and 79,330 observations for the city hotel. This dataset is taken from Kaggle [Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).
## Assumptions
1. No unusual occurrences between 2015 and 2017 will have a substantial impact on the data used.
2. The information is still current and can be used to analyze a hotel's possible plans in an efficient manner.
3. There are no unanticipated negatives to the hotel employing any advised technique.
4. The hotels are not currently using any of the suggested solutions.
5. The biggest factor affecting the effectiveness of earning income is booking cancellations.
6. Cancellations result in vacant rooms for the booked length of time.
7. Clients make hotel reservations the same year they make cancellations.
## Questions for the analysis
1. What are the variables that affect hotel reservation cancellations?
2. How can we make hotel reservations cancellations better?
3. How will hotels be assisted in making pricing and promotional decisions?
## Hypothesis
1. More cancellations occur when prices are higher.
2. When there is a longer waiting list, customers tend to cancel more frequently.
3. The majority of clients are coming from offline travel agents to make their reservations.
## Analysis and Findings

![image](https://user-images.githubusercontent.com/121368375/223601609-c6a83f85-c0b4-4f55-918f-e21699cd6cf9.png)

The accompanying bar graph shows the percentage of reservations that are cancelled and those that are not. It is obvious that there are still a significant number of reservations that have not been canceled. However, there are still 37% of clients who canceled their reservation, which has a significant impact on the hotels' earnings.

![image](https://user-images.githubusercontent.com/121368375/223601699-3fc583ea-a523-4311-95c6-d590ed77f1aa.png)

In comparison to resort hotels, city hotels have more bookings. It's possible that resort hotels are more expensive than those in cities.

![image](https://user-images.githubusercontent.com/121368375/223601732-94ccd900-76ed-455e-9df9-00ab4ca6bab5.png)

The line graph above shows that, on certain days, the average daily rate for a resort hotel is quite high than that of a resort hotel. It goes without saying that weekends and holidays may see a rise in resort hotel rates.

![image](https://user-images.githubusercontent.com/121368375/223601772-7b2621a1-f6f8-4810-82f4-ddea4234b89d.png)

I have developed the grouped bar graph to analyze the months with the highest and lowest reservation levels according to reservation status. As it can be seen, the number of confirmed reservations is highest in the month of August, whereas January is the month with the most cancelled reservations.

![image](https://user-images.githubusercontent.com/121368375/223601827-b3421b39-3584-4130-964a-025f7557378b.png)

This bar graph demonstrates that cancellations are most common when prices are highest and are least when they are lowest. Therefore, the cost of the accommodation is solely responsible for the cancellation.
Now, let's see which country has the highest reservation cancellations. The top country is Portugal with the highest number of cancellations.

![image](https://user-images.githubusercontent.com/121368375/223601890-f124833b-9724-4e8c-b10b-5724b35836b1.png)


Let’s check the market segment from where guests are visiting the hotels and making reservations. Are they coming from Direct or Groups, Online or Offline Travel Agents? Around 47.9% of the clients come from online travel agencies, whereas 20% come from offline travel agencies and tour operators. Only 10% of clients book hotels themselves. The surprising fact is 47% of reservation cancellations are made by customers from online travel agencies and only 4% by direct customers.

 ![image](https://user-images.githubusercontent.com/121368375/223601947-0feb464d-7567-4e37-93fd-2100ff851d40.png)
 
As seen in the graph, reservations are cancelled when the average daily rate is higher than when it is not cancelled. It proves all the above analysis true, that the higher price leads to higher cancellation.
## Suggestions
1. Cancellation rates rise as the price does. In order to prevent cancellations of reservations, hotels could work on their pricing strategies and try to lower the rates for specific hotels based on locations. They can also provide some discounts to the consumers.
2. As the ratio of the cancellation and not cancellation of the resort hotel is higher in the resort hotel than the city hotels. So, the hotels should provide a reasonable discount on the room prices on weekends or on holidays.
3. In the month of January, hotels can start campaigns or marketing with a reasonable amount to increase their revenue as the cancellation is the highest in this month.
4. They can also increase the quality of their hotels and their services mainly in Portugal to reduce the cancellation rate.
## Tools used
Python, Jupyter Notebooks

