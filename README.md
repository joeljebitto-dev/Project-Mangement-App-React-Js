# Project Management App - React JS

A simple project management application built with React, Vite, and Tailwind CSS. The app lets users create projects, add descriptions and due dates, view projects from a sidebar, and manage project-specific tasks.

## Features

* Create new projects
* Add project title, description, and due date
* View all projects in a sidebar
* Select a project to view its details
* Delete projects
* Add tasks to a selected project
* Remove tasks from a project
* Component-based React structure
* Tailwind CSS styling
* Vite development workflow

## Tech Stack

* React
* Vite
* Tailwind CSS
* JavaScript
* ESLint

## Project Structure

```text
Project-Mangement-App-React-Js/
├── src/
│   ├── MainSection/
│   │   ├── Default.jsx
│   │   ├── Project.jsx
│   │   └── ProjectCreate.jsx
│   ├── Sections/
│   │   ├── MainSection.jsx
│   │   └── NavBar.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── package.json
└── README.md
```

## How It Works

The app stores project data in React state. Each project contains:

```js
{
  title: string,
  description: string,
  dueDate: string,
  todo: string[]
}
```

Main flow:

```text
Create Project
  ↓
Add title, description, and due date
  ↓
Select project from sidebar
  ↓
View project details
  ↓
Add or remove project tasks
```

## Installation

Clone the repository:

```bash
git clone https://github.com/joeljebitto-dev/Project-Mangement-App-React-Js.git
cd Project-Mangement-App-React-Js
```

Install dependencies:

```bash
npm install
```

Or with pnpm:

```bash
pnpm install
```

## Running the App

Start the development server:

```bash
npm run dev
```

Or with pnpm:

```bash
pnpm dev
```

Then open the local URL shown in the terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

```bash
npm run dev
npm run build
npm run lint
npm run preview
```

Or with pnpm:

```bash
pnpm dev
pnpm build
pnpm lint
pnpm preview
```

## Build for Production

```bash
npm run build
```

The production build will be generated in the `dist/` directory.

## Notes

* This is a frontend-only project.
* Project and task data are stored in React state.
* Data is not persisted after page refresh.
* The repository name currently uses `Mangement`; consider renaming it to `Project-Management-App-React-Js` for spelling consistency.

## Future Improvements

* Add localStorage persistence
* Add project editing
* Add task completion status
* Add task filtering
* Add drag-and-drop task ordering
* Add search for projects
* Add form validation
* Add responsive mobile layout
* Add unit tests
* Refactor state updates to avoid direct mutation
* Add TypeScript for stronger data modeling

## Author

Built by [Joel Jebitto](https://github.com/joeljebitto-dev).
