# Backend Coding Challenge

At aspaara a squad of superheroes works on giving superpowers to planning teams.
Through our product dashboard, we give insights into data – a true super-vision
superpower. Join forces with us and build a dashboard of the future!

![aspaara superhero](aspaara_superhero.png)

## Goal

Create a simple backend application that provides an API for a dashboard which
allows a planner to get insights into client and planning information.

You will find the corresponding data that needs to be imported into the database
in `planning.json`, which contains around 10k records.

## Requirements

1. Create proper database tables that can fit the data model.
2. Create a script that imports the data into the database (sqlite).
3. Create REST APIs to get the planning data from the database.
    1. The APIs don't need to be complete, just create what you can in the
       available time.
    2. Please include at least one example on how to do each of the following:
        1. pagination
        2. sorting
        3. filtering / searching

## Data Model

* ID: integer (unique, required)
* Original ID: string (unique, required)
* Talent ID: string (optional)
* Talent Name: string (optional)
* Talent Grade: string (optional)
* Booking Grade: string (optional)
* Operating Unit: string (required)
* Office City: string (optional)
* Office Postal Code: string (required)
* Job Manager Name: string (optional)
* Job Manager ID: string (optional)
* Total Hours: float (required)
* Start Date: datetime (required)
* End Date: datetime (required)
* Client Name: string (optional)
* Client ID: string (required)
* Industry: string (optional)
* Required Skills: array of key-value pair (optional)
* Optional Skills: array of key-value pair (optional)
* Is Unassigned: boolean

## Used Tech Stack

* Python 3.8+
* Flask
* Bootstrap

## Additional details

* Use `Shift` + `Enter` to each cell in notebook
* After Running last cell go to `http://127.0.0.1:5000` 
* Wait till the page loads
* Implemented Features:
	1. pagination (option to select entries per and current page)
    2. sorting (option to sort each columns)
    3. filtering / searching (option to search/filter)

## Additional details

* Forked the project, Made changes, pushed it into Git and added `sundara.amancharla@aspaara.com` as a contributor.
* All the codes are present in main.ipynb file.
* Structure of main.ipynb
    * Database creation `planner.db`
    * Display of Database description
    * Database updation using `planning.json`
    * Creation a simple backend application using `Flask` and `Bootstrap` that provides an API for a dashboard which
	  allows a planner to get insights into client and planning information.
* Time taken for completion `4 hours`