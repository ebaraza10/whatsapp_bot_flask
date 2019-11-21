#A Whatsapp bot in flask

##Functionality supported:
Allow users to set reminders with dates and reminder messages via Whatsapp
Automatically sends set reminders on the chosen date via Whatsapp

##Technologies used:
Python(Flask)
Google sheets(storage of reminders/database)
Docker


##How to setup:
Setup and enable Google sheets API. 
Rename .env_template to .env
Edit .env variables to match your environement
Run docker-compose -f docker-compose.yml up -d