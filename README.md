# Case study: How does a bike-share navigate speedy success?

This file is an R Markdown document titled "Case Study: How does a bike-share navigate speedy success?". It serves as a comprehensive analysis of Cyclistic's bike-sharing service, focusing on the behavioral distinctions between casual riders and annual members. Key sections and content include:

# Scenario and Problem Statement:

  - Cyclistic aims to increase profitability by converting casual riders into annual members, as annual members generate higher recurring revenue.
  - The marketing team seeks data-driven insights for targeted strategies.

# Business Task:

  - Analyze historical trip data to compare usage patterns, identify behavioral differences, and recommend strategies to convert casual riders.

# Data Preparation:

  - Combines and cleans historical data (2019 and 2020) sourced from Motivate International Inc.
  - Ensures data integrity by removing errors like duplicate entries, negative ride durations, and test rides.

# Data Processing:

  - Renames columns for consistency.
  - Adds calculated fields (e.g., ride length, day, month, year).
  - Filters out invalid data for quality analysis.

# Descriptive Analysis:

  - Compares ride durations and patterns between casual riders and members.
  - Investigates trends by weekday and visualizes data using plots (e.g., ride counts and durations by user type and day).

# Conclusions:

Casual riders take significantly longer trips, averaging 3,860 seconds per ride, compared to members, who average just 219 seconds. Interestingly, while casual riders show higher activity on Thursdays and Fridays, members are more active on weekends (Saturday and Sunday). However, the total number of rides is higher for members on weekdays, likely due to commuting patterns, whereas casual riders exhibit a noticeable summer peak, suggesting seasonal leisure use. A t-test (p < 2.2e-16) confirms that the difference in ride durations between the two groups is highly significant, reinforcing that casual riders consistently take longer trips on average. These insights highlight distinct usage behaviors—casual riders leaning toward leisure and members toward routine travel.

# Recommendations:

  - Target casual riders who frequently use bikes on Thursdays and Fridays with weekday-specific discounts for membership sign-ups. Example: Ride 3+ weekdays? Save 30% with an annual membership!
  - Capitalize on the summer peak by offering limited-time summer membership deals (e.g., 3-month trial at a reduced rate).
  - Identify casual riders with longer trip durations and offer them bonus ride credits upon membership conversion.
  - Deploy on-the-spot membership sign-up kiosks at high-traﬀic casual rider stations, especially near leisure hotspots.
