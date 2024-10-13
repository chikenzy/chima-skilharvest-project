 # Chima-Skilharvest-Project

## [Project Name](#project-name)
## [Project Overview](#project-overview)
## [Data source](#data-source)
## [Data cleaning and preparation](#data-cleaning-and-preparation)
## [Data tools used](#data-tools-used)
## [Exploratory Data analysis(EDA)](#Exploratory-data-analysis(EDA))
## [Report Visualization](#report-visualization)

## 	Project Name
Analytical performance of Chikenzie Business Enterprise

## Project Overview
This project focuses on analyzing the sales performance of Chikenzie Business Enterprise, a Nigerian-based venture with a market presence across the five geographical regions of the country. The enterprise operates multiple stores, offering a variety of business lines and product models. The analysis covers the fiscal period from 2001 to 2016, examining different trade dates and day categories to understand units sold and total revenue generated. By evaluating these parameters, the project aims to provide valuable insights into sales trends and performance, enabling informed decision-making and compelling storytelling.

## 	Data source
The primary source of data is MS Excel, and this is open-source data that can be freely downloaded from an open source online such as;

  - Kaggle
  -  FRED
  -   repository site
  -    google 

## 	Data cleaning and preparation
Processes involved pivoting, different Excel functions
In the initial phase of the data cleaning and preparation, the following action is performed;
1.	Data loading and inspection
2.	Handling missing variables
3.	Data cleaning and formatting

4.	## 	Data tools used
5.	MS Excel [download here](https://www.microsoft.com)
  - Microsoft Power Bi
  - Google sheet
  -Google software

These are the major tools used for the analyses, Helps to pivot and analyse data

## Exploratory Data analysis(EDA)
 This involves Exploring data to answer some questions about the data such as,
Market
-	the highest market by revenue and units sold 
-	the lowest market by units sold 
### Region
-	the highest region by revenue
  
   <img width="488" alt="r top 5 reg by rev" src="https://github.com/user-attachments/assets/5c0884a7-5a5a-45a1-9b34-f786327f09b7">

-	The  lowest region by unit sold
  
<img width="479" alt="r lowest region by uni sold" src="https://github.com/user-attachments/assets/21742845-dc52-43b5-82f7-6d9c670d22fc">

### Store
-	store with the highest revenue
  
  <img width="515" alt="st top store by rev" src="https://github.com/user-attachments/assets/2de18cb6-d5c5-422f-851d-1c2f8484a9d8">

-	store with the least units sold
  
<img width="488" alt="st bot store b uni " src="https://github.com/user-attachments/assets/5ddc230c-4caf-49b8-a75b-477ff12a6a29">

### Trade date
-	trade date with the highest revenue
  
<img width="427" alt="tt top trade date b rev" src="https://github.com/user-attachments/assets/48b1301c-2e71-431c-b2ad-9315939c9fb7">
 
-	 as well as the highest unit sold
<img width="506" alt="tt top trade date by uni" src="https://github.com/user-attachments/assets/873f4707-7091-48ef-aaa2-7f4fd4bc4c23">

### Model
-	the model with the top units sold
  
<img width="484" alt="m top model by uni" src="https://github.com/user-attachments/assets/825e765f-1a13-4fb9-885f-6def49f0434b">

-	model with that of the bottom 5 unit sold

<img width="454" alt="m bot model by uni" src="https://github.com/user-attachments/assets/2594ff47-952e-405d-9f33-ade45afaa908">

### Line of Business
-	what line of business generated the highest revenue

<img width="496" alt="l top  line of biz" src="https://github.com/user-attachments/assets/d24371e8-b6a4-4b46-975c-2a21e0f653d6">

-	line of business with the least unit

<img width="499" alt="l bot line of biz by uni sold" src="https://github.com/user-attachments/assets/13cd21d8-38bc-4538-9e59-975cd1f486bd">

###  Day Category
-	 highest day category by revenue and units sold

<img width="404" alt="dc top day category by rev" src="https://github.com/user-attachments/assets/c78b3719-a7f5-4ef4-b778-eca8ba419f6a">

 
-	Lowest day category by unit sold 

<img width="470" alt="dc bot day cat by uni" src="https://github.com/user-attachments/assets/5b2284c6-90f9-4113-9d06-6b76301832eb">

The above questions will be answered using the pivot analysis, and the process involves;
  I.	Access the data
  II.	Have a critical study of the data
  III.	With the use of the ‘IF’ function, access the category of the units sold to have a holistic view of their performance rate in terms of sales
#### Pivot Table field
To access the pivot data table field;
-	Highlight the data by pressing shft + ctr + rgt + dwn key
-	Go to insert
#### Pivot table
-	Select a table or range on the field 
-	Select a new worksheet
-	Select OK
-	You will be brought to a new worksheet with a PIVOT TABLE FIELD
#### The Pivot Field
The essence of the pivot field is for ease of summarization of data based on the data you are working with.

It has 4 major components;
-	Row: data to appear horizontally
-	Column: data to appear in the column field
-	Value: for data that appears as aggregate functions
-	Filter: to filter data on a row or column
#### Summarization
-	Go to the pivot table field
-	Click on the field for rows and /or columns for the non-aggregates functions
-	Click on the value field to get the aggregates function
  ####  filter for the top or least
-	Right click
-	Click top 10
-	Reduce it to the value you want to summarize it to
-	Click bottom or top( as the case may be)
-	OK
#### sort for the highest or lowest
-	Right click
-	Click sort
-	Sort smallest to largest or vice versa
-	OK
#### visualize
-	Click fn+alt+f1 function
-	Copy and paste it on your new worksheet

## Report/Visualization
Summarization from the pivot table field will give us a good graphic /pictorial /chart of the analysis for ease of understanding and comprehension.
Visualization is done in Excel from the pivot table field thus;

