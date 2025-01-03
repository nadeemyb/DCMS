# DCMS (Privacy by Design Enabled Dynamic Consent Management Systems: A Demonstration Perspective)
Steps for Using the Dynamic Consent Management System (DCMS)

Here are instructions for running your PHP and MySQL project on WAMP:

Unzip the Files: Extract the project folder onto your system.

Set Up the Database:

Open phpMyAdmin from the WAMP control panel.
Create a new database and import the provided .sql file into it.
Configure the Project:

Update the database credentials in the configuration file (e.g., db_config.php) to match your MySQL settings.
Run the Project:

Place the project folder in the www directory of WAMP.
Open a browser and go to http://localhost/<project-folder-name>.

This document provides a step-by-step guide for utilizing the Dynamic Consent Management System (DCMS), showcasing the roles of Subject, Controller, and Requester.
________________________________________
Login Credentials
Subject
•	Username: nadeem.yb@gmail.com
•	Password: 123
Controller
•	Username: c1@gmail.com
•	Password: 123
Requester
•	Username: requester@gmail.com
•	Password: 123
________________________________________
Steps for Using DCMS
1. Subject Logs into the System
•	Navigate to the login page.
•	Enter the Subject's credentials (nadeem.yb@gmail.com, 123).
•	View your medical reports on the dashboard.
________________________________________
2. Requester Submits a Formal Request
•	Requester logs in using their credentials (requester@gmail.com, 123).
•	Fills out a form specifying:
o	The type of data required.
o	Research-related details.
•	Submits the form, which is forwarded to the Controller's dashboard.
________________________________________
3. Controller Reviews the Request
•	The Controller logs in using their credentials (c1@gmail.com, 123).
•	Verifies the Requester's authentication.
•	Checks the system for relevant Subject data matching the request.
•	Filters data dynamically based on disease type or other parameters.
________________________________________
4. Controller Sends Consent Request to the Subject
•	After verification, the Controller sends a consent request to the Subject's dashboard.
________________________________________
5. Subject Responds to the Consent Request
•	Subject logs in to view the notification about the Requester's request.
•	Decides to Grant or Deny the consent request.
o	If Granted, the system notifies both the Controller and Requester.
o	If Denied, the process ends here.
________________________________________
6. Data Sharing and Revocation
•	Upon granting consent:
o	The system dynamically provides the Requester with the requested data.
•	The Subject retains the right to revoke consent at any time:
o	Once revoked, access is automatically restricted.
o	Data is removed from the Requester's view.
________________________________________
Transparency and Data Flow
•	All actions are logged for transparency.
•	The system ensures GDPR compliance and respects the Subject's autonomy.

Video Tutorial
The following video tutorial demonstrates the above working process in detail:
Click here to access the video tutorial on Google Drive (https://drive.google.com/file/d/1DCO99YcD48jDt2wH_5xFrF6yPdQ-d9Wl/view?usp=drive_link)
