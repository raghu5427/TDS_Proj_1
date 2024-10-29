# TDS_Proj_1
This Repo is created for Project 1 of Tools in DS course.

# 1
This Python script leverages the GitHub API to retrieve user data for individuals located in Toronto with over 100 followers, along with details about their public repositories. Here’s a summary and breakdown of each part:
**Summary**
The script uses the GitHub API to:
Find all users in Toronto with over 100 followers.
Fetch each user’s profile details.
Retrieve each user’s public repositories.
Save both user details and repository information to CSV files (users_1.csv and repositories_1.csv).

Scraping : 
* As a first step I created a response object by queriying the API with all User Data pertaining to Toronto and has minimum of 100 followers
* As a next step in my codeflow - I call a functio to get the User data fields as per the project requirement.
* For each of the User I iterated to pick the repo details and using that  
