# Google Calendar Automator
Scrapes calendar events from HTML table data and uploads them to your calendar through the Google Calendar API. This saves the user from having to manually transfer every event on a webpage to their calendar.

Schedules and events in HTML are usually stored in tables. With BeautifulSoup, we can more easily parse through a table's rows and columns. This project retrieves the relevant event data such as time and description and converts into a JSON. The JSON is then sent to the Google Calendar API, which is able to populate a calendar through JSON data. 

## Getting Started

### Installing
Requires Python 2 and BeautifulSoup4

Install BeautifulSoup4 with `pip install BeautifulSoup4`

Clone the repository with `git clone https://github.com/DNishanth/Google-Calendar-Automator.git`

### Usage
Test with test_mahacks.py and test_soccer.py

### Notes
- Team Members: Nishanth Duraiarasu, Tyler Jiang, Kevin Kelly, Randy Wang
- Prize Winner at [MAHacks 2017](https://www.hackerearth.com/sprints/mahacks-spring-2017/)
