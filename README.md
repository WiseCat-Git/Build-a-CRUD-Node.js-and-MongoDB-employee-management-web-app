# Build-a-CRUD-Node.js-and-MongoDB-employee-management-web-app

# Main Project structure

employee-management-app/
├── server.js
├── models/
│   ├── employee.js
│   └── department.js
├── routes/
│   ├── employee.js
│   └── department.js
├── public/
│   ├── index.html
│   ├── style.css
│   └── app.js
└── package.json

# Project Overview:

The Apollonia Dental Practice team aimed to lay the groundwork for a digital employee management system. The goal was to create a CRUD (Create, Read, Update, Delete) web application to store and manage information about their employees and departments. This system serves as a foundation for future expansions, such as assigning patients to staff members and managing projects within the practice.

# Technologies Used:

Backend: Node.js, Express.js, MongoDB, Mongoose
Frontend: HTML, CSS, JavaScript
Tools: MongoDB Compass, Postman (for API testing)
Achieved Objectives:

# Database Creation:

MongoDB was used to create a database named apollonia_db, containing two collections: employees and departments.

Mongoose was employed to define schemas for both employees and departments, enforcing data structure and validation.
Web UI for Employee and Department Management:

A responsive and user-friendly web interface was developed using HTML, CSS, and JavaScript.

The UI allows users to perform CRUD operations on employees and departments, such as adding new entries, viewing existing ones, and deleting them.

# CRUD Operations Implementation:

1. Create: Forms were provided to add new employees and departments. Upon submission, the data is sent to the server and stored in the MongoDB collections.

2. Read: The application fetches and displays lists of employees and departments from the database, updating the UI dynamically.
Update: While this initial version does not include an update feature, the foundation is laid to easily incorporate this in future iterations.

3. Delete: Users can delete employees and departments directly from the UI, which also removes the corresponding entries from the MongoDB collections.

# Backend Integration:

Express.js was used to handle server-side logic and routing. The server manages API endpoints for performing CRUD operations, ensuring seamless communication between the frontend and backend.

Static files were served using Express, allowing the frontend to interact with the backend API.
Testing and Validation:

The functionality was tested by adding and deleting employees and departments through the UI.
MongoDB Compass was used to validate that the operations were correctly reflected in the database.

# Conclusion:

The project successfully met all the defined objectives. The result is a functional and extendable employee management web application that provides a solid foundation for Apollonia Dental Practice's digital transformation journey. Future enhancements can include more advanced features like assigning patients, role-based access control, and detailed analytics.
