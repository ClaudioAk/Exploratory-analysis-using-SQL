# Exploratory-analysis-using-SQL
 Insurance Upgrades Exploratory Analysis

Travel Assured provides travel services to its customers. They are based in the United States.

Travel Assured provides everything from flights and hotel bookings to holiday insurance.

The sales team wants to sell upgrades to customers. So they can do this, it is vital that the data is clean, accurate and available for reporting.

They need your help to prepare some data before they start to run a new promotion.

**Database Schema**

<img width="719" height="343" alt="schema" src="https://github.com/user-attachments/assets/3361f479-98e7-499a-9463-35eedf7c63e2" />

# Task 1 

The sales team want to use customer information to target their new promotion. But they think the data may not be clean enough to use. 

The table below shows what the sales team expect the data types and format to be.

Write a query that makes the `customers` table match the description provided, including identifying and cleaning all invalid values. 

-  Your output should be a DataFrame with the name 'clean_data'. Do not modify the `customers` table.
-  Note that the DataLab environment formats dates as YYYY-MM-DD-hh-ss-SSS. 

| Column Name       | Description                                                      |
|-------------------|------------------------------------------------------------------|
| customer_id         | Unique integer (set by the database, can’t take any other value) |
| location       | State names as a lower case string                              |
| age        | Integer value giving age of customer                              |
| registration_date          | Date of first registration with company                    |


# Task 2

The sales team wants to run a promotion on upgrades to international travel insurance policies. 

They only want to send this promotion to customers who have an active, US policy type.

Write a query to provide the `customer_id` and `start_date` for eligible customers.



# Task 3

After the promotion has been sent, the sales team will need to monitor the number of active policy holders by policy type who purchased an upgrade.

Write a query that returns the data for the sales team to monitor. Your output should include `policy_type` and `number_active` columns.

