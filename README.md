# ABC-Call-Volume-Trend-Analysis
The "Call Volume Trend Analysis" is a data analytics project that aims to provide valuable insights into the inbound call trends of ABC, a company operating in the insurance sector. As a data analyst, my task is to analyze the provided dataset containing information about incoming calls and derive meaningful conclusions to optimize the experience.
# Project Description
As a data analyst, my task is to analyze the provided dataset containing information about incoming calls and derive meaningful conclusions to optimize the customer experience and improve workforce planning. Business Understanding: ABC operates in a highly competitive market, where advertising plays a crucial role in attracting and retaining customers. The first impression of the business is formed through advertising efforts, and the company's analytical skills are essential in identifying cost-effective media platforms to convert audiences into customers. The CX team's role is vital as they handle inbound customer support calls. The team's goal is to attract, engage, and delight customers, ultimately turning them into loyal advocates for the business. The project's focus is to understand call volume trends and
optimize workforce allocation to enhance customer satisfaction and reduce call abandonment rates.
## About the Dataset:
The dataset for the "Call Volume Trend Analysis" project contains 115,406 rows and
consists of the following columns:
1. Agent_Name: The name of the call center agent who handled the call.
2. Agent_ID: Unique identifier for each call center agent.
3. Customer_Phone_No: Phone number of the customer who made the inbound call.
4. Queue_Time(Secs): The time, in seconds, the customer had to wait in the queue
before connecting with an agent.
5. Date_&_Time: The date and time of the incoming call.
6. Time: The time of the day when the call was received.
7. Time_Bucket: Categorization of time into specific buckets (e.g., 1-2, 2-3) for
analysis.

8. Duration(hh:mm:ss): The total duration of the call in hours, minutes, and seconds
format.
9. Call_Seconds(s): The duration of the call in seconds.
10. Call_Status: Indicates whether the call was abandoned, answered, or transferred.
11. Wrapped_By: Information about the agent who handled the call after it was
transferred.
12. Ringing: Time spent ringing before the call was answered by an agent.
13. IVR_Duration: Duration of the Interactive Voice Response (IVR) interaction, if
applicable.
This dataset provides comprehensive information about inbound calls received by the
CX team. The various columns will be utilized to analyze call volume trends, average call
duration, and manpower planning for improved customer experience and call center
efficiency.
The dataset for the "Call Volume Trend Analysis" project contains 115,406 rows of data,
covering a span of 23 days. It provides detailed information about inbound calls
received by the CX team during this period. The dataset includes time buckets, which
categorize the data into specific time intervals (e.g., 9-10, 10-11) for easier analysis and
visualization.
The dataset's columns offer valuable insights into various aspects of the inbound calls,
such as agent information, customer phone numbers, queue times, call date and time,
call duration, call status, and more. These data points will be leveraged to conduct a
comprehensive analysis to understand call volume trends, average call duration, and
plan manpower allocation effectively to enhance customer experience and reduce call
abandonment rates.

## Approach
1. Data Understanding: First, we will examine the dataset containing information
about inbound calls received by the CX team over 23 days. We'll review the
columns, such as agent names, call duration, call status, and more, to understand
the data.
2. Average Call Duration: We'll calculate the average duration of all incoming calls
for each time bucket. This will help us identify if specific time periods have
longer or shorter call durations.
3. Call Volume Analysis: To understand call patterns, we'll create a chart or graph
showing the total number of calls received in each time bucket. This visualization
will help identify peak call hours.
4. Manpower Planning: We aim to reduce the call abandonment rate from 30% to
10%. By calculating the minimum number of agents required in each time
bucket, we'll ensure that at least 90 out of 100 calls are answered promptly.
5. Night Shift Manpower Planning: We'll address the issue of no agents available at
night by proposing a manpower plan for each time bucket. The goal is to keep the
maximum abandon rate at 10% and provide a better customer experience.
6. Insights and Recommendations: Based on the analysis, we'll derive valuable
insights into call trends, customer behaviour, and agent efficiency. These insights
will help make data-driven decisions to optimize workforce allocation and
enhance customer satisfaction.
Tech-Stack Used – MS Excel 2021
The project "Call Volume Trend Analysis" utilizes Microsoft Excel 2021 as the primary
tech stack. MS Excel is employed for data import, cleaning, and preparation. It uses
formulas, PivotTables, and charts for analysis and visualization. MS Excel's user-friendly
interface makes it ideal for efficient data analytics in this project.
● Pivot Tables and Pivot Charts
● Data Visualization
● Arithmetic Operations
