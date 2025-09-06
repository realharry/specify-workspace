# Tasks: Photo Organization Application

**Input**: Design documents from `/specs/001-build-an-application/`

## Phase 3.1: Setup
- [ ] T001 Create project structure: `src/` and `tests/` directories.
- [ ] T002 Initialize a Vite project with vanilla JavaScript.
- [ ] T003 Install `sqlite3` and `vitest` dependencies.
- [ ] T004 Configure `vitest` for the project.

## Phase 3.2: Database and Models
- [ ] T005 [P] Create the database schema in `src/database/schema.sql`.
- [ ] T006 [P] Implement the database connection module in `src/database/connection.js`.
- [ ] T007 [P] Create the `Album` data model in `src/models/album.js`.
- [ ] T008 [P] Create the `Photo` data model in `src/models/photo.js`.

## Phase 3.3: Services and Tests (TDD)
- [ ] T009 [P] Write failing tests for `AlbumService` in `tests/services/album.test.js`.
- [ ] T010 [P] Write failing tests for `PhotoService` in `tests/services/photo.test.js`.
- [ ] T011 Implement `AlbumService` in `src/services/album.js` to make the tests pass.
- [ ] T012 Implement `PhotoService` in `src/services/photo.js` to make the tests pass.

## Phase 3.4: UI Implementation
- [ ] T013 [P] Create the main application layout in `index.html` and `src/main.js`.
- [ ] T014 [P] Implement the "New Album" button functionality.
- [ ] T015 [P] Implement the album list view.
- [ ] T016 [P] Implement the drag-and-drop functionality for re-organizing albums.
- [ ] T017 [P] Implement the album view with a tile-like interface for photos.
- [ ] T018 [P] Implement the "Add Photos" button functionality.

## Phase 3.5: Polish
- [ ] T019 [P] Write unit tests for UI components.
- [ ] T020 [P] Write integration tests for the application.
- [ ] T021 [P] Style the application using CSS to match the desired look and feel.
- [ ] T022 [P] Add documentation to the code.

## Dependencies
- T001, T002, T003, T004 must be completed before all other tasks.
- T005, T006, T007, T008 can be done in parallel.
- T009 and T010 must be completed before T011 and T012.
- T011 and T012 must be completed before UI implementation.

## Parallel Example
```
# Launch T005-T008 together:
Task: "Create the database schema in src/database/schema.sql"
Task: "Implement the database connection module in src/database/connection.js"
Task: "Create the Album data model in src/models/album.js"
Task: "Create the Photo data model in src/models/photo.js"
```
