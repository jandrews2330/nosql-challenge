# nosql-challenge
Using the provided Jupyter files, I followed the pre-populated instructions using prior class material and with the assistance of Xpert Learning Assistance.

Part 1: Database and Jupyter Notebook Set Up
Using the NoSQL_setup_starter.ipynb, I updated the command text used to import the JSON file through the terminal. 
Named the database uk_food
Reviewed one document in the establishments collection
Assigned establishments collection to a variable


Part 2: Update the Database
Inserted the record for Penang Flavours
Found the BusinessTypeID for "Restaurants/Cafe/Canteen" (it equals '1') BusinessType and updated the Penang document with this BusinessTypeID. 
Removed records associated with the Dover Local Authority and verified there were no more Dover documents and there were still documents remaining
Changed latitude and longitude to float types, and RatingValue to integers, while converting non-number values to Null

Part 3: Exploratory Analysis
Question 1: Which establishments have a hygiene score equal to 20?
    There are 41 establishments with a hygiene score of 20, and the results are contained within the NoSQL_analysis_starter.ipynb file
Question 2: Which establishments in London have a RatingValue greater than or equal to 4? 
    There are 33 establishments in London with a Rating greater than or equal to 4.
Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? 
    The businesses are: Volunteer, Plumstead Manor Nursery, Atlantic Fish Bar, Iceland, and Howe and Co Fish and Chips - Van 17
Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas. 
    There are 55 local authorities with at least one establishment with a hygiene score of 0. The count of establishments within the first ten localities is shown below: 

0	Thanet	1130
1	Greenwich	882
2	Maidstone	713
3	Newham	711
4	Swale	686
5	Chelmsford	680
6	Medway	672
7	Bexley	607
8	Southend-On-Sea	586
9	Tendring	542

