# university-project-managing-bug-fixes
# Web App for Managing Bug Fixes
The project involves the development of a web application dedicated to the management and resolution of bugs within a software application. The main purpose of the application is to facilitate communication between members of a development team to identify, monitor, and resolve bugs efficiently.
# Key Features
- Single Page Application (SPA) architecture accessible from various devices: desktop, mobile, and tablets.

- User Authentication: Students can log in with an email-based account.

- Project Monitoring: Ability to register software projects for bug tracking.

- Bug Management: Log bugs with information like severity, priority, description, and associated commit link.

- Role-Based Permissions: Manage access rights for project members to add and modify projects or update bug statuses, while testers can add new bugs.
# Project Structure
The project focuses on understanding and developing the interaction between the front-end and back-end within a web application, specifically for bug management and resolution.
# Front-End
The structure of the project is organized into three main components:

- HTML, CSS, JavaScript: The project is organized into separate components with individual files for each. This modular development allows for efficient code management.
- Client-Server Architecture: Emphasizes the importance of the front-end in providing a pleasant and functional user experience
# Back-End
The back-end is responsible for managing bug fixes and handling operations related to collections, bugs, and users. Key components include:

- Controllers:
  - bugs.js: Handles operations for bug collection, with a focus on the create and update functions for data manipulation.
  - users.js: Manages user-related operations, with emphasis on the create and update functions for user data management.
- Models:
  - bugs.js and users.js: Define the data structures and relationships in the database.
- Routes:
  - API routes are defined in bugs.js and users.js, improving request handling and error management.
- Services:
  - CRUD operations are performed using bugs.js and users.js modules, where data consistency bugs are identified and fixed.
- Main:
  - Configures the Express server, manages middleware, and handles database connections to ensure overall stability.
# Conclusion
By addressing and fixing bugs in each section, the goal is to improve the overall quality and stability of the application. The project emphasizes the importance of effective communication and collaboration within development teams to manage software bugs efficiently.

# Demonstration

