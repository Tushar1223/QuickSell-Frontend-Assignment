Kanban Board Application
This project is a responsive Kanban board application built with React JS. It fetches data from an API to display tickets that can be grouped and sorted based on specific criteria.

Features
Grouping Options: Organize tickets by status, user, or priority.
Sorting Options: Sort tickets by priority (descending) or title (ascending).
Persistent View State: Saves the user’s grouping and sorting preferences across sessions.
Responsive Design: Optimized layout for both desktop and mobile views.

Project Requirements
Framework: React JS
CSS: Pure CSS and Styled JSX (no external CSS libraries)
Functionality: Matches provided design specifications
API: https://api.quicksell.co/v1/internal/frontend-assignment

Getting Started
To run the project locally:

Install dependencies:
npm install

Run the development server:
npm start

Open http://localhost:3000 in your browser to view the application.

Build for production:
npm run build

This will generate an optimized build in the build folder, ready for deployment.


Project Structure:-

src/
│
├── assets/
│   ├── icons_FEtask/                  # Stores all icons and asset images
│
├── ui-elements/
│   ├── Header/
│   │   ├── header.css                 # Styles for Header component
│   │   └── index.jsx                  # Header component
│   │
│   ├── kanban-board/
│   │   ├── Card/                      # Folder for Card component
│   │   │   ├── card.css               # Styles for Card component
│   │   │   └── index.jsx              # Card component
│   │   │
│   │   ├── Column/                    # Folder for Column component
│   │   │   ├── column.css             # Styles for Column component
│   │   │   └── Column.jsx             # Column component
│   │   │
│   │   ├── controls/                  # Folder for controls like dropdown
│   │   │   └── DisplayDropdown/
│   │   │       ├── displayDropdown.css # Styles for DisplayDropdown component
│   │   │       └── index.jsx          # DisplayDropdown component
│   │   │
│   │   └── Grid/                      # Folder for Grid component
│   │       ├── grid.css               # Styles for Grid component
│   │       └── index.jsx              # Grid component
│   │
│   ├── Loader/
│   │   ├── loader.css                 # Styles for Loader component
│   │   └── index.jsx                  # Loader component
│   │
│   └── UserIcon/
│       ├── usericon.css               # Styles for UserIcon component
│       └── index.jsx                  # UserIcon component
│
├── utilities/                         # Folder for utility functions
│   ├── index.js                       # Main utility export
│   └── util.jsx                       # Utility functions (e.g., icon handling)
│
├── App.css                            # Global app styles
├── App.js                             # Main App component
├── App.test.tsx                       # Tests for the App component
├── constants.js                       # Contains constants such as API endpoints
├── index.css                          # Global styles
└── index.js                           # Entry point for ReactDOM
