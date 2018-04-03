# MARS - Get your @mars.com for free

This is a simple mail application.
here we use 2 tables, users and message
user table has 4 col.:id,first name, last name and email
message table has 7 col: id, sender, receiver, subject, body, date,timestamp
Here the main page has 3 basic components:compose, inbox and sent mail. 
in compose, we compose the mail and the subject and the body gets updated in the message table
in inbox, the messages are shown. the body col. is directly retrieved from the message table and displayed.
in sent mail, all the messages sent by the admin is shown
