<h1>Backend Features</h1>
Models

Lead: Tracks lead details (name, email, phone).
Follow-Up: Tracks follow-ups and their statuses (Pending, Completed, Missed).
User: Manages user roles (Admin, Sales Manager, Sales Rep).
Controllers:

CustomLoginController: Handles custom authentication logic.
CustomRegisterController: Manages user registration.
FollowUpController: Manages follow-up operations like scheduling and status updates.

Validation: Ensures unique email addresses and valid follow-up dates.

<h1>Frontend (React)</h1>
Leads List: Displays leads fetched from the API.
Follow-Up List: Displays follow-ups for each lead.
Forms: Create new leads and schedule follow-ups with proper validation.
Notifications: Real-time feedback using react-toastify.
Responsive Design: Built with Bootstrap for mobile-friendly.
