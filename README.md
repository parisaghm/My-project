# Project-Planner
Project Planner with Vue.js

# Overview
The Project Planner is a Vue.js web application that helps you manage your projects. You can create, edit, and delete projects, as well as mark them as complete or ongoing. This project uses a JSON server to simulate a backend and stores projects in a local database.

# Features

- Add Project: Create a new project with a title and details.
- Edit Project: Update the details of an existing project.
- Delete Project: Remove a project from the list.
- Filter Projects: View all projects, only completed projects, or only ongoing projects.

# Components

- Navbar: The navigation bar at the top of the application.
- FilterNav: A component that allows users to filter projects based on their status (all, completed, ongoing).
S- ingleProject: Displays individual project information and allows for completion toggling and deletion.
- AddProject: A form to add new projects.
- EditProject: A form to edit an existing project.
- HomeView: Displays a list of all projects with filtering options.

# Project Setup

Prerequisites:
- Node.js (version 12 or later)
- npm (comes with Node.js)
- Vue CLI (optional, if you want to use Vue CLI features)

# Installation

1. Clone the repository:
   
```
git clone https://github.com/your-username/project-planner.git
cd project-planner
```
   
2. Install dependencies:

```
npm install
```
   
3. Start the JSON server:

   This project uses JSON Server to simulate a backend for storing projects. Install it globally using npm:

   ```
   npm install -g json-server
   ```

   Run the JSON server:

   ```
   json-server --watch db.json
   ```

   This will start the server on http://localhost:3000 and use the db.json file in the root directory for storing projects.

4. Run the application:
   Start the Vue.js application by running:
   
   ![33](https://github.com/user-attachments/assets/e518c66e-e318-48c3-8836-4518d1e2d207)
   
   The app will be available at http://localhost:8080.

# JSON Server

This project uses db.json to simulate a backend. It serves as the database for storing project information. When running the JSON server, the data will be available at http://localhost:3000/projects.

# Technologies Used

- Vue.js 3: JavaScript framework for building user interfaces.
- JSON Server: Simple mock server to simulate a backend API.
- HTML5 & CSS3: For structuring and styling the app.

