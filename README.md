FreshFables operates a reliable online grocery delivery service in various areas of Jaipur, catering to a diverse range of customer needs with a wide selection of high-quality products. The company leverages data-driven insights to streamline its operations, ensure timely deliveries, and maintain exceptional customer satisfaction. You have been provided with last month's order details in the link below:

FreshFables

Management has asked you to provide an overview of the orders which they received last month. You have been provided with the following information about the company’s processes which you need to read to understand the overall delivery process of the company.

Order Data Overview

The provided dataset includes last month's order details, with delivered and out-of-stock items listed separately. If an item is out of stock when an order is placed, the company can automatically generate details of such items for each delivered order.

Order Workflow

Order Placement: Once an order is placed, processing begins immediately, and the customer receives an estimated delivery time within the app


Order Processing Time: The processing time is fixed at 2 minutes for every order.

Order Packing Time: The packing time is based on the number of items ordered: if only one item is ordered, the processing time is 1 minute; for 2 to 4 items, it takes 2 minutes; and for 5 to 6 items, the processing time is 3 minutes, regardless of the quantity of each item.

Assignment of Delivery Agents: As per standard procedures, Delivery agents should be assigned within 2 minutes of the order being marked as packed, ensuring a smooth transition to the delivery phase. 

Delivery Time: The company aims to deliver the order within 10 minutes.

Time Segmentation

FreshFables categorizes the day into distinct time periods for operational tracking:


Morning: Orders placed at or after 6:00 AM but before 12:00 PM (12:00 PM exclusive)

Noon: Orders placed between 12:00 PM and 3:00 PM (3:00 PM inclusive)

Evening: Orders placed between 3:00 PM and 7:00 PM ((7:00 PM inclusive)


Night: Orders placed after 7:00 PM but before 12:00 AM (midnight).

Note: The company does not accept orders after midnight and begins taking orders again at 6 AM.


Additionally, it categorizes each week into weekdays and weekends, with Friday, Saturday, and Sunday considered as weekends, and the remaining days as weekdays.

Peak Time Identification

FreshFables designates specific time slots as peak hours to accommodate higher demand:

Morning Peak Time: 8:00 AM to 10:00 AM.

Evening Peak Time: 6:00 PM to 10:00 PM.

Delivery Time Metrics

The company closely monitors delivery performance, defining delays based on the following criteria:

Non-Peak Hours: An order is considered delayed if the actual delivery time exceeds the expected delivery time by more than 5 minutes.

Peak Hours: An order is considered delayed if the actual delivery time exceeds the expected delivery time by more than 15 minutes.

Note: The expected delivery time comprises processing time, packing time, assignment time, and delivery time.

You are required to:

Click on the above link to open the spreadsheet.

Make a copy of this sheet and rename it as “<Your Name_FreshFables>”.

Complete the below task to complete this analysis.

Task 1

Perform an “Exploratory Data Analysis for the data given by the company.

Your answer should match with the screenshot given below:

Task1

Delayed Delivery Analysis
![image](https://github.com/user-attachments/assets/adeefa90-5847-4c27-8d3d-a999688d0c17)


Management seeks to evaluate the overall efficiency of the delivery process and has tasked you with creating a comprehensive dashboard to present this information effectively.

Your dashboard should be in similar to screenshot given below:

Task 2

Analysis of Operation Process

The company aims to evaluate the efficiency of its dark store and delivery operations by analyzing delays during both peak and non-peak periods. To achieve this, the management will conduct a variance sensitivity analysis for each stage of the operations workflow—processing, packaging, assignment and delivery. This analysis will help identify the root causes of delays.

1. Stage Categorization

Outlier: If the variance percentage is less than -60%, the stage is labeled as an 'Outlier.'

Immediate Attention: If the variance percentage is more than or equal to 150%, the stage is labeled as requiring 'Immediate Attention.'

Other stages are categorized based on the degree of delay (e.g. Ontime, Delayed or Slightly Delayed etc.).

Interpretation of Variance Sensitivity Table

-100% to less than -10%: Way Before Time

-10% to less than  0%: Before Time

0% to less than  5%: On Time

5% to less than  40%: Slight Delay

40% and above: Delayed

2. Prioritization for Overall Remarks for each Order

First Priority:

If any stage requires 'Immediate Attention,' all such stages must be listed in the overall remark as Risk for each order.

Second Priority:

Stages with delays are considered next.

Third Priority:

Stages with slight delays are given the lowest priority.

3. Major Issue Identification

All stages requiring 'Immediate Attention' must be listed as major issues for each order. For Delayed or Slightly Delayed processes, the stage with the maximum variance is highlighted as the major issue.

Task 3

Management aims to evaluate each stage of the operations workflow to enhance processes and improve customer satisfaction. To support this goal, you are tasked with creating a dashboard similar to the screenshot as given below.

![image](https://github.com/user-attachments/assets/0542da6f-ed9c-453e-8c05-b0f99ef1b097)


Order Analysis

Management aims to evaluate order performance and has assigned you the responsibility of creating a comprehensive dashboard to effectively showcase key insights and trends.

You are required to

You are required to open the spreadsheet created by you in a previous exercise named  “<Your Name_FreshFables>”.

Complete the below task to complete this exercise.

Task

Create a dashboard similar to the one shown in the screenshot below using the Master data of FreshFable exercise.
![image](https://github.com/user-attachments/assets/f9b6537b-607b-4189-b53b-504eaafe90d2)

