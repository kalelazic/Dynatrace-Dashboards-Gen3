# Executive Overview Dashboard
This dashboard provides an executive level overview on KPIs and Customer Experience.

![Executive Overview Dashboard](ExecutiveOverview.png)

# Prerequisites

Required: [Create a conversion goal](https://www.dynatrace.com/support/help/platform-modules/digital-experience/web-applications/analyze-and-use/define-conversion-goals) for a user action that indicates a converted user session (i.e. Order Confirmation Page).


# Target Audience

- Application Owner
- Line of Business
- Executive

# Use Cases

- Are performance issues impacting my customer experience?
- Are errors impacting my customer experience?
- Are performance and error trends impacting my customer experience?
- Are my KPIs rtrending in the right direction?
- What days/times do I have good customer experience?
- Are my users converting efficiently? 
- Does a change in my APDEX score impact my customer experience?
- Are my users staying engaged?
- Do I have user satisfaction problems/trends?
- Is my traffic trrending in the right direction?
- Is my bounce rate normal and trending in the right direction?

# Install Instructions

- Download https://github.com/TechShady/Dynatrace-Dashboards-Gen3/blob/main/Executive%20Overview.json
- Launch the new Gen3 UI
- Select the Dashboard app
- In the upper righthand corner, select Upload and select your json file
- Refresh your dashboard list and launch your Dashboard

# User Guide

The Executive Overview Dashboard is broken down into three sections.

![Executive Overview Dashboard](ExecutiveOverview-1.png)

The top section is called the KPI banned. This section has the following KPIs:
- Avg Duration: Time between the initial user input and complete page load.
- Avg Errors: Average number of Request and JavaScript Errors.
- Efficiency Rate: Rate of sessions that converted with good user experience. A perfect efficiency rate is 100.
- Deficiency Rate: Rate of sessions that abandoned with poor user experience. A perfect deficiency rate is 0.
- Conversion Rate: Rate of sessions that converted.
- Apdex: Application Performance Index is a standard developed by an alliance of companies for measuring the performance of applications. A perfect Apdex score is 1.

Each KPI cell displays the current value for the last 24 hours. Each KPI is compared to a seven-day time shift over the past 24 hours and will display, in parentheses, the KPI difference and trend direction.

![Executive Overview Dashboard](ExecutiveOverview-2.png)

The middle section KPI metrics (with comparison to a seven-day time shift) for: 
- Sessions - Total number of user sessions.
- New Sessions - Total number of new user sessions.
- Satisfied Sessions - Total number of user sessions that had a user experience score of SATISFIED.
- Tolerated Sessions - Total number of user sessions that had a user experience score of TOLERATED.
- Frustrated Sessions - Total number of user sessions that had a user experience score of FRUSTRATED.
- Avg Time On Site - Average session duration.
- Requests - Total number of user actions.
- Bounces - Total number of user sessions that bounced from the web site.
- Conversions - Total number of user sessions that reached the conversion goal.
- Abandons - Total number of user sessions that did not reach the conversion goal.

![Executive Overview Dashboard](ExecutiveOverview-3.png)

The bottom section charts customer satisfaction over the last seven days.