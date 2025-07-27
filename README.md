# Google and Outlook Calendar Automation using Python
This repository conveys how to automate event creation in Outlook calendar and Google calendar. It can create:
- Events are generated via an .ics calendar files for Outlook.
- Real time updates to events in Google Calendar using Google Calendar API.

## Features
- Generate .ics file which can be imported into Outlook
- Create, update and delete events using python
- Required and optional all-day recurring events until a particular timeline

## Use Cases
- Course Schedules
- Meeting Invites
- Personal reminders

## Setup Instructions
- For Outlook, download icalendar, datetime and pytz library.
  Alternatively, create an environment using requirement.txt
- For Google Calendar:
  First set up Google Calendar API to make sure calendar is updated everytime it is changed:
  - Create a project for calendar in google cloud. If you already have a project that you want to reuse,
    you can do that, but it is a good idea to make a new project.
  - Activate the Google Calendar API for your project.
  - Go to API and Services -> OAuth Consent Screen and add your credentials.
  - Download credentials.json file and put it in the same directory as your python script.
  - After that, click on clients and create a new client.
  Install the modules necessary for Google Calendar from requirement.txt, or create an environment using
  requirement.txt

## Clone the Repository
git clone https://github.com/trahman64/google-outlook-calendar-python.git

## Install dependencies
pip install requirement.txt


