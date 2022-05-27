# SALES REPORT(REPORT 1)

### Data Source: Nubiaville Recruitment team(sales test data)
## ETL And Data Cleaning
Data claning and ETL is the process of obtaining the data using a data connector, transforming the data into useful format using power query editor and loading it into report view for visualization and analysis. 
The folowing steps where taken to clean this dataset:

1)Excel data connector was used to fetch the data from my local storage

2) Load the data into powerquery editor for cleaning

3)Convert ID and sku-code into strings to make data type to be uniform

4)Remove the last row on the poduct table because the row was filled with  null  values

5)Replace blank cells and null values on the kpi_level column with 'NO', this is because null and emptiness signify negative or No.

6)Replace null with zeros on numeric columns

## Data Modelling
The excel wookbook has 4 different tables. These tables are related with each other because of the presence of primary and foriegn keys. The primary keys and foreign keys where used to form relationship between the various tables. Below is the diagram of the model schema.

![Data model](https://user-images.githubusercontent.com/72034856/170734560-5e9260a7-88ee-4302-b760-370b3751f0ae.PNG)


## Dax and Measures Created For Insight

1) Base Measures

i) Revenue

ii) Revenue contribution

iii) Sales Volume

iv) Target Difference

2) Specific scenario

 i)Top 10 sellers
 
3)Time intelligence Measures

i)Days since last purchase

ii)Last Purchase

iii) Sales Difference

iv) Sales Last Year

4) Year Wise Measures

i) 2016 sales

ii) 2017 sales

iii) 2018 sales

iv) 2019 sales

v) 2020 sales

vi)2021 sales

## Data Visualization
This the fun stage where the data is converted into beautiful visualization. The following  visualization was carried out:

1) Total Revenue using card visuals
2) Total volume
3) Target sales compared to actual sales
4) Case price of product categories
5) Revenue contribution by market
6) Revenue by customer type
7) Revenue by sellers
8) Revenue by year

![Assessment Report1](https://user-images.githubusercontent.com/72034856/170714334-c88b060e-5ff6-48b6-86fc-a6b6287bb637.png)

# [Link to PowerBI file](https://github.com/Raph-09/Assessment/blob/main/Assessment%20Report1.pbix)

## How to download
1) Cick on the link above and you will be directed to my github

2) Click on download

3) Ensure you have powerBI installed


# PROCUREMENT REPORT(REPORT 2)
### Dataset: procurement dataset

## ETL and Data Cleaning
1) Excel data connector was used to fetch the data from my local storage

2) Load the data into powerquery editor for cleaning
 
4) Replace null values present in status column with "cancelled" because null is likely to mean procurement was cancelled
 
6) Replace null in the sourcing manager column with "No Sourcing Manager"
 
8) Replace null in the cost centre column with "No cost centre"
 
10) Replace Iseyin, Ibadan and Zaria with Nigeria

12) Replace CDI with Ivory Coast


## Data Visualization

1) Average Budget

2) Average Days Of Approval

4) Number of procurement by category

6) Maximum Budget

8) Total Number of procurement

10) Budget by department

12) Procurement by status

14) Procurement by country

16) Finally slicer was created to control the view of the visuals above depending on if the procurement was approved, denied, cancelled etc

![Assesment Report 2](https://user-images.githubusercontent.com/72034856/170714427-4fda7c28-f7c8-43e3-bc99-6fdd68171a56.png)

### [Link to PowerBI file](https://github.com/Raph-09/Assessment/blob/main/Assesment%20Report%202.pbix) 

## How to download
1) Cick on the link above and you will be directed to my github

2) Click on download

3) Ensure you have powerBI installed

# WORK ORDER(REPORT 3)

## ETL and Data Cleaning

1) Excel data connector was used to fetch the data from my local storage

2) Load the data into powerquery editor for cleaning
 
4) Replace null values with 'No' on the following columns: wtyparts, wtylbr and rush

5) Convert total cost column to numeric

6) Promote the first row to column header

## Data Analysis And Visualization

1) Total Cost

2) Total Fee

3) Average Wait

4) Average Labour Hour

5) Service total cost, fee and wait

6) Labour cost by district

7) Total fee and wait by district

8) Average wait by tech lead

9) Urgent Labour

10) How cost varies with days of the week

11) Labour hours by tech lead


![Assesment Report3](https://user-images.githubusercontent.com/72034856/170714519-caec2b94-b2a7-41fc-8b08-124339f43f9d.png)

### [Link to PowerBI](https://github.com/Raph-09/Assessment/blob/main/Assesment%20Report3.pbix)

## How to download
1) Cick on the link above and you will be directed to my github

2) Click on download

3) Ensure you have powerBI installed
