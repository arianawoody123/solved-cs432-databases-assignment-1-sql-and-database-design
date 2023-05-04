Download Link: https://assignmentchef.com/product/solved-cs432-databases-assignment-1-sql-and-database-design
<br>
<strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Submission guidelines</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">:​ Submit the zipped folder containing all the files (database, an image of the database schema, and pdf containing screenshots of all the SQL queries) using the </span><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://forms.gle/UKhFTS9aHYKkqxV27">Google</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://forms.gle/UKhFTS9aHYKkqxV27">form</a><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://forms.gle/UKhFTS9aHYKkqxV27">.</a><u style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​</u><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> Rename your submission as ‘Roll number_Name’. Submissions in the incorrect format will not be accepted. </span><strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Any</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​</span><strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> late submission will be summarily given zero marks without any further discussion.</strong>

<h1>____________________________________________________________________________</h1>




As a Software Engineer, you are asked to design a database schema of an E-Commerce platform XYZ. XYZ is an online marketplace for three types of products – books, electronics, and furniture.

Following functionalities are made available to the customers:

<ul>

 <li>Search for products.</li>

 <li>Browse through products available on sale.</li>

 <li>Add products to their cart and save for later.</li>

 <li>Buy products.</li>

 <li>Rate and add reviews for products they bought in the past.</li>

 <li>Browse through their past orders.</li>

 <li>[<em>Functionality</em>​ <em> for Bonus marks</em>​] Products recommendation by the platform based on their purchase and search history.</li>

</ul>




A user can signup on the platform by using a valid email id and password.




XYZ has a fixed set of retailers in various cities from which it procures products.




Each product contains information about the Retailer from which it was purchased by the platform, along with other information like description, date of manufacture, etc. Product prices are dynamic and can be updated.




Create a database schema for the above application. Your database must include the name of the tables you have identified, the attributes of the table and the integrity constraints like Primary key, Foreign key, and NOT NULL.<strong>  </strong>

<strong>[5 marks = 3 (table and attribute definitions) + 2 (defining integrity constraints)] </strong>




Write SQL queries for the following questions. Questions 1-20 carry 2 marks each. Question 21

(bonus question) carries 5 marks. <strong>No partial marks for questions 1-20.</strong>​




<ol>

 <li>Populate the tables with at least 10 dummy records. (You can use a dummy data</li>

</ol>

generator, but please ensure that the database constraints are satisfied.)

<ol start="2">

 <li>Delete a user from the database. After deleting the user update name of the user as ‘Anonymous’ in all the ratings and reviews written by that user.</li>

 <li>Decrement the price of all products priced above Rs. 5000 by 10%, which were viewed by less than 10 users in the last 3 months.</li>

 <li>Add 2 delivery addresses for a user with userid = 101.</li>

 <li>Find all retailers and their email addresses who operate from the city ‘Delhi’.</li>

 <li>Find email addresses of all users who reside in the city ‘Mumbai’ and have made a total purchase greater than or equal to Rs. 5000 in the past.</li>

 <li>Find all products in the database whose name contains the string <em>‘le’</em>​ ​. E.g. Apple, Oracle, etc.</li>

 <li>Find the last 3 orders of the first user.</li>

 <li>Find products in the cart of the second user.</li>

 <li>List all books published after 2001.</li>

 <li>List all electronics products in the price range 10k-20k.</li>

 <li>List all furniture pieces by the retailer ‘Ikea’.</li>

 <li>Sort all laptops according to the price in increasing order.</li>

 <li>List all products that were added to the database after 27/07/2019.</li>

 <li>List all books authored by ‘Franz Kafka’.</li>

 <li>Print the UserId and EmailId of all users who have saved a product in the cart, whose quantity is less than 3.</li>

 <li>Find the order with the maximum number of products.</li>

 <li>List all products added to the database in the past 10 days.</li>

 <li>List all retailer ids whose products, userid = 55 has purchased.</li>

 <li>Write a query to update the discount on all new products by 5% and store it as a new table Diwali_Deals.</li>

 <li>[<em>Bonus</em>​<em> Question</em>​] List the top 10 recommended products for the userid=101 based on the user’s purchase and search history.</li>

</ol>





