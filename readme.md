# Project contains two main processes.
- Process one: Request for Business Travel Approval
-	Process two: Business Travel settlement

# Project Team:
-	Lukasz Walenski s15585
-	Tomasz Faldrowicz s16280

# Develompent framework:
- Microsoft Power Platform 

# Project scope:
-	Development of application and testing
-	Documentation 
-	AzureDevOps as a tool to monitor Development progress
-	real data usage

- Application can be run on any mobile devile(IOS/Android), can be also embeded into Microsoft Teams
- Also will contain features not used in process but for learning purpose
- Main goal of application is to replace typical document management effort in company via automation.

# Basic Requirements:
 Process one: Request for Business Travel Approval
-	SharePoint list as a database
-	User creates a Travel Approval with proper information
-	Approval is sent to Manager, based on ActiveDirectory
-	Manager can approve/deline, add comments
-	After approval, notification is sent to User and next approval is sent to TravelExpenses Team for Final Approval 
-	After final approval (yes) user is notified
-	User can go thru his approvals via gallery
-	From Approved record user can create a Travel Settlement
-	User can add files, place signature
-	After sending Settlement (with files and signature) record is no longer visible for user
-	Signature can be send as attachment, as a pdf or embedded into email body (part of learning)

Process two: Business Travel settlement (Could Be DONE - high risht that process is to complex to be done)
-	Database: CommonDataService
- Main goal of this process is to create a big report with a signature and attachments.
- Report should contain fields like from where to where user was traveling, time, mean of transport, expenses, etc

As agred with Pawel Czapiewski - he will receive credentials to PowerPlatform for testing purpose
