# Contactly - Contact Management System

A responsive Week 2 assignment project built with HTML, CSS and vanilla JavaScript.

## Features
- Complete CRUD: create, view, edit and delete contacts
- Name required; email and phone format validation
- Live search across name, email, phone, company, job title and group
- Group filtering: Work, Personal, Family, Other
- Sorting: name A-Z, name Z-A, recently added, company
- Favorites view and favorite toggle
- Generated initials avatars with deterministic colors
- JSON import and JSON export
- Browser localStorage persistence
- Light/dark theme toggle
- Responsive desktop, tablet and mobile layout
- Empty states, delete confirmation, toast messages
- Ctrl/Cmd + K focuses search; Escape closes the dialog

## Structure
```text
contact-management-system/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── README.md
```

## Run
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or use VS Code Live Server.
4. The app starts with four sample contacts.

No npm install, build process, API key or database is required.

## Data
Contacts are stored in the browser's localStorage. They do not sync between devices or upload to a server. Export JSON before clearing browser data.

Import accepts a JSON array or an object containing a `contacts` array. Import replaces the current list after confirmation, so export a backup first.

## Limitations
This is a frontend-only learning project. It does not provide server-side authentication, cloud sync or a production database. Browser localStorage is not suitable for storing sensitive real customer information. The app uses no external icon/font library, so its core UI works offline.

## Submission checklist
- Add, edit, delete and favorite contacts
- Test search by name, email, phone and company
- Test every group filter and sort option
- Export JSON, reload, then import the backup
- Test mobile layout
- Be ready to explain CRUD, arrays/objects, localStorage and JSON import/export
