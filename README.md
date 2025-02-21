#!/bin/bash
# submission_reminder_app_Nkennyelvis
Submission Reminder Application
This Bash script automates the setup of a submission reminder application that alerts students about upcoming assignment deadlines.
Files and Directory Structure
create_environment.sh   # Script to set up the environment
submission_reminder_{Username}/
./config/
|____config.env          # Stores assignment details and deadline
./assets/
|____submissions.txt     # Contains student submission records
./modules/
|____Functions.sh        # Helper functions for checking submissions
./app/
reminder.sh         # Runs the reminder script based on the assignment deadline
startup.sh              # Launches the submission reminder app
Setup and Usage
Step 1: Clone the Repository
git clone https://{Your personalToken}@github.com/yourgithubusername/submission_reminder_app_githusername.git
cd submission_reminder_app_githusername
Step 2: Run the Setup Script
chmod +x create_environment.sh
./create_environment.sh
The script will prompt you for your name and create the necessary directories and files.
Step 3: Start the Application
chmod +x startup.sh
./startup.sh
This will run the reminder application and display students who haven't submitted their assignments.
Permissions
Ensure all scripts are executable:
chmod +x startup.sh app/reminder.sh modules/functions.sh
