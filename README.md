Based on the Google Analytics 4 public dataset ga4_obfuscated_sample_ecommerce, which is located at - https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=ga4_obfuscated_sample_ecommerce&t=events_20210131&page=table

complete the following tasks:

1. Build a closed funnel based on users for 2020 with the ability to filter by product name.
Funnel steps: select_item, view_item, add_to_cart, purchase. Write an SQL query to retrieve data. Visualize the received data in any convenient way.

2. Build a report on a multi-channel sequence (source / channel) for user sessions before purchase (purchase event) for 2020.
The result of the report should be chains of sources/channels and the number of users who made a purchase for each chain. That is, all touches (sessions) and their sources/channels before the purchase. An example of such a sequence in GA reports - https://prnt.sc/MGTHqGz8y2z6
Write an SQL query to retrieve data. Visualize the received data in any convenient way.

3. Cohort analysis. Calculate Weekly Retention (return of users). The condition for inclusion in the cohort is the user's first visit.
Data for analysis - the entire available period. Write an SQL query to retrieve data. Visualize the received data in any convenient way.

* users must be counted by the user_pseudo_id field
