# CSV Editor - Future Improvements

This document outlines potential enhancements for the CSV Editor project. These ideas are organized by category and can be implemented incrementally to improve functionality and user experience.

---

## Data Manipulation

1. **Add/Delete Rows & Columns** - Currently you can only collapse; being able to insert and remove would be powerful
2. **Undo/Redo System** - Track changes and allow reverting edits
3. **Copy/Paste Multiple Cells** - Select and copy ranges of cells at once
4. **Column Reordering** - Drag and drop to rearrange columns
5. **Search & Replace** - Find values across the dataset and replace them
6. **Duplicate Detection** - Highlight or remove duplicate rows

## Data Analysis

7. **Column Statistics Panel** - Show sum, average, min, max, count for selected columns
8. **Data Type Detection** - Auto-detect and format dates, numbers, currency
9. **Filtering** - Filter rows based on column values (like Excel filters)
10. **Formula Support** - Simple calculations between cells
11. **Data Validation** - Set rules for what can be entered in cells

## User Experience

12. **Keyboard Navigation** - Arrow keys to move between cells, Enter to edit, Tab to next cell
13. **Column Resizing** - Drag column borders to adjust width
14. **Freeze Header Row** - Keep headers visible while scrolling
15. **Multi-cell Selection** - Click and drag to select ranges
16. **Right-click Context Menu** - Quick access to common actions
17. **Auto-save to LocalStorage** - Prevent data loss on accidental close

## Import/Export

18. **Auto-detect CSV Delimiter** - Handle TSV (tabs), semicolons, pipes, etc.
19. **Export to Other Formats** - JSON, Excel-compatible TSV, SQL INSERT statements
20. **Import from Clipboard** - Detect CSV in clipboard and load directly

## Performance & Scalability

21. **Virtual Scrolling** - Render only visible rows for large datasets (10,000+ rows)
22. **Progressive Loading** - Load large files in chunks
23. **Web Worker Parsing** - Parse CSV in background thread for better responsiveness

## Polish

24. **Accessibility Improvements** - ARIA labels, better screen reader support, keyboard-only operation
25. **Column Type Icons** - Visual indicators for detected data types
26. **Better Mobile Support** - Touch-friendly controls and responsive layout
27. **Customizable Themes** - More color schemes beyond light/dark

---

## Implementation Status

Track implemented features by moving them from "Planned" to "Completed":

### Planned
- All 27 items listed above

### In Progress
- None

### Completed
- None

---

## Priority Recommendations

Consider implementing these high-impact features first:

1. **Keyboard Navigation** (#12) - Significantly improves usability for power users
2. **Add/Delete Rows & Columns** (#1) - Essential data manipulation capability
3. **Undo/Redo System** (#2) - Safety net for users making edits
4. **Auto-save to LocalStorage** (#17) - Prevents data loss
5. **Column Resizing** (#13) - Common user expectation for table interfaces

---

*Last Updated: 2025-11-18*
