# calendar-task-scheduler
Create Scheduled Tasks on Windows using calendar events

To run the script:
Download all files in this repo
Copy the Python script to a folder of your preference (I suggest creating a dedicated folder for the script as we'll be using a Python virtual environemt to run it)
Update values in the config.ini file based on your preferences
Using a terminal / command prompt, CD to the script's directory
Run the following to create a virtual environment `python -m venv venv` or `python3 -m venv venv` (check which one works for you)
Activate the virtual environment using `pmm-venv\Scripts\activate`
Install the following packages:
`pip install pywin32`
`pip install ics`
`pip install requests`
`pip install icalendar`
Run `python windows-task-scheduler.py`
