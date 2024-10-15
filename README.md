# Kanban Board Application

This project is a React-based Kanban board that allows users to organize tasks dynamically using data fetched from the provided API. Users can group and sort tasks based on their preferences. The Kanban board is designed to be user-friendly and responsive.

## Features

- **Dynamic Grouping**: Users can group tasks by **Status**, **User**, or **Priority**.
- **Sorting Options**: Sort tasks by **Priority** (descending order) or **Title** (ascending order).
- **Persistent State**: The application remembers the user's last grouping and sorting preferences, even after a page refresh.
- **Priority Levels**: Each task is assigned a priority ranging from "No Priority" to "Urgent."

## API Details

The Kanban board interacts with the following API:

- **Endpoint**: `https://api.quicksell.co/v1/internal/frontend-assignment`
- **Response Structure**: The API provides a list of tickets with fields such as `id`, `title`, `status`, `assignedUser`, and `priority`.

### Priority Levels

The application interprets priority values as follows:

- `4` - Urgent
- `3` - High
- `2` - Medium
- `1` - Low
- `0` - No Priority

## Getting Started

### Prerequisites

Make sure you have the following installed:

- **Node.js** (v12 or higher) and **npm**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/kanban-board.git
   cd kanban-board

## Install the project dependencies:
npm install

## Run the development server

npm start

### Access the application:
Open http://localhost:3000 in your browser.

## Project Structure
.
├── public
├── src
│   ├── components
│   │   ├── dropdown.jsx
│   │   ├── priority.jsx
│   │   ├── priority.css
│   │   ├── status.jsx
│   │   ├── status.css
│   │   ├── user.jsx
│   │   ├── user.css
│   ├── icons_FEtask
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

### Key Directories and Files

components/: Contains React components used in the app.
dropdown.jsx: Component for grouping and sorting options.
priority.jsx, status.jsx, user.jsx: Components for displaying tasks grouped by priority, status, and user respectively.
CSS files: Stylesheets for the components.
icons_FEtask/: Icons used in the app.
App.js: Main component that manages state and renders child components.
index.js: Entry point for the React app.
App.css, index.css: Global styles for the app.

### Technologies Used

React JS: Core library for building the app.
Ant Design: UI component library for styling.
Axios: For making HTTP requests to the API.
CSS: For custom styles.