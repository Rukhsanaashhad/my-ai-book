---
id: 1
title: Establish Constitution for Docusaurus Book Project
stage: constitution
date_iso: 2025-11-30
surface: agent
model: gemini
feature: none
branch: null
user: hey
command: /sp.constitution I want to build a book/documentation project for Docusaurus. The book should have:
  - Multiple chapters
  - Pages with content
  - Table of contents
  - Navigation
  - Export to Markdown format
labels:
  - "constitution"
  - "docusaurus"
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files_yaml: |
  - .specify/memory/constitution.md
  - .specify/templates/plan-template.md
tests_yaml: |
  - none
---

## PROMPT

/sp.constitution I want to build a book/documentation project for Docusaurus. 
The book should have:
- Multiple chapters
- Pages with content  
- Table of contents
- Navigation
- Export to Markdown format

## RESPONSE

I have updated the project constitution to align with your request for a Docusaurus book project.

- **Version**: 1.0.0
- **Rationale**: Initial version of the constitution.
- **Changes**:
    - Set the project name to "Docusaurus Book Project".
    - Defined 5 core principles: Content First, Clear Navigation, Platform Portability, Docusaurus-Powered, and Spec-Driven Development.
    - Updated the `plan-template.md` to include a constitution check based on the new principles.
- **Suggested Commit Message**: `docs: establish constitution v1.0.0 for Docusaurus book project`
