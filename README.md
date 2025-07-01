# Week-3-Code-challengeSimple Blog Application
A basic web application for creating, viewing, editing, and deleting blog posts using a JSON server backend.
Features

Display a list of posts
View post details
Create new posts
Edit existing posts
Delete posts
Responsive form handling with validation

## Setup

Ensure a JSON server is running at "http://localhost:3000/posts" (e.g., using json-server --watch db.json).
Include the provided index.html, script.js, and style.css in your project.
Open index.html in a browser.

## Usage

Posts are listed on the left; click a post to view details.
Use the "New Post" form to create posts.
Click "Edit" or "Delete" on a post to modify or remove it.
Edit forms appear when editing; cancel to hide.

## Dependencies

JSON Server (for backend API)
Basic HTML/CSS/JavaScript (no external libraries)

## Notes

Ensure all form fields (title, author, content) are filled before submitting.
Image URLs are optional; defaults to a random image if not provided.
