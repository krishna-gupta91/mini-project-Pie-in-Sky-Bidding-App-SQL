# mini-project-Pie-in-Sky-Bidding-App-SQL
Questions – Write SQL queries to get data for the following requirements:

Show the percentage of wins of each bidder in the order of highest to lowest percentage.

Display the number of matches conducted at each stadium with the stadium name and city.

In a given stadium, what is the percentage of wins by a team which has won the toss?

Show the total bids along with the bid team and team name.

Show the team id who won the match as per the win details.

Display total matches played, total matches won and total matches lost by the team along with its team name.

Display the bowlers for the Mumbai Indians team.

How many all-rounders are there in each team, Display the teams with more than 4 all-rounders in descending order.

Write a query to get the total bidders points for each bidding status of those bidders who bid on CSK when it won the match in M. Chinnaswamy Stadium bidding year-wise. Note the total bidders’ points in descending order and the year is bidding year. Display columns: bidding status, bid date as year, total bidder’s points

Extract the Bowlers and All Rounders those are in the 5 highest number of wickets. Note

use the performance_dtls column from ipl_player to get the total number of wickets

Do not use the limit method because it might not give appropriate results when players have the same number of wickets

Do not use joins in any cases.

Display the following columns teamn_name, player_name, and player_role.

show the percentage of toss wins of each bidder and display the results in descending order based on the percentage

find the IPL season which has min duration and max duration. Output columns should be like the below: Tournment_ID, Tourment_name, Duration column, Duration

Write a query to display to calculate the total points month-wise for the 2017 bid year. sort the results based on total points in descending order and month-wise in ascending order. Note: Display the following columns:

Bidder ID, 2. Bidder Name, 3. bid date as Year, 4. bid date as Month, 5. Total points Only use joins for the above query queries.

Write a query for the above question using sub queries by having the same constraints as the above question.

Write a query to get the top 3 and bottom 3 bidders based on the total bidding points for the 2018 bidding year. Output columns should be: like: Bidder Id, Ranks (optional), Total points, Highest_3_Bidders --> columns contains name of bidder, Lowest_3_Bidders --> columns contains name of bidder;

Create two tables called Student_details and Student_details_backup.

Table 1: Attributes Table 2: Attributes Student id, Student name, mail id, mobile no. Student id, student name, mail id, mobile no.

Feel free to add more columns the above one is just an example schema. Assume you are working in an Ed-tech company namely Great Learning where you will be inserting and modifying the details of the students in the Student details table. Every time the students changed their details like mobile number, You need to update their details in the student details table. Here is one thing you should ensure whenever the new students' details come , you should also store them in the Student backup table so that if you modify the details in the student details table, you will be having the old details safely. You need not insert the records separately into both tables rather Create a trigger in such a way that It should insert the details into the Student back table when you inserted the student details into the student table automatically.
