AI Cohort Daily Check-in & Analysis Tool

This is an interactive web application for daily check-ins within a group, such as an AI cohort or a classroom. It features two distinct views: a user-facing page for submitting check-ins and a private, password-protected admin dashboard for historical analysis and data export.

User View (/): Allows users to report their morale and understanding of recent material on a scale of 1 to 10. The system provides unique, personalized feedback and displays a live roster for the current day. The ability to check in is controlled by the instructor.

Admin Dashboard (/admin): A secure, multi-tabbed dashboard for instructors. It requires a password ("Instructor") to access.

* Session Control: Instructors can start and end the check-in availability for all users with the click of a button.
* Daily Summary Tab: Provides a historical log of all check-ins, grouped by date, with automatically calculated daily averages for both morale and understanding.
* Calendar Log Tab: Presents a chronological list of all days with check-in activity, allowing for quick access to specific dates.
* Student Analysis Tab: Lists every unique student and provides a collapsible, detailed view of their entire check-in history (date, time, and scores). This tab also includes a one-click button to export all historical data to an Excel (.xlsx) file for offline analysis.

Key Features

* Secure Admin Dashboard: A separate /admin URL protected by a login page.
* Instructor Session Control: Admin users can globally enable or disable the ability for students to check in.
* Persistent Data Storage: Check-ins, including timestamps, are saved to a local checkins.json file. The session status (open/closed) is saved in status.json.
* Comprehensive Analytics: The dashboard provides daily averages, a chronological log, and a detailed per-student breakdown.
* Export to Excel: All check-in data can be easily exported to an .xlsx file.
* Highly Personalized Feedback: Utilizes an extensive library of 200 unique responses for users.
* Modern, Professional UI: A sleek, dark, and translucent "frosted glass" design is used on both user and admin pages.

Technology Stack

* Backend: Python with Flask framework
* Frontend: HTML, JavaScript
* Styling: Tailwind CSS (loaded via CDN)
* Data Storage: JSON file
* Data Handling/Export: Pandas & openpyxl

How to Run This Project

To run this application on your local machine, follow these steps:

1. Save Files:
   * Save the app.py file to a new folder on your computer.
   * Save this README.md file into the same folder.

2. Open a Terminal or Command Prompt:
   * Navigate into the folder you just created (e.g., cd Desktop/my-checkin-app).

3. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```bash
   pip install Flask pandas openpyxl
   ```

5. Run the application:
   ```bash
   python app.py
   ```

6. Two files, checkins.json and status.json, will be created automatically in the folder to store the data.

7. Open your browser:
   * User View: Navigate to http://127.0.0.1:5000/
   * Admin Login: Navigate to http://127.0.0.1:5000/login (The password is Instructor)
   * Admin Dashboard: After logging in, you will be directed to http://127.0.0.1:5000/admin