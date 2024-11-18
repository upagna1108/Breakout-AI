# Breakout-AI
My project on custom email sender
Custom Email Sender with Brevo Integration This project is a custom email sender application that uses Brevo (formerly SendinBlue) API to send emails and track their delivery status. The application is built with Streamlit and allows users to upload a CSV file containing email data, customize the email content, and send bulk emails with real-time tracking. ## Features - Upload CSV file containing email data - Customize email subject and body with placeholders - Send bulk emails using Brevo API - Real-time email sending status and tracking dashboard
It can be done using the google api and it is secure because it needs to verified with ones mail
I used eOAuth2for secure email service connections.
The content in csv file place a major role and 
It is easy because it is integrated with Throttling technique which sends messages with in allocated time.
Using  Email Service Provider (ESP) we can able to track the delivery details.
We can see a dashboard below the application which gives information about whether the message is sent or seen.
firstly, iam using python(streamlit),google api s,
Upload CSV File
Click on the "Upload a CSV file" button.
Select your CSV file containing email data. Ensure the CSV contains a column named Email.
Customize Email Content
Enter the email subject and body in the provided input fields.
Use placeholders like {ColumnName} in the email body to dynamically replace them with values from the CSV file.
Authenticate and Send Emails
Enter your Brevo API key.
Click on the "Authenticate and Send All Emails" button.
The real-time dashboard will display the sending status and delivery status for each email.
