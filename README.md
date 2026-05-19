Social Network Data Cleaner
Problem Statement

Social network data can contain duplicate records, inactive users, and missing information. Cleaning this data manually is time-consuming and can lead to errors.

Solution

This project cleans and processes social network JSON data automatically using Python.

Input

data.json

Contains:

User details
Friend connections
Liked pages
Output

data_result.json

A cleaned JSON file with:

Valid users
Unique friend lists
Removed duplicate pages
Business Rules Used
Remove users with empty names
Remove duplicate friends
Remove inactive users
Remove duplicate pages
Technologies Used
Python
JSON
How to Run
Place data.json in the project folder.
Run the script:
python main.py
Check data_result.json for cleaned data.
Use Case

This project helps clean social network datasets before analysis, storage, or further processing.
