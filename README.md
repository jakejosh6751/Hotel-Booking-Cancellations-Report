# Hotel Booking Cancellations Report
![hotel_view_banner](https://github.com/jakejosh6751/Hotel-Booking-Cancellations-Report/assets/148710647/49cdea0e-bfc1-45a2-af66-bcb0dbe7f373)

### Project Overview:	
A facility with two hotels, Resort and City, is faced with a dilemma of multiple booking cancellations which greatly cuts down their revenue. The central interest in this data analysis project is to get insight about booking cancellations level, impact on revenue, and sources driving cancellations in order to better manage the situation.

### Data Overview:
The dataset has booking information for Resort and City hotels with Arrival Dates from 2015-2017. The data set contains 119,390 entries and 17 features that include Hotel Booking Date, Arrival Date, Lead Time, Distribution Channel, Customer Type, Country, Deposit Type, Status, Revenue, and Revenue Loss.

### Tools and Skills:
Power BI, PowerPoint, and DAX (DIVIDE, AVERAGE, CALCULATE, COUNT, COUNTROWS, & SUM).

### Data Preparation:
In this dataset, there are no missing values, contaminated, inconsistent, invalid or duplicate entries. 
- A new column named “Lead Category” is created from “Lead Time” with the following groupings;
0-100, 101-200, 201-300, 301-400, 401-500, Above 500 Days.
- A “Date Table” named “Calendar” is generated as shown below;

![date table](https://github.com/jakejosh6751/Hotel-Booking-Cancellations-Report/assets/148710647/1a53bef3-d467-4a2b-a625-a15d3a21371b)

### Data Model:
![data model](https://github.com/jakejosh6751/Hotel-Booking-Cancellations-Report/assets/148710647/2ed5b608-ba99-4323-b44b-2bb93c3d9996)

### Visuals:
![report_page1](https://github.com/jakejosh6751/Hotel-Booking-Cancellations-Report/assets/148710647/f06db293-08b3-46c2-8cc2-714b7c2c815d)

![report_page2](https://github.com/jakejosh6751/Hotel-Booking-Cancellations-Report/assets/148710647/f6db0b17-2d51-45e4-8695-b67383b10e8f)

### Insights:
-	Highest revenue losses are recorded in July and August.
-	Most cancellations come from City Hotel with up to 43% in 2015.
-	The higher the Lead Time, the more likely an imminent cancellation.
-	Highest cancellations in April and June with 40% and 41% respectively.
-	Highest cancellations by key features are; Online Travel Agent (26%), Portugal (22%), Transient (30%), and No Deposit (24% in City and 23% in Resort) for Distribution Channel, Nationality, Customer Type, and Deposit Type respectively.

### Recommendations:
-	To have an objective estimate of future revenues, a deduction of 36% should be done to reflect average percentage of cancelled reservations across all sources.
-	Accept multiple “No Deposit” bookings with high “Lead Days” to reduce revenue losses due to last minute cancellations.
-	More data with parking lots, cuisines and visa policy information for example, might provide more insights regarding cancellations.

