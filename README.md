# Note App

A simple and interactive web application for creating, editing, and managing notes. The app allows users to create notes, edit them in real-time, and delete them when no longer needed. All notes are saved in the browser's local storage, ensuring they persist even after the page is refreshed.

## Features

- **Create Notes**: Add new notes with a single click.
- **Edit Notes**: Edit notes in real-time with a `contenteditable` interface.
- **Delete Notes**: Remove notes by clicking the delete icon.
- **Persistent Storage**: Notes are saved in the browser's local storage and persist across page reloads.
- **Line Breaks**: Pressing `Enter` inserts a line break instead of creating a new paragraph for better formatting.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling and layout.
- **JavaScript**: Logic for creating, editing, deleting, and saving notes.

## How to Use

1. **Create a Note**:
   - Click the "Create Note" button to add a new note.
   - Start typing to add content to the note.

2. **Edit a Note**:
   - Click on any note and edit the text directly.

3. **Delete a Note**:
   - Click the delete icon (🗑️) in the bottom-right corner of the note to remove it.

4. **Save Notes**:
   - Notes are automatically saved to local storage as you type or delete them.

### `index.html`
- Contains the structure of the app, including the notes container and the "Create Note" button.

### `style.css`
- Defines the styling for the app, including the layout, colors, and responsive design.

### `index.js`
- Handles the logic for:
  - Creating new notes.
  - Deleting notes.
  - Saving notes to local storage.
  - Real-time updates for note editing.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nimasaghi-dev/note-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd note-app
   ```
3. Open `index.html` in your browser to run the app.

## Future Improvements

- Add support for categorizing notes (e.g., work, personal).
- Implement a dark mode toggle.
- Allow users to customize note colors.
- Add a search functionality to filter notes.

---

Enjoy taking notes with this simple and efficient app! 🚀
