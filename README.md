# calendar-task-scheduler
Create Scheduled Tasks on Windows using calendar events

## To run the script:
1. Download all files in this repo
2. Copy the Python script to a folder of your preference (I suggest creating a dedicated folder for the script as we'll be using a Python virtual environemt to run it)
3. Update values in the config.ini file based on your preferences
4. Using a terminal / command prompt, CD to the script's directory
5. Run the following to create a virtual environment `python -m venv venv` or `python3 -m venv venv` (check which one works for you)
6. Activate the virtual environment using `venv\Scripts\activate`
7. Install the following packages:
 - `pip install pywin32`
 - `pip install ics`
 - `pip install requests`
 - `pip install icalendar`
8. Run `python windows-task-scheduler.py`

Use the included .bat file to run the script from Task Scheduler keep your tasks up to date.
