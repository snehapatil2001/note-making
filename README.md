# Note Making Project

This project is a simple note-making application built using React for learning purpose using HTML, CSS, Bootstrap, JavaScript, TypeScript. It allows users to create, edit, and delete notes with tags for organization.

## Features

- Create new notes with titles, content, and tags.
- Edit existing notes.
- Delete notes.
- Organize notes using tags.
- Responsive design for various screen sizes.

## Project Structure

The project structure is organized as follows:

- **src/**
  - **useLocalStorage.tsx:** Custom React hook for managing state in local storage.
  - **NoteList.tsx:** Component for displaying a list of notes with filtering and tag editing functionalities.
  - **NoteListModule.css:** CSS module for styling the NoteList component.
  - **NoteLayout.tsx:** Component for layout management, including displaying individual notes.
  - **NoteForm.tsx:** Form component for creating and editing notes.
  - **NewNote.tsx:** Component for creating a new note.
  - **Main.tsx:** Main entry point of the application.
  - **EditNote.tsx:** Component for editing existing notes.
  - **App.tsx:** Main application component managing routes and state.

## Getting Started

To run the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm:

   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Dependencies

To run the project locally, follow these steps:

- **React**: A JavaScript library for building user interfaces.
- **React Router DOM**: Declarative routing for React applications.
- **React Bootstrap**: Bootstrap components built with React.
- **React Markdown**: Markdown component for React.
- **React Select**: Customizable select component for React.
- **UUID**: Library for generating unique identifiers.

## Scripts

- dev: Starts the development server.
- build: Builds the project for production.
- lint: Lints the project code.
- preview: Previews the production build locally.
