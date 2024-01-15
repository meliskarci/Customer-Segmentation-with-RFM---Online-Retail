# CRM
CRM, short for "Customer Relationship Management," is the concept of effectively managing the communication between businesses and their customers. The goal is to strengthen customer satisfaction by adopting a customer-centric approach, acquiring new customers, and retaining existing ones while also increasing the profitability of the business. In the world of CRM, various CRM applications are used to achieve this goal. These include customer lifecycle optimizations, communication through various campaigns and digital marketing, efforts to acquire customers through promotions, customer retention strategies, cross-selling, up-selling efforts, customer segmentation activities, and more. The overall aim is to make the entire customer relationship process more efficient based on data-driven strategies. These are strategic efforts implemented to acquire more customers and profits with less time and effort.

## So What is the RFM ?
The commonly used RFM analysis in CRM analytics gets its name from the initials of the recency, frequency, and monetary metrics. It allows for segmenting customers based on their purchase habits and enables strategic actions to be taken for each segment as needed. It is a rule-based technique used for customer segmentation.

## RFM Metrics
Recency: The customer's recency, either being new or the most recent purchase time. If one customer's recency score is 1 and another's is 10, the one with a score of 1 is better for us.

Frequency:The total number of purchases a customer has made

Monetary: Monetary value of the total spending made by the customer.

What will we do?
After performing the necessary basic tasks to understand and prepare the data, we will conduct the RFM analysis in three steps.

Calculation of RFM Metrics: We will calculate the Recency, Frequency, and Monetary values for each customer.

Calculation of RFM Scores: We will convert the obtained Recency, Frequency, and Monetary values into scores ranging from 1 to 5. Our goal is to convert them all to the same gender and make them comparable. A distribution from 5 to 1 needs to be calculated, assigning 5 to large values and 1 to small values. In this step, it is important to note that a customer who has shopped just yesterday or a few days ago is more valuable to us. Therefore, unlike Frequency and Monetary values, those with smaller Recency values will be assigned 5, and those with larger values will receive 1. Afterward, we concatenate the scores we have created as string values.

Creation and Analysis of RFM Segments: We group customers into simple segments based on the scores we have created.

## Customer Segmentation with RFM
## Business Problem
*An e-commerce company wants to segment its customers and determine marketing strategies based on these segments.

The data set named 'Online Retail II' contains the sales of an online retail store based in the United Kingdom between 01/12/2009 and 09/12/2011.

## Variables
- InvoiceNo: A unique number for each transaction or invoice. If it starts with 'C,' it indicates a canceled transaction.
- StockCode: Product code. A unique number for each product.
- Description: Product name
- Quantity: Quantity of products. Indicates how many of each product were sold on the invoices.
- InvoiceDate
- UnitPrice: Product price (in Sterling)
- CustomerID
- Country: Country of the customer
