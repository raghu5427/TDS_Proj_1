# TDS_Proj_1
This Repo is created for Project 1 of Tools in DS course.

# 1
This Python script leverages the GitHub API to retrieve user data for individuals located in Toronto with over 100 followers, along with details about their public repositories. Here’s a summary and breakdown of each part:
**Summary**
The script uses the GitHub API to:
Find all users in Toronto with over 100 followers.
 - This step had multiple pages, so I had to iterate until there is no more data to append to the List. 
Fetch each user’s profile details.
- This Extracted User List is loaded into the users.csv
Retrieve each user’s public repositories.
- By iterating to each of the User Login, I went to another API endpoint which provided repo details.
Save both user details and repository information to CSV files (users.csv and repositories.csv).

Most Surprising and Interesting data I found after ANalysing the DATA:
- There is a steady decline of new Toronto users from 2012. This number is almost 97% down from the number in 2012.

Action for future developers:
The program ran for more than 15-20 minutes, the number of API calls that were made was huge, in fact at one point the connection could not be established. For each user ID we were making repository call. The code should be written in a optimized way. 
