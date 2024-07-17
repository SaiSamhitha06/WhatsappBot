WhatsApp Bot for Hospital Appointments

This project is a WhatsApp bot designed to streamline the process of booking hospital appointments. It uses Botpress Studio for the bot interface, Make.com for webhook creation, and Google Spreadsheets for data storage.

   Features

  -->   Patient Information Management:   Stores and retrieves patient information from Google Spreadsheets and Botpress tables.
  -->   Appointment Scheduling:   Allows patients to book, modify, and cancel appointments via WhatsApp.
  -->   New and Existing Patients:   Differentiates between new and existing patients to provide a personalized experience.

   Setup and Configuration

     Prerequisites

  --> Botpress Studio
  --> Make.com account
  --> Google account for Google Spreadsheets

     Steps to Create the WhatsApp Bot

1.   Create a Bot in Botpress Studio:  
     --> Use Botpress Studio to design the conversational flow for booking appointments.
     --> Define the interactions and responses to guide users through the appointment process.

2.   Create a Webhook in Make.com:  
     --> Sign in to Make.com and create a new scenario.
     --> Add a webhook module to listen for incoming messages from the bot.
     --> Configure the webhook to receive data such as patient details and appointment information.

3.   Connect the Webhook to Google Spreadsheets:  
     --> Create a Google Spreadsheet to store patient information and appointment details.
     --> Use the Google Sheets module in Make.com to connect the webhook to your spreadsheet.
     --> Set up actions to add, update, or retrieve data from the spreadsheet based on the bot's interactions.

4.   Integrate the Bot with Google Spreadsheets:  
     --> In Botpress Studio, configure the bot to send and receive data from the Google Spreadsheet via the webhook.
     --> Store information about new and existing patients in the Botpress tables for quick access.

     Deployment

1.   Deploy the Botpress Bot:  
     --> Follow Botpress's deployment guide to host your bot on a server or cloud platform.
     --> Ensure your bot is accessible and can interact with users on WhatsApp.

2.   Set Up WhatsApp Integration:  
     --> Use a service like Twilio to connect your bot to WhatsApp.
     --> Configure Twilio to forward WhatsApp messages to your bot's endpoint.

   Usage

1.   Start a Conversation:  
     --> Users can start a conversation with the bot on WhatsApp.
     --> The bot will guide them through the process of booking an appointment.

2.   Provide Information:  
     --> Users will be asked to provide their details (e.g., name, contact information) if they are new patients.
     --> Existing patients will be recognized and their information retrieved from the database.

3.   Book, Modify, or Cancel Appointments:  
     --> Users can book new appointments, modify existing ones, or cancel them as needed.
     --> The bot will update the information in the Google Spreadsheet accordingly.

