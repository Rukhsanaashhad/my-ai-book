# Data Model: AI-Driven Development Book

This document outlines the data model for the book. Since the book's content is stored in Markdown files, this model describes the conceptual structure of the content.

## Entities

### Book

The top-level entity that represents the entire book.

**Attributes**:

- `title`: The title of the book.
- `author`: The author of the book.

### Chapter

A chapter is a collection of pages.

**Attributes**:

- `title`: The title of the chapter.
- `pages`: An ordered list of pages within the chapter.

### Page

A page is a single document of content.

**Attributes**:

- `title`: The title of the page.
- `content`: The content of the page in Markdown format.

## Relationships

- A `Book` has one or more `Chapters`.
- A `Chapter` has one or more `Pages`.

## State Transitions

Not applicable for this project, as the content is static.
