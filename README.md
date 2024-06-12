# Google Fiber Customer Satisfaction Project

## Project Overview
[Google Fiber](https://fiber.google.com/) is a broadband internet company that provides fiber optic internet to both residential and commercial customers. The customer service team would like to use business intelligence tools to monitor and improve customer satisfaction. Leadership would like to better understand the circumstances in which customers contact customer service more than once for the same inquiry, how often, and why. Google Fiber requested a dashboard tool to explore the trends in repeat calls. This will help leadership develop a customer support strategy that fully addresses inquiries in the first call.

## Stage I - Planning
Detailed notes were collected during a project meeting. The objectives of the planning stage are to review the meeting notes to identify the relevant stakeholders and to organize tasks into milestones. The following documents were prepared to document the stakeholder requirements, project requirements, and project strategy.
[Stakeholder Requirements Document] encapsulates stakeholder needs and requests to better understand the project scope prior to planning teh project details and strategy.
[Project Requirements] Document establishes the information needed to achieve the stakeholder requests.
[Strategy Document] outlines the plan to meet the project goals and flesh out deliverables.

> #### Purpose:
> The Google Fiber customer service team has requested a dashboard to provide insights on how often customers phone customer support after an initial inquiry. The team’s ultimate goal is to reduce call volume by increasing customer satisfaction and improving operational optimization. The dashboard should demonstrate an understanding of this goal and provide stakeholders with insights about repeat caller volumes in different markets and the types of problems they represent.

> #### Stakeholders:
- Emma Santiago, Hiring Manager (primary contact)
- Keith Portone, Project Manager (primary contact)
- Minna Rah, Lead BI Analyst
- Ian Ortega, BI Analyst
- Sylvie Essa, BI Analyst

> #### Stakeholder usage details:
To understand how often customers are calling customer support after their first inquiry; this will help leaders understand how effectively the team is able to answer customer questions the first time.

> #### Primary requirements:
An accessible dashboard with large print and text-to-speech alternatives, including the following:
- A chart or table measuring repeat calls by their first contact date
- A chart or table exploring repeat calls by market and problem type
- Charts showcasing repeat calls by week, month, and quarter
- Provide insights into the types of customer issues that seem to generate more repeat calls
- Explore repeat caller trends in the three different market cities
- Design charts so that stakeholders can view trends by week, month, quarter, and year

#### Data
To anonymize and fictionalize the data, the datasets the columns market_1, market_2, and market_3 to indicate three different city service areas the data represents. 

The data also lists five problem types:
- Type_1 is account management
- Type_2 is technician troubleshooting
- Type_3 is scheduling
- Type_4 is construction
- Type_5 is internet and Wi-Fi

Additionally, the dataset also records repeat calls over seven-day periods. The initial contact date is listed as contacts_n. The other call columns are then contacts_n_number of days since first call. For example, contacts_n_6 indicates six days since first contact. 
