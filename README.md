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
. ├── public/ # Public directory for static files ├── src/ # Source directory for the application │ ├── components/ # Contains React components │ │ ├── dropdown.jsx # Component for grouping and sorting options │ │ ├── priority.jsx # Component for displaying tasks by priority │ │ ├── priority.css # Styles for priority component │ │ ├── status.jsx # Component for displaying tasks by status │ │ ├── status.css # Styles for status component │ │ ├── user.jsx # Component for displaying tasks by user │ │ ├── user.css # Styles for user component │ ├── icons_FEtask/ # Icons used in the application │ ├── App.css # Global styles for the application │ ├── App.js # Main component managing state │ ├── index.css # Styles for the entry point │ ├── index.js # Entry point for the React app │ ├── logo.svg # Logo for the application ├── .gitignore # Git ignore file ├── package.json # Project dependencies and scripts ├── package-lock.json # Locked versions of dependencies └── README.md # Project documentation

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

### Demo

<img width="941" alt="image" src="https://github.com/user-attachments/assets/336af3f9-7e04-423f-9dd8-5bc71bda3186">


<img width="953" alt="image" src="https://github.com/user-attachments/assets/20070f55-8c82-4400-94e6-69c2ce57c845">

<img width="945" alt="image" src="https://github.com/user-attachments/assets/74ef3ed5-6e16-4eb7-97d6-0b250520a265">

<img width="940" alt="image" src="https://github.com/user-attachments/assets/a74a114a-189a-467b-8110-2fe800de7bc2">




