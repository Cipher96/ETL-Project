# ETL-Project
Perform ETL using Spar Nord Bank published dataset.
<br>
Before getting into designing the ETL pipeline, lets us understand the problem statement.
<br>
**Problem statement:**
- Banks have to refill the ATMs when the money goes below a specific threshold limit. Cash refilling into ATMs depends on the activity, area where an ATM is located, weather, day of the week etc.
- Spar Nord bank is trying to observe the withdrawal behaviour and the corresponding dependant factors to optimally manage the refill frequency of a particular ATM as well as the overall effort required.
- We have data from more than 100 ATMs across Denmark. Data is captured for every transaction including withdrawn amount, card type, location, date, time, ATM type etc.
- Spar Nord Bank has built a Dimensional Model datastore (ATM Data Mart) og this ATM transaction data to understand the ATM usage pattern.
<br>
Dataset source - https://www.kaggle.com/datasets/sparnord/danish-atm-transactions
<br>
**ETL Architecture:**
![Screenshot 2024-09-13 005645](https://github.com/user-attachments/assets/6d36e719-41bd-4adf-9dcd-d9cf3593b6e8)

Thanks!
