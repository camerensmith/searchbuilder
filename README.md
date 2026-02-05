# Search Builder

Quick Boolean query builder for sourcing roles. The page is fully client-side, so you can run it locally or from a browser.

## Features

- 🔍 **Boolean Query Builder** - Generate complex Boolean search queries for job searches
- 💾 **Save & Load Queries** - Save frequently used queries and load them anytime
- 📤 **Export/Import** - Backup and restore your saved queries as JSON files
- 🔖 **Bookmarks** - Quick access to favorite job board URLs with favicon support
- ⌨️ **Keyboard Shortcuts** - Speed up your workflow with keyboard shortcuts
- 🎯 **Live Preview** - See your query update in real-time with optimized debouncing
- 📊 **Character Counter** - Track query length with warnings for Google's limits
- 🎨 **Modern UI** - Clean, responsive design that works on all devices

## Keyboard Shortcuts

- `Ctrl/Cmd + Enter` - Run search immediately
- `Ctrl/Cmd + K` - Focus on job titles field
- `Ctrl/Cmd + S` - Save current query (when name is filled)

## Usage

1. Fill in job titles, keywords, and other search criteria
2. The Boolean query updates automatically in real-time
3. Click "Search" to open Google/Bing with your query
4. Save commonly used queries for quick access later
5. Export your queries for backup or sharing

## Recent Improvements

- ✅ Added debouncing (300ms) for better performance with live preview
- ✅ Added keyboard shortcuts for common actions
- ✅ Enhanced copy button with visual feedback
- ✅ Added export/import functionality for saved queries
- ✅ Added delete buttons for bookmarks
- ✅ Improved error handling with try-catch blocks
- ✅ Added confirmation dialogs for destructive actions
- ✅ Added JSDoc comments for better code maintainability
- ✅ Extracted configuration into constants
- ✅ Added helpful tips section with keyboard shortcuts