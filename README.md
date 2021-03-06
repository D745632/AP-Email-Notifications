# AP-Email-Notifications

## Getting Started 

These files will help you understand how to get a similar project up and running on your local machine for development and testing purposes. Reach out to GSA at rpa.gsa.gov for notes on how to deploy the project on a live system.

Note that many of these bots touch on and operate in a system unique to GSA, and moderate to substantial modification may be required for your system to run the process. 

## Software Used in this Process
* UiPath Studio
* G-mail (EAS) 
* Microsoft Share Drive 
* Microsoft Excel

## Built with 
* UiPath Studio 

## Description  
The Accounts Payable Email Notification BOT was developed to automate email notifications for outstanding invoices pending a Receiving Report.  The BOT uses the daily Outstanding Invoice Report from GSA Finance, an EASi (a GSA system for managing contracts and acqusitions) Award Team List updated weekly from Business Intelligence and an employee/supervisors list to generate the email notifications.  There is a separate Missing Contact list for all awards outside of EASi.  The emails are sent on Day 1, 5, 10, 15, 20, and 25 to the CO, COR, CS and supervisors after Day 15. The process automatically escalaltes - the bot will start off with a lower level contact, and then escalate to higher individuals until it gets a response. The BOT is triggered manually at 7am, 10am, 2pm, and 6pm ET.   

## Developer & Authors
Mike Greise, GSA IT
