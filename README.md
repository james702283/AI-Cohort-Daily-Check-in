# AI Cohort Daily Check-in

This is an interactive web application designed for members of a group, such as an AI cohort, a development team, or a classroom, to perform a daily check-in. It allows users to report their current morale and their understanding of recent material on a scale of 1 to 10. The system provides unique, personalized, and encouraging feedback and displays the results on a live roster.

(Note: This is a placeholder image link. You would replace this with a screenshot of your actual application.)

## Key Features

* Dual-Metric Input: Collects two key data points from each user: emotional well-being (morale) and learning progress (understanding).
* Highly Personalized Feedback: Utilizes an extensive library of 200 unique responses to generate tailored feedback based on the user's specific scores.
* Modern, Professional UI: Features a sleek, dark, and translucent "frosted glass" design over a high-quality background image.
* Live Roster: Displays a real-time list of all users who have checked in, fostering a sense of community and shared experience.
* User-Friendly Interface: Includes clear instructions, intuitive input fields, and helpful error handling for a smooth user experience.
* Encouraging Tone: All user-facing text is crafted in a positive, supportive, and motivational tone to foster a safe and encouraging environment.

## Technology Stack

* Backend: Python with Flask framework
* Frontend: HTML, JavaScript
* Styling: Tailwind CSS (loaded via CDN)

## How to Run This Project

To run this application on your local machine, follow these steps:

1. Save Files:
   * Save the app.py file to a new folder on your computer.
   * Save this README.md file into the same folder.

2. Open a Terminal or Command Prompt:
   * Navigate into the folder you just created. For example: `cd Desktop/my-checkin-app`

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

6. Open your browser:
   * Navigate to http://127.0.0.1:5000 to see and use the application. 