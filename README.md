# Module 14 Challenge - NYC CitiBike Analysis with Tableau

## Overview of the Project

### Purpose

The purpose of this project is to build a visualization storyboard to present to a group of investers in order to open a bike-sharing program in Des Moines, IA. Our client provided ridership data from CitiBike for New York City, NY in August 2019. Our program uses this data as an analogue to forcast ridership in Des Moines, IA.

### Tableau Public Link
We have provided the link to the Tableau Public Story bellow.
[link to dashboard](https://public.tableau.com/app/profile/carlos.uroza/viz/NYCCitiBikeAnalysiswithTableau/NYCCitiBikeAnalysis)

## Results

### Deliverable 1 - Change Trip Duration to a Datetime Format
The image below shows the output of our Jupyter Notebook. This notebook is used to convert the "tripduration" column in the original csv file into a datetime format in a new column named "tripduration_dt".
![Del1](https://user-images.githubusercontent.com/103288980/182085154-01d76536-2968-4aba-ae3a-d9a596f63133.PNG)


### Deliverable 2 - Create Visualizations for the Trip Analysis
We have included a variety of visualizations with functional filters in our Trip Analysis in order to address our stakeholders' potential concerns:

1. Checkout Times for Users
![Del2-1](https://user-images.githubusercontent.com/103288980/182091252-993ebfbf-6c6a-44cc-8a64-2e843f08afdc.PNG)
* This graph shows the relation between trip duration and number of trips. We can observe that most trips last about 5mins.

2. Checkout Times by Gender
![Del2-2](https://user-images.githubusercontent.com/103288980/182091267-1207eba7-0582-4e1f-9108-c336a53addab.PNG)
* This graph shows the relation between trip duration and number of trips by Gender. We can observe the same trip duration distribution for Men and Women.

3. Trips by Weekday per Hour
![Del2-3](https://user-images.githubusercontent.com/103288980/182091324-8dbba69a-4a03-4085-bfe9-5b60a67fda62.PNG)
* This graph shows that most rides happen around the normal commuting times.

4. Trips by Gender (Weekday per Hour)
![Del2-4](https://user-images.githubusercontent.com/103288980/182091354-1e8f068c-8b82-4cbc-aea0-df5d6ef0be56.PNG)
* This graph shows that most rides also happen around the normal commuting times for both Men and Women.

5. User Trips by Gender by Weekday
![Del2-5](https://user-images.githubusercontent.com/103288980/182091364-6d089b70-3f4c-4fdb-b456-2ff39bcf07d9.PNG)
* This graph shows the relationship between user type and number of trips by gender and day of the week. We can observe that most subscribers use the citibikes on weekdays.

6. Top Starting Locations
![Del2-6](https://user-images.githubusercontent.com/103288980/182091408-e861373d-cd6b-4c46-85dc-caa19615eda1.PNG)
* This map shows the layout of trip starts over a geographic area. We can observe most trips start in Manhattan.

7. Top Ending Locations
![Del2-7](https://user-images.githubusercontent.com/103288980/182091426-79862893-9d10-4481-8357-b4820cc59ebb.PNG)
* This map shows the layout of trip ends over a geographic area. We can observe most trips also end in Manhattan. It is possible most of these trips are for a short distance.


### Deliverable 3 - Create a Story and Report for the Final Presentation
The following images are the individual pages of our full Tableau Story board presentation. Please use the link above to see the story hosted on Tableau Public.

![Page1](https://user-images.githubusercontent.com/103288980/182089042-a293ab41-dd87-4bc9-b484-5bd6c82e5475.PNG)

![Page2](https://user-images.githubusercontent.com/103288980/182089067-8d310e19-7a2f-4e31-aaa2-b76aec4a90cc.PNG)

![Page3](https://user-images.githubusercontent.com/103288980/182089121-8e57175b-96e8-487d-a2ce-26280897435e.PNG)

![Page4](https://user-images.githubusercontent.com/103288980/182089151-4cdbd3e2-92ea-42d4-aa78-df6def5c9fff.PNG)

![Page5](https://user-images.githubusercontent.com/103288980/182089184-47f2f45b-f4cd-4245-9ee1-d66d827710bf.PNG)

## Summary
In summary, our Analysis indicates that NYC is a strong candidate for bikesharing services around commuting times. As such, we can reasonably expect that ridership does not entirely depend upon NYC's tourism activities. It is our recommendation that a bikesharing service aimed at commuters could also be sustainable in Des Moines, IA.

### Recomendations
Our presentation could be improved by adding the following additional visualizations from the given dataset.
1. Customer Type (By Age Groups)
![Del3-1](https://user-images.githubusercontent.com/103288980/182089237-7c42a29a-8b59-49ec-9a15-92784426db3a.PNG)
* This graph shows the proportion of user types according to age groups. This could be useful in determining a marketing strategy.

2. Total Trip Duration (By Age Group)
![Del3-2](https://user-images.githubusercontent.com/103288980/182089265-c88bd2d2-c27a-4d81-994a-c0e508415d3b.PNG)
* This graph breakes down total ridership duration by each age group. If our revenue depends on ridership duration, this graph would be useful in determining the market segments contributing most to our bottom line. Please note, this graph is set on a logarithmic scale.
