# Sending-Emails
### When we need to send an email to more than one person, it requires a lot of time and effort
### So we solve this problem by:
- Collect all eamils in Excel file 
- import excel file using pandas 
- import importanat libraries
   1. smtplib to connect the smtp server to send email
   2. import EmailMessage to create email formate
- Loop for all email rows in excel file
- create email structure
- send emails by smtp server
