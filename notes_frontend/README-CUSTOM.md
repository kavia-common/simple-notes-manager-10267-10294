# Simple Notes Frontend (Svelte)

A minimalistic notes app with:
- Create note
- Edit note
- Delete note
- View notes
- Simple search

Tech: SvelteKit, Vite, localStorage persistence.

## Running

- npm install
- npm run dev
- Open http://localhost:3000

## Structure

- src/lib/stores/notes.ts — Store with localStorage persistence and CRUD helpers
- src/lib/components/Header.svelte — App header with search input
- src/lib/components/Sidebar.svelte — Notes list and "New Note" button
- src/lib/components/Editor.svelte — Editor for viewing/updating/deleting the selected note

## Data

Notes are stored in the browser's localStorage. No backend required.

If you later connect to a database or an API, replace the store implementation with API calls and keep the UI intact.
