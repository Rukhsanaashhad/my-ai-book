# Quickstart: Adding Content

This guide explains how to add new chapters and pages to the book.

## Adding a New Chapter

1.  Create a new directory in the `docs` directory. The name of the directory will be the URL slug for the chapter.
    ```bash
    mkdir docs/new-chapter
    ```
2.  Add a `_category_.json` file to the new directory to configure the chapter's title in the sidebar.
    ```json
    {
      "label": "New Chapter Title",
      "position": 3
    }
    ```
3.  Add new pages to the chapter directory.

## Adding a New Page

1.  Create a new Markdown file (`.md` or `.mdx`) in the appropriate chapter directory.
2.  The filename will be the URL slug for the page.
3.  Add content to the file using Markdown.
4.  The page title will be automatically inferred from the first `h1` heading in the file. You can also set it explicitly using frontmatter:
    ```markdown
    ---
    title: My New Page
    ---

    # Page Content
    ```
5.  Update the `sidebars.js` file to include the new page in the navigation.
