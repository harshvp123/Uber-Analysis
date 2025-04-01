# Uber-Analysis
Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.

KPI’s:

1.Total Bookings – How many trips were booked over a given period?

2.Total Booking Value – What is the total revenue generated from all bookings?

3.Average Booking Value – What is the average revenue per booking?

4.Total Trip Distance – What is the total distance covered by all trips?

5.Average Trip Distance – How far are customers traveling on average per trip?

6.Average Trip Time – What is the average duration of trips?

Expected Outcomes:

✔ Determine patterns in ride reservations and income production.

✔ Examine how efficient the travel is in terms of length and distance.

✔ Examine booking values and travel trends over time.

✔ Offer suggestions to enhance pricing strategies and boost client happiness.

CHART’s:
Create a Measure Selector using a Disconnected Table with the following values:

1.Total Bookings

2.Total Booking Value

3.Total Trip Distance

Then, use a measure to dynamically update the visualizations based on user selection.

1.By Payment Type (Card, Cash, Wallet, etc.)

2.By Trip Type (Day/Night)

Additional Enhancements:

1.Dynamic Title –Adapt the chart title to the chosen metric.

2.Slicers – For a more thorough examination, include interactive filters for Date, City, and other variables.

3.Tooltips – Display further information such as the trip distance or average booking value.

Vehicle Type Analysis - Grid View in Power BI

Create a grid table (matrix or table visual) to analyse key performance indicators like Total Bookings, Total Booking Value, Avg Booking Value, Total Trip Distance across different Vehicle Types in Uber trips.

Power BI Implementation:

Use a Table or Matrix Visual to display Vehicle Type with the KPIs.

Apply Conditional Formatting to highlight high and low values.

Enable Sorting & Filtering for user interaction.

Total Bookings by Day:

Detecting trends and fluctuations in daily trip volumes.

Identifying peak and off-peak booking days.

Understanding the impact of external factors (holidays, events, weather) on ride demand.

Supporting strategic planning for resource allocation and pricing adjustments.

Location Analysis:

Understanding trip locations is crucial for optimizing ride distribution, demand forecasting, and operational efficiency. This analysis focuses on:

Most Frequent Pickup Point

Identify the most common starting locations for trips.

Helps in optimizing driver availability and dynamic pricing strategies.

Most Frequent Drop-off Point:

1.Find the most common drop-off locations.

2.Requires activating an inactive relationship in Power BI between Pickup Location and Drop-off Location in the data model.

Farthest Trip:

1.Determine the longest trip based on distance travelled.

2.Useful for analysing outlier trips, long-distance demand, and fare optimization.

Total Bookings by Location (Top 5):

1.Identify the top 5 locations with the highest trip bookings.

2.Helps in demand forecasting and optimizing driver availability in high-traffic areas.

Most Preferred Vehicle for Location Pickup:

1.Determine the most frequently booked vehicle type at each pickup location.

2.Supports strategic vehicle distribution based on customer preferences and location demand.

Other Implementation Enhancements for Uber Trip Analysis Dashboard

1.Bookmark for Data Details 

Add a "Data Details" bookmark to display a pop-up or side panel explaining:

1.1Meaning of key metrics (Total Bookings, Total Trip Distance, etc.).

1.2Description of tables used in the analysis.

1.3Data source and refresh frequency.

2.Clear Slicer Button 

2.1Add a "Clear Filters" button using a blank button with a Reset Slicers action to reset all selections in one click.

2.2Improves user experience for quick dashboard resets.

3.Download Raw Data Button 

3.1Add a button to export raw data in CSV or Excel format.

3.2Use Power Automate or built-in Power BI Export functionality.

3.3Enables users to analyse raw data outside Power BI if needed.

DAHBOARD 2: TIME ANALYSIS

To understand trip patterns based on time, Uber needs to analyse ride demand and trends across different time intervals. This dashboard will help in optimizing operations, pricing, and driver availability.

Global Dynamic Measure (Filters All Charts)

A measure selector will be created for:

✔ Total Bookings

✔ Total Booking Value

✔ Total Trip Distance

This dynamic measure will update all visuals based on user selection.

Visualizations:

1.By Pickup Time (10-Minute Intervals) - Area Chart

1.1 Groups trip bookings into 10-minute intervals throughout the day.

1.2 Helps in identifying peak and off-peak demand periods.

2.By Day Name - Line Chart

2.1 Shows booking trends across Monday to Sunday.

2.2 Useful for analysing weekday vs. weekend demand.

3.By Hour and Time - Heatmap (Matrix Grid)

3.1 Rows: Hours of the Day (0–23)

3.2 Columns: Days of the Week (Mon-Sun)

3.3 Values: Selected Dynamic Measure (e.g., Total Bookings)

3.4 Highlights peak booking hours across different days.

DAHBOARD 3: DETAILS TAB

To provide in-depth insights and allow users to explore granular data, a Grid Tab will be created. This tab will enable drill-through functionality, allowing users to access detailed records based on selections made in other dashboards.

Features of the Grid Tab:

Grid Table with Key Fields:

Displays essential trip details

Drill-Through Functionality:

Users can right-click on a data point from other visuals (e.g., charts, heatmaps) and drill through to this Grid Tab.
Displays detailed records related to the selected data point.

Bookmark for Full Data View:

A "View Full Data" bookmark to toggle between filtered drill-through data and the complete dataset.

Allows users to reset filters and see all records easily.




