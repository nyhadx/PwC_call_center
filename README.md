# PwC Call Center Trends

Create a dashboard in Power BI for a call center manager working for a big telecom company. The client wants a dashboard that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset. 



![Dashboard Screenshot](https://github.com/nyhadx/PwC_call_center/blob/main/Summary_Dashboard.png)
![Dashboard Screenshot](https://github.com/nyhadx/PwC_call_center/blob/main/Agent_Dashboard.png)

## Introduction

This series of projects are part of the PwC Digital Accelerator Program, an initiative aimed at upskilling employees to technologies such as automation, digital literacy, machine learning and design thinking.

The client was looking for transparency and insights into the data they had. Wanted an accurate representation of long-term call center customer and agent behavior.



## Data Preparation

The dataset contains the following info:
1.	Call ID: Unique identifier for each call.
2.	Agent: Name of the call center agent who handled the call.
3.	Date: Date of the call.
4.	Time: Time when the call took place.
5.	Topic: The subject matter of the call (e.g., Contract related, Technical Support, Payment related).
6.	Answered (Y/N): Indicates whether the call was answered.
7.	Resolved: Indicates whether the issue was resolved.
8.	Speed of answer in seconds: Time taken for the agent to answer the call.
9.	AvgTalkDuration: Average duration of the call (in seconds).
10. Satisfaction rating: Customer satisfaction rating for the call (on a scale of 1-5, with 5 being the highest).

*Cleaned to fix the AvgTalkDuration data type from time format to decimal.
*Fixed Date format from datetime to date format.
*Duration (seconds) were converted to minutes for easy comparisons.
