# Google Calendar Quickstart

Complete the steps described in the rest of this page to create a simple Python command-line application that makes requests to the Google Calendar API.

## Step 1: Enable the Google Calendar API

To start using the script you first need to go to https://developers.google.com/calendar/quickstart/python and press the "ENABLE THE GOOGLE CALENDAR API" to activate it. 

Then, in resulting dialog, click the **DOWNLOAD CLIENT CONFIGURATION** and save the file **credentials.json** to your working directory.

## Step 2: Install the Google Client Library

Run the following command to install the library using pip:

`pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`

## Step 3: Running the program

Run the sample using the following command:

`python calendar.py`

### Prerequisites and Notes

To run this quickstart, you'll need:

* Python 2.6 or greater
* The pip package management tool
* A Google account with Google Calendar enabled
* Authorisation information is stored on the file system, so subsequent executions will not prompt for authorisation.
