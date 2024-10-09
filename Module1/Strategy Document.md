### **Strategy Document**

**Project Name:** Cyclistic BI Project

**BI Analyst:** Kadri Hearns

**Client/Sponsor:** Sara Romero, VP of Marketing

**Sign-off Matrix:**

| Name | Team/Role | Date |
| ----- | ----- | ----- |
| Sara Romero | VP, Marketing |  |
| Adhira Patel | API Strategist |  |
| Megan Pirato | Data Warehousing |  |
| Rick Andersson | Data Governance Manager |  |

**Primary Dataset:** [NYC Citi Bike Trips](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike?pli=1)

**Secondary Dataset:** [Census Bureau US Boundaries](https://console.cloud.google.com/marketplace/product/united-states-census-bureau/us-geographic-boundaries)

**User Profiles:**

* Intended Audience: Marketing, Product Development, Customer Data, and Procurement teams.  
* Dashboard Usage: Stakeholders will use the dashboard to understand customer demand trends, identify areas for station expansion, and analyze usage by customer type.

**Dashboard Functionality:**

* **Feature:** Data filters for date and weather impact analysis  
* **Reference Dashboard:** None specified, but functionality should mirror dashboards used in transportation analytics for congestion insights.  
* **Access:** Access should be limited to stakeholders and key team members (see the Sign-off Matrix).

**Scope:**

* Include data on bike trip times, locations, customer types, weather conditions, and station congestion.  
* Exclude personally identifiable information to maintain data privacy.

**Date Filters and Granularity:**

* Default time-frame: Last 12 months of data.  
* Granularity options: Day, week, month, and year views.

**Metrics and Charts:**

**Chart 1:**

* **Title:** Station Demand Map  
* **Type:** Heatmap  
* **Dimensions:** Starting and ending station locations  
* **Metrics:** Number of trips per station

**Chart 2:**

* **Title:** Peak Usage by Customer Type  
* **Type:** Bar chart  
* **Dimensions:** Customer type (subscriber, one-time user)  
* **Metrics:** Total trips per customer type

**Chart 3:**

* **Title:** Year-over-Year Growth  
* **Type:** Line chart  
* **Dimensions:** Year  
* **Metrics:** Percentage growth in trips

**Dashboard Mockup:**

* To be included after initial stakeholder review of key metrics and charts.

