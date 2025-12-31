Project Overview:
In this project, you will analyze a fictional music database using SQL to answer business
questions and uncover insights related to customers, sales, and music genres. This is an
opportunity to apply your SQL skills, including joins, grouping, filtering, sorting, and using CTEs
and window functions for advanced queries.
Dataset Structure:
Assume the database has the following tables:
1. employee: Contains details of employees, including their job title and seniority levels.
2. invoice: Contains all invoices with billing information.
3. customer: Contains customer data, such as first and last names and contact
information.
4. invoice_line: Detailed information on each item within an invoice.
5. track: Details of each track, including genre and duration.
6. album: Contains information on music albums.
7. artist: Information on artists.
8. genre: Information on genres.
Each table has relevant fields like customer_id, invoice_id, track_id, artist_id, etc., for joining
tables.
Instructions:
1. Easy Level Queries:
• Q1: Find the most senior employee based on job title.
o Hint: Use the employee table and sort by the levels column in descending order.
• Q2: Determine which countries have the most invoices.
o Hint: Group the invoice data by billing_country, then count and sort the results.
• Q3: Identify the top 3 invoice totals.
o Hint: Sort the invoice table by the total column.
• Q4: Find the city with the highest total invoice amount to determine the best location for
a promotional event.
• Q5: Identify the customer who has spent the most money.
o Hint: Use a join between customer and invoice, group by customer_id, and sum
the totals.
2. Moderate Level Queries:
• Q1: Find the email, first name, and last name of customers who listen to Rock music.
o Hint: Use joins across customer, invoice, invoice_line, and track, filtering for the
genre Rock.
• Q2: Identify the top 10 rock artists based on track count.
o Hint: Use joins across artist, album, and track and filter by the genre Rock.
Count tracks per artist.
• Q3: Find all track names that are longer than the average track length.
o Hint: Calculate the average length and compare each track’s length to this
average.
3. Advanced Level Queries:
• Q1: Calculate how much each customer has spent on each artist.
o Hint: Use a CTE to calculate the earnings per artist from invoice_line, then join it
with customer, invoice, and artist.
• Q2: Determine the most popular music genre for each country based on purchases.
o Hint: Use a CTE or window function to rank genres by purchase count per
country.
• Q3: Identify the top-spending customer for each country.
o Hint: Calculate the total spending per customer per country and filter for the
highest spending.
Guidelines for Completing the Project:
1. Step-by-Step Execution: Start by writing and executing each query in sequence. Ensure
each query is correct before moving to the next.
2. Use CTEs and Window Functions: For complex queries, break down the steps using
CTEs to make your query easier to read and understand.
3. Test and Validate Results: Use sample data to test each query's accuracy.
4. Document Your Queries: Add comments explaining your logic, particularly for more
complex queries.
5. Final Presentation: Summarize your findings, especially for questions related to
customer insights and sales, as they provide value to the business.
Expected Outcomes:
• A list of queries that return insights about the business, customers, and music trends.
• A final report summarizing insights such as the best city for events, top customers,
popular genres by country, etc.
ALL THE BEST!!!