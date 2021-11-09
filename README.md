# New-York-Violation-Tickets
 Analysis and visualization of parking tickets in NYC during 2015 and 2017. <br /> <br />

This project was done as a final project of Business Analyst Course. <br />
The data was taken from NYCOpenData and stored in the SQL database, for the students' use. <br /> <br />

The analysis was done using mostly Power BI and was divided into 5 different reports.<br /><br />

The first step was the preparation of the data (ETL) using Power Query: <br />
Preparation of dimension tables by merging existing tables by different categories - location, issuers, vehicle. <br />
Preparation of Facts table - merging the violation description and fine amount details to the exsiting parking violation table, <br />
fixing data types and cleaning missing or duplicate values. <br />
Creation of date dimension table using 'M' language. <br />
Filteration of the data years - using 2015 to 2017. <br /><br />


Data modeling: <br />
Creation of relationships between the dimension tables and the facts table. <br /><br />


Creating measures and calculated columns: <br />
Calculation of tickets count, average fine, revenue, profit, YTD, MTD ect. <br /><br />


The project includes 5 reports, each one exmanining different analysis subject. <br /><br />

The first report examines the different kind of parking violations and the different time occurance. <br />
The report shows the most popular violations for each borough in NY, the distribution of parking <br />
violations according to weekdays and different time bins of the day. <br /><br />

The second report examines the different body types (ex: private, truck etc.). <br />
It shows the tickets count and average fine amount for each body type, the most common violations <br />
and a heat map showing the geographic location of the violations. <br /><br />

The third report examines violations done by trucks in Manahattan. <br />
It shows the streets and avenues in which the highest number of violations occured, as well as the 3 most common violations. <br /><br />

The fourth report exmaines the different issuing agencies. <br />
It shows the tickets count, revenue, profit and average annual salary for each issuing agency, <br />
distribution of normalized tickets count by months and years. <br /><br />

The fifth report examines more general insights such as average missing parking and standing spots in NY and a heat map showing their locations. <br />

The main conclusions derived from this project are: <br />
There is a severe shortage in parking spots during weekdays and working hours. <br />
Most of the parking violations are attributed to local NY citizens using private cars for parking in "no parking" areas. <br />
A proper reccomandation to solve this would be adding parking spots and parking lots  <br />
as well as developing an accesible application for parking payments.
