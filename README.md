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
*Fixed Date format from DateTime to date format.
*Duration (seconds) were converted to minutes for easy comparisons.

## Analysis
### 1. Key Metrics:
   
•	Total Calls: 5000
•	Abandoned Calls: 946 or 18.9% of calls were abandoned. Customers might be leaving due to longer wait times
•	Average Answer Speed: 1.1 minutes
•	Average Handling Time: 3.7 minutes
•	Customer Satisfaction Score: 3.4 indicates generally positive but not outstanding

### 2. Visuals and Insights

•	Number of Calls by Satisfaction Rating: Most calls received a rating of 3 or 4. Focusing on low rates uncovers reasons behind it whether it be unresolved issues or long wait times
•	Number of Calls by Topic: Most common calls were streaming and payment related. This could indicate a recurring problem or a need for better service
•	Resolution Rate: With a 73% resolution rate, there might be room for improvements. High unresolved calls of 27%. Agents might need more training or resources for handling issues. 
•	Call Volume: The call center operates from 9AM to 6PM, with peak volume around 11AM – 1PM. 
•	Agent Performance: The workload distribution was relatively balanced as well, and individual performances

### 3. Recommendations

1.	Address the high abandonment rate by adding more agents during peak hours or introducing callbacks for abandoned calls
2.	Improve resolution rate by investigating low-rated calls, and resources for addressing complex issues
3.	Enhance customer satisfaction by replicating 5-star rating practices





