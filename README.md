# EDA on Hotel-Booking-Analysis

**Project Summary**

There are several factors which affects the hotel booking by the customers such as type of hotel whether it
is city hotel or resort hotel, time of booking, seasonal rates, length of stay and many more. The trends in
these factors affects the profitability of the hotel. Second thing that may come into action is the cancellation
of bookings due to variation in these factors across the time. Our Analysis leads one to understand the
governing factors which plays the major role during the bookings by the customers.
Following steps that involved during our Analysis are as follows:

**Data Exploring:**

The given dataset is been uploaded in the collab notebook by using csv file format function. Next step was
importing libraries which were Pandas, NumPy, Matplotlib and Seaborn. After uploading the dataset, we
have gone through the data that describing columns and rows where around 119390 rows and 32 columns
are present. Also using info and describe function we get know regarding the different datatypes and the null
values present in the given data set.

**Data Cleaning and Manipulation:**

Now for the analysis it was important to simplify the data as we can so we move further with replacing the
Nan values with 0 in Company, Agent and Children column and other in Country column. Also, there were
many duplicate data presents in the given dataset which has been removed by us by using drop function.
Datatype of ‘reservation status date’ is changed from String object to Datetime. Finally, we manipulated with
incorrect values of people leaving the room by dropping these rows which was recorded as Zero.

**Exploratory Data Analysis (EDA):**

We have down Univariant and Bivariant Analysis of the given data. Major guest preferred city hotel as
compare to the resort and peak time of booking of city hotel is July and August. Agent ID 9 is most efficient
agent having more than 28700 bookings. Guest from Portugal have major visits and mostly preferred system
by the guest is BB type. Major booking was of A, D, E room types while luxury rooms F, G, H are less
preferred but sill they are profitable to hotels. During Analysis we come to know that as special requests
increases, the average adr also increase. Cancellation of City hotels are more as compare to Resort hotel
but loss in adr due to this cancellation is vice versa. Also, people preferred No Deposit mode while booking
which was almost 99% which may be one of the major reasons of cancellation of bookings.

**Conclusions** :

1. 61.1% of guests preferred City hotel and 38.9% of guests preferred Resort hotel hence most preferred hotels are 'City Hotel'
2. In 2016 maximum number of guests visited the hotels and 2015 was the worst performing year for the hotels
3. 79.1% bookings were made through TA/TO (travel agents/Tour operators).
4. 98.7% customers loved to use 'Non Deposite' Type.
5. 27.5% of total bookings were cancelled.
6. TA/TO distribution channels have highest number of cancellation which is about 21400 including Resort Hotel and City Hotel
7. Hotels should take some charges for bookings. We can see that as soon as some kind of charges are taken the number of cancellations decreases drastically. 
8. BB( Bed & Breakfast) is the most preferred  type of meal by the guests
9. Agent Id 9 has done most number of bookings
10. Maximum number of guests were from Portugal, i.e. more than 25000 guests.
11. Only 3.9 % people were revisited the hotels. Rest 96.1 % were new guests. Thus retention rate is low.
12. August and July are the busiest months of the year. It may be because of the ''vacation'' and also a lot of ''festivals''come in these months.
13. City hotel have high adr as compared to Resort hotel. Hence they are more profitable.
14. We can observe that as the number of special requests increases the avg adr also increases.
15. Lead time for 'Resort Hotel' is more in the month of June and September and for 'City Hotel' lead time is more in July and August.
