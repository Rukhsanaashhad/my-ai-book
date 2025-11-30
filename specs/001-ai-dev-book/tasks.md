# Tasks: AI-Driven Development Book

**Input**: Design documents from `specs/001-ai-dev-book/`

## Phase 1: Setup

- [ ] T001 Initialize a new Docusaurus project
- [ ] T002 Configure `docusaurus.config.js` with the book title, author, and other metadata
- [ ] T003 [P] Create the initial directory structure for the book content (`docs/`)

## Phase 2: Foundational (Blocking Prerequisites)

- [ ] T004 Create the introduction page at `docs/intro.md`
- [ ] T005 Create the first chapter directory at `docs/chapter1`
- [ ] T006 [P] Create the first two pages of the first chapter at `docs/chapter1/page1.md` and `docs/chapter1/page2.md`

## Phase 3: User Story 1 - Browse Book Content

- [ ] T007 [US1] Add content to the introduction page at `docs/intro.md`
- [ ] T008 [US1] [P] Add content to the first page of the first chapter at `docs/chapter1/page1.md`
- [ ] T009 [US1] [P] Add content to the second page of the first chapter at `docs/chapter1/page2.md`

## Phase 4: User Story 2 - Navigate with Table of Contents

- [ ] T010 [US2] Create `sidebars.js` to define the navigation and table of contents
- [ ] T011 [US2] Verify that the table of contents is visible and that links to pages are working correctly

## Phase 5: User Story 3 - Navigate Between Pages

- [ ] T012 [US3] Verify that "Next" and "Previous" buttons are present on pages and are working correctly. (Docusaurus handles this automatically)

## Phase 6: User Story 4 - Export Content to Markdown

- [ ] T013 [US4] Create a script to copy all files from the `docs` directory into a new `export` directory.

## Phase N: Polish & Cross-Cutting Concerns

- [ ] T014 [P] Add custom styling to `src/css/custom.css`
- [ ] T015 Run a final build of the Docusaurus site to ensure there are no errors

## Dependencies & Execution Order

- **Setup (Phase 1)** must be completed before any other phase.
- **Foundational (Phase 2)** depends on Setup and blocks all other phases.
- **User Story phases (3-6)** can be worked on in parallel after the Foundational phase is complete.
- **Polish (Phase N)** should be done last.
