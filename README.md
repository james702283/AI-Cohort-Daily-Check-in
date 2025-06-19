AI Cohort Daily Check-in & Analysis Tool

This is an interactive web application for daily check-ins within a group, such as an AI cohort or a classroom. It features two distinct views: a user-facing page for submitting check-ins and a private admin dashboard for historical analysis.

User View (/): Allows users to report their morale and understanding of recent material on a scale of 1 to 10. The system provides unique, personalized feedback and displays a live roster for the current day.

Admin Dashboard (/admin): Provides instructors with a historical log of all check-ins, grouped by date. It automatically calculates and displays the daily average for both morale and understanding, serving as a powerful tool for tracking trends and improving lessons.

(Note: This is a placeholder image link. You would replace this with a screenshot of your actual application.)

## Key Features

* Separate User and Admin Views: Provides a simple check-in interface for users and a powerful data analysis dashboard for instructors at a separate /admin URL.
* Persistent Data Storage: Check-ins are saved to a local checkins.json file, creating a permanent historical record.
* Daily Analytics: The admin dashboard automatically calculates and displays the average morale and understanding scores for each day.
* Highly Personalized Feedback: Utilizes an extensive library of 200 unique responses to generate tailored feedback based on the user's specific scores.
* Modern, Professional UI: Features a sleek, dark, and translucent "frosted glass" design.
* Live Roster (User-Facing): The main page shows a list of check-ins for the current day only.

## Technology Stack

* Backend: Python with Flask framework
* Frontend: HTML, JavaScript
* Styling: Tailwind CSS (loaded via CDN)
* Data Storage: JSON file

## How to Run This Project

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

4. Install the required dependency (Flask):
   ```bash
   pip install Flask
   ```

5. Run the application:
   ```bash
   python app.py
   ```

6. A file named checkins.json will be created automatically in the folder to store the data.

7. Open your browser:
   * User View: Navigate to http://127.0.0.1:5000/
   * Admin View: Navigate to http://127.0.0.1:5000/admin

Last updated: June 19, 2025 