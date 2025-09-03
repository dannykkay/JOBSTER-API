Jobster API is a comprehensive and secure full-stack application designed to help you manage your job search. The backend is a powerful API built with Node.js and Express, while the frontend is a production-ready React application. This system allows you to effortlessly track the status of your job applications, from initial submission to a final decision.

Key Features
Secure User Management: The API uses JSON Web Tokens (JWT) for authentication, ensuring that only you can access and modify your personal job application data. A dedicated route allows you to easily update your user profile.

Complete Job Lifecycle: The system supports the full CRUD (Create, Read, Update, Delete) cycle for job applications, allowing you to add new jobs, view them, update their status, and remove them as needed.

Advanced Data Analytics: Beyond simple tracking, the API provides powerful statistical insights into your job search. You can view a breakdown of your job statuses and see a historical timeline of monthly applications.

Robust Data Handling: The API features advanced query capabilities, enabling you to filter, sort, and paginate through your job applications for efficient data retrieval.

Production-Ready Architecture: Your project's architecture is optimized for deployment. It serves the React frontend directly from the Express server, ensuring a clean and single-origin setup for production environments.

API Security: To prevent abuse and ensure stability, your API includes a rate limiter on authentication routes and a special testUser feature that provides a read-only experience for testing purposes.
