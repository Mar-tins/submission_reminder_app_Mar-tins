# Submission Reminder App

This project is a simple reminder application built with shell scripting. It helps to alert students about upcoming assignment deadlines by checking submission records.

## Repository Structure

- **create_environment.sh:**  
  A shell script that sets up the directory structure and populates all necessary files for the app.
  
- **README.md:**  
  This file, which explains how to set up and run the application.
  
- **Generated Directory (submission_reminder_app_yourName):**  
  When you run the script, it creates a folder named `submission_reminder_app_yourName` (where `yourName` is the input you provide), containing:
  - **config/**  
    Contains `config.env` with configuration details.
  - **modules/**  
    Contains `functions.sh` which has helper functions.
  - **assets/**  
    Contains `submissions.txt` with student submission records.
  - **reminder.sh:**  
    The main script that reads configurations and executes the reminder function.
  - **startup.sh:**  
    A script to start the reminder app by calling `reminder.sh`.

## Prerequisites

- A Linux/Unix based operating system.
- Bash shell installed.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Mar-tins/submission_reminder_app_Mar-tins.git
   cd submission_reminder_app_Mar-tins
