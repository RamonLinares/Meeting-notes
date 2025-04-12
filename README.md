# Meeting Notes

A modern, lightweight web application for managing meeting notes and action items. Built with vanilla JavaScript and HTML, this application provides a clean and intuitive interface for taking notes, tracking action items, and organizing your meeting information.

## Features

- **Rich Text Editing**: Create and edit notes with rich text formatting using the Trix editor
- **Action Items Tracking**: Create and manage action items with checkboxes to track completion
- **Note Organization**: 
  - Pin important notes to keep them at the top
  - Search through all notes and action items
  - Sort notes by creation date
- **Data Management**:
  - Automatic saving to local storage
  - Import/Export functionality via XML
  - Draft saving for unsaved notes
- **Responsive Design**: Works well on both desktop and mobile devices
- **Modern UI**: Clean, intuitive interface with smooth animations and transitions

## Usage

1. **Creating a Note**:
   - Click the "+" button in the bottom right corner
   - Enter a title (optional)
   - Add rich text content using the editor
   - Add action items (one per line)
   - Set a deadline (optional)
   - Click "Save Note"

2. **Managing Notes**:
   - Pin/unpin notes using the pin icon
   - Edit notes by clicking the edit icon
   - Delete notes using the delete icon
   - Search through notes using the search bar
   - Mark action items as complete using checkboxes

3. **Data Management**:
   - Export all notes to XML using the menu (three dots)
   - Import notes from XML using the menu
   - All changes are automatically saved to local storage

## Technical Details

- Built with vanilla JavaScript and HTML
- Uses Trix editor for rich text editing
- No external dependencies except for Trix editor
- Responsive design using CSS Grid and Flexbox
- Local storage for data persistence
- XML-based import/export functionality

## Browser Compatibility

The application works in all modern browsers that support:
- Local Storage
- ES6 JavaScript features
- CSS Grid and Flexbox

## License

This project is open source and available under the MIT License. 