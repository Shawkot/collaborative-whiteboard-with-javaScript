# Collaborative Whiteboard Application

Welcome to the Collaborative Whiteboard, a cutting-edge application designed to enable real-time, interactive communication among multiple users through a shared digital whiteboard interface.

# Technical Overview
The application is engineered using Node.js and Socket.IO to establish a robust and efficient server-side infrastructure, ensuring seamless real-time interaction. On the client side, jQuery is employed to provide a responsive and user-friendly experience, while MongoDB is utilized as the database solution to manage data efficiently.

# Key Features
Draw: Utilize the brush tool for free-hand drawing directly on the whiteboard. Initial support includes a single brush size and color, optimized for simplicity and ease of use.

Erase: Effortlessly remove drawings with the eraser tool, offering a clean slate for new ideas.

Undo: Revert any recent drawing or erasing actions to correct mistakes or reconsider changes.

Sticky Notes: Enhance your whiteboard with interactive sticky notes. Add, move, edit, or delete notes as needed, with a confirmation step for deletions to prevent accidental loss of information.

Image Upload: Enrich discussions by uploading images to the whiteboard, providing a visual aid to your collaborative efforts.

Commenting on Images: Interact with uploaded images by adding, viewing, editing, or hiding comments, facilitating detailed discussions and feedback.

Download Whiteboard: Save a snapshot of your whiteboard as a PNG file, allowing you to preserve and share the state of your collaborative workspace.

Session Management: Join or leave sessions at your convenience. Hosts can end sessions for all users, with a confirmation, if you are the host of the session and you decide to leave, the session will terminate for every connected user.

# Roadmap
- [ ] Enhanced Real-Time Collaboration: Plans to evolve the whiteboard for improved synchronous interaction among a greater number of users.
- [ ] UI Improvements: Ongoing development focused on refining user interface components for an even more intuitive and engaging user experience.

# Installation Guide
To get started with the Collaborative Whiteboard, follow these simple steps:
- Prerequisites: Ensure MongoDB is installed on your system.
- Clone the Repository: Download the source code by cloning the repository.
- Project Setup: Navigate to the project directory in your terminal.
- Dependencies: Execute `npm install dotenc` followed by `npm install` to install all necessary dependencies.
- Start the Application: Run `npm run start` to launch the server.
- Access the Application: Open a web browser and navigate to `localhost:3000` to start using the whiteboard.
