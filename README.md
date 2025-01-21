# Maven_Movies_Rental_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business

## Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

## Project Objectives:

### Customer Insights:

Identify customer details (names, emails) for targeted marketing campaigns.
Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:

Explore the rental inventory and classify movies based on rental rates and availability.
Provide recommendations for expanding the movie collection based on popularity and rental rates.
Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories.
Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:

Help track and manage movie inventory effectively.
Highlight gaps in the inventory and optimize stock levels.

### Tools & Library Used 

[<img src="./my sql logo.png" alt="myql-logo" width="100"/>](https://www.mysql.com/) &nbsp;

# Project Result

[Click here to get full code](https://github.com/adeebhashmi55/MOVIE_RENTAL_SQL_PROJECT/blob/main/code%20movies%20rental.sql)

# Query Task

1. Extract the first name, last name, and email address of all customers to prepare a comprehensive contact list for the marketing team.

 <img src="CODE OUTPUT/email ids.PNG"  height="150"  />&nbsp;

2. Analyze the rental rates and determine the number of movies in each rental category.

 <img src="CODE OUTPUT/rental rate category.PNG" />&nbsp;

3. Find the rating category with the most films.

 <img src="CODE OUTPUT/RATING CATEGORY COUNT.PNG" />&nbsp;

4. Find the most prevalent rating in each store.

 <img src="CODE OUTPUT/RATING CATEGORY PER STORE.PNG" />&nbsp;

 5. List of films with their Name, Category, and Language.

<img src="CODE OUTPUT/TITLE_LANG_CATEGORY.PNG" />&nbsp;

6. Count how many times each movie has been rented.

<img src="CODE OUTPUT/POPULARITY_MOST_RENTAL.PNG" />&nbsp;

7. Top 10 films by revenue

<img src="CODE OUTPUT/TOP 10 REVENUE.PNG" />&nbsp;

8. Customer with the highest spending

<img src="CODE OUTPUT/TOP 1 SPENDING CUST.PNG" />&nbsp;

9. Which store has brought the most revenue

<img src="CODE OUTPUT/PER STORE REVENUE.PNG" />&nbsp;

10. How many rentals do we have for each month

<img src="CODE OUTPUT/RENTALS_PER_MONTH.PNG" />&nbsp;

11. Identify and reward customers who have rented a minimum of 30 times, including their phone number and email ID

<img src="CODE OUTPUT/LOYAL_30_CUST_ALL_DESC.PNG" />&nbsp;

12. Retrieve all payment records for the first 100 customers, ordered by customer ID

<img src="CODE OUTPUT/FIRST_100_CUST.PNG" />&nbsp;

13. Retrieve payment records over $5 for the first 100 customers (ordered by customer ID), since January 1, 2006

<img src="CODE OUTPUT/OVER_$5_.PNG" />&nbsp;

14. Retrieve all payment records from the first 100 customers, along with payments over $5 from any customer

<img src="CODE OUTPUT/SPECIFIC_CUST.PNG" />&nbsp;

15. Retrieve a list of films that include a 'Behind the Scenes' special feature

<img src="CODE OUTPUT/SPECIAL_FEATURES.PNG" />&nbsp;

16. Retrieve unique movie ratings along with the count of movies for each rating

<img src="CODE OUTPUT/RATING_NOOF_MOVIES.PNG" />&nbsp;

17. Retrieve a count of titles, grouped by rental duration

<img src="CODE OUTPUT/RATING_RENTAL_SLICED_@.PNG" />&nbsp;

18. Retrieve movie ratings, the count of movies for each rating, average movie length, and compare with rental duration

<img src="CODE OUTPUT/RATING_COUNT_LENGTH.PNG" />&nbsp;

19. Retrieve the count of films, along with the average, minimum, and maximum rental rates, grouped by replacement cost 

<img src="CODE OUTPUT/REPLACEMENT_COST_IF.PNG" />&nbsp;

20. Retrieve a list of customer IDs who have rented fewer than 15 times in total

<img src="CODE OUTPUT/LESS_THAN_15_RENT.PNG" />&nbsp;

21. Retrieve a list of all film titles, along with their lengths and rental rates, sorted from longest to shortest

<img src="CODE OUTPUT/length&rentalprice.PNG" />&nbsp;

22. Categorize movies as per length

<img src="CODE OUTPUT/movies_length_bucket.PNG" />&nbsp;

23. Categorize movies to recommend based on various age groups and demographics

<img src="CODE OUTPUT/recomm_sys.PNG" />&nbsp;

24. Retrieve a list of the first and last names of all customers, along with their store and activity status (e.g., 'store 1 active', 'store 1 inactive', 'store 2 active', or 'store 2 inactive')

<img src="CODE OUTPUT/CUST_STORE_ACTIVITY.PNG" />&nbsp;

25. Retrieve a list of all films in inventory, including the film title, description, associated store_id, and inventory_id

<img src="CODE OUTPUT/FILM_INVENTORY.PNG" />&nbsp;

26. Retrieve the first name, last name, and the count of movies for each actor

<img src="CODE OUTPUT/ACTOR_NO_OF_FILMS.PNG" />&nbsp;

27. Retrieve a list of all film titles, along with the count of actors associated with each title

<img src="CODE OUTPUT/INVESTOR_REQUEST.PNG" />&nbsp;

28. Retrieve a list of all actors, along with the titles of the films they appear in

<img src="CODE OUTPUT/ACTOR_N_APPEARANCE.PNG" />&nbsp;

29. Retrieve a list of distinct film titles and their descriptions currently available in the inventory at Store 2

<img src="CODE OUTPUT/EXPANSION.PNG" />&nbsp;

30. Retrieve a unified list of all staff and advisor names, including a column indicating their role as either 'Staff' or 'Advisor'

<img src="CODE OUTPUT/CONFERENCE_LIST.PNG" />&nbsp;
