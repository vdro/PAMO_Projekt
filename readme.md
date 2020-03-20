# Project contains two main processes.
•	Process one: Request for Business Travel Approval
•	Process two: Business Travel settlement

Project Team:
•	Lukasz Walenski s15585
•	Tomasz Faldrowicz s16280

Develompent framework:
Microsoft Power Platform 

Project scope:
•	Development of application and testing
•	Documentation 
•	AzureDevOps as a tool to monitor Development progress
•	real data usage

Application can be run on any mobile devile(IOS/Android), can be also embeded into Microsoft Teams
Also will contain features not used in process but for learning purpose
Main goal of application is to replace typical document management effort in company via automation.

Basic Requirements:
•	Process one: Request for Business Travel Approval
o	SharePoint list as a database
o	User creates a Travel Approval with proper information
o	Approval is sent to Manager, based on ActiveDirectory
o	Manager can approve/deline, add comments
o	After approval, notification is sent to User and next approval is sent to TravelExpenses Team for Final Approval 
o	After final approval (yes) user is notified
o	User can go thru his approvals via gallery
o	From Approved record user can create a Travel Settlement
o	User can add files, place signature
o	After sending Settlement (with files and signature) record is no longer visible for user
o	Signature can be send as attachment, as a pdf or embedded into email body (part of learning)
•	Process two: Business Travel settlement
o	Database: CommonDataService
Main goal of this process is to create a big report with a signature and attachments.
Report should contain fields like from where to where user was traveling, time, mean of transport, expenses, etc
