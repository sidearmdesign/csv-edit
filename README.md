# CSV Viewer/Editor

A modern, feature-rich CSV editor that runs entirely in your browser. No installation required, no server needed - just open the HTML file and start editing.

## Features

### 📁 File Operations
- **Drag & Drop** - Simply drag a CSV file anywhere on the page to load it automatically
- **File Upload** - Traditional file picker with visual feedback
- **Paste Data** - Copy and paste CSV data directly into the editor
- **Export** - Download your edited data as a CSV file

### ✏️ Editing
- **Inline Cell Editing** - Click any cell to edit its contents
- **Add/Delete Rows** - Insert new rows or remove existing ones
- **Add/Delete Columns** - Create new columns with custom names or delete unwanted ones
- **Undo/Redo** - Full history with 50-step undo/redo support (Ctrl/Cmd+Z, Ctrl/Cmd+Shift+Z)

### ⌨️ Keyboard Navigation
- **Arrow Keys** (↑↓←→) - Navigate between cells
- **Enter** - Start editing the selected cell
- **Tab/Shift+Tab** - Move to next/previous cell
- **Ctrl/Cmd+Z** - Undo
- **Ctrl/Cmd+Shift+Z** - Redo

### 🎯 View Controls
- **Column Sorting** - Click column headers to sort data (ascending/descending)
- **Collapse Rows/Columns** - Temporarily hide rows or columns to focus on specific data
- **Show All** - Expand all collapsed items at once
- **Sticky Headers** - Column headers stay visible when scrolling

### 🖱️ Navigation
- **Pan Mode** - Middle-click + drag or Space + drag to pan around large datasets
- **Horizontal Scroll** - Shift + scroll wheel for horizontal scrolling
- **Visual Selection** - See which cell is currently selected with blue highlight

### 🎨 Interface
- **Light/Dark Mode** - Toggle between themes with persistent preference
- **Organized Toolbar** - Buttons grouped by function (File, Edit, View)
- **Hover-to-Show Buttons** - Column actions appear on hover for a clean interface
- **Responsive Design** - Adapts to different screen sizes

## How to Use

### Getting Started

1. **Open the Editor**
   - Simply open `csv-editor.html` in any modern web browser
   - No installation or dependencies required

2. **Load Your Data**
   - **Drag & Drop**: Drag a CSV file from your desktop onto the browser window
   - **File Picker**: Click "Choose File" and select a CSV file
   - **Paste**: Click "Paste" and paste your CSV data, then click "Load Pasted Data"

3. **Edit Your Data**
   - Click any cell to edit its contents
   - Use keyboard navigation for faster editing
   - Add or delete rows and columns as needed

4. **Export Your Changes**
   - Click "Export" to download the edited CSV file
   - File will be saved as `edited-data.csv`

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Arrow Keys | Navigate between cells |
| Enter | Edit selected cell |
| Tab | Move to next cell |
| Shift+Tab | Move to previous cell |
| Ctrl/Cmd+Z | Undo last change |
| Ctrl/Cmd+Shift+Z | Redo |
| Space + Drag | Pan around the table |
| Shift + Scroll | Horizontal scrolling |

### Tips & Tricks

- **Hover over column headers** to see collapse and delete buttons
- **Click column headers** to sort data by that column
- **Collapse rows/columns** you don't need to see temporarily
- **Use "Show All"** to quickly expand everything
- **The Actions column** shows collapse and delete buttons for each row
- **All changes are tracked** - use Undo/Redo freely

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

Requires JavaScript to be enabled.

## Technical Details

- **Pure Vanilla JavaScript** - No frameworks or dependencies
- **Single HTML File** - Entire application in one portable file
- **Client-Side Only** - All processing happens in your browser
- **Local Storage** - Dark mode preference is saved locally
- **CSV RFC 4180 Compliant** - Properly handles quotes, commas, and newlines

## File Structure

```
csv-edit/
├── csv-editor.html       # Main application (open this in your browser)
├── test-data.csv         # Sample data for testing
├── IMPROVEMENTS.md       # Future enhancement ideas
└── README.md            # This file
```

## Privacy & Security

- **100% Client-Side** - Your data never leaves your computer
- **No Server** - No data is uploaded or stored anywhere
- **No Tracking** - No analytics or telemetry
- **Open Source** - All code is visible and auditable

## Future Improvements

See `IMPROVEMENTS.md` for a comprehensive list of planned features and enhancements.

## License

Free to use and modify for any purpose.

## Support

For issues or questions, please refer to the code comments or create an issue in the repository.

---

**Enjoy editing your CSV files!** 🎉
