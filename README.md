## Student Timetable

A browser-based student planner for organizing classes, tracking attendance, and building study habits. The project is provided as standalone HTML files, so no build tools or server are required.

## Files

- **`student-timetable-standalone.html`** — bundled version of the timetable app. Its styles and Chart.js library are included in the file.
- **`timetable.html`** — original version of the app.

## Run it

Download or clone the project, then open `student-timetable-standalone.html` in a modern web browser. Create an account in the page to start using it.

## Features

- Dashboard with today's classes, attendance, study streak, XP, and weekly attendance chart
- Weekly class schedule and subject management
- Calendar-based attendance tracking and attendance summaries
- Attendance predictor for maintaining a target percentage
- Pomodoro focus timer
- Searchable notes, daily goals, and exam countdowns
- Multiple color themes
- Import and export of app data as JSON

## Data and privacy

The app saves account details and planner data in the browser's local storage. Data stays in that browser on that device; it does not automatically sync to other devices. Clearing browser storage can remove saved data, so use the JSON export to keep a backup.

The built-in account screen is for local/demo use and is not secure production authentication. Do not use it to store sensitive information or real passwords.

The standalone file bundles its CSS and charting library. Google Fonts and Font Awesome icons are loaded from online CDNs, so those fonts and icons may not appear without an internet connection.

## Contributing

To suggest changes to the original repository, create a fork, commit your changes to the fork, and open a pull request.
