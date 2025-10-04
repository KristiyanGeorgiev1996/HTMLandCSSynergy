# HTML and CSS: Tags and Selectors – Front-End Test Automation 🧑💻

This file contains tasks from the **HTML and CSS: Tags and Selectors** section of the _Front-End Test Automation_ course at SoftUni. Each task demonstrates the use of fundamental HTML tags and CSS selectors to create web pages with different structures and functionality.

---

## 🔧 Tasks Overview

### 📝 Task 1: First HTML Page
**Task Description:**  
Create an HTML page with a valid structure including `<html>`, `<head>`, and `<body>`. The page should contain a paragraph of text, with part of the text highlighted using a semantic tag, such as `<strong>`.

**Requirements:**
- Valid HTML5 document (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
- `<head>` should include an appropriate `<title>`.  
- `<body>` must include at least one paragraph (`<p>`) with text.  
- Use a semantic tag (`<strong>` or similar) to emphasize part of the text.

---

### 📝 Task 2: ToDo List
**Task Description:**  
Create an HTML page that displays a list of tasks to do and completed tasks. The page should use an ordered or unordered list (`<ol>` or `<ul>`) to present items and visually distinguish between active and completed tasks using CSS.

**Requirements:**
- Valid HTML5 document with all standard tags.  
- `<head>` should include a `<title>` and link to an external CSS file.  
- `<body>` should include:
  - A list heading (`<h1>` or `<h2>`).  
  - A list of active tasks (`<ol>` or `<ul>`).  
  - A list of completed tasks visually distinct via CSS.  
- On hover, list items should change background color and display a line-through (`text-decoration: line-through`).  
- CSS should differentiate active tasks from completed tasks (`.done`), with completed tasks crossed out by default.

---

### 📝 Task 3: Navigation Bar
**Task Description:**  
Create an HTML page with a navigation bar containing links to main sections of the website. Navigation should be structured using a list and use appropriate semantic HTML tags. CSS styling should ensure readability and basic layout.

**Requirements:**
- Valid HTML5 document with standard tags.  
- `<head>` must include a `<title>` and link to an external CSS file.  
- Use a semantic `<nav>` tag for the navigation wrapper.  
- Inside `<nav>`, include an unordered list (`<ul>`) containing links (`<a>`) to different sections.  
- CSS should define font styles and basic spacing for the page body.

---

### 📝 Task 4: Blog Posts
**Task Description:**  
Create an HTML page that displays a list of blog posts. Each post should include a title, publication date, author, and a brief content summary. Use semantic HTML tags such as `<article>`, `<header>`, `<h2>`, `<time>`, and `<p>`.

**Requirements:**
- Valid HTML5 document with standard tags.  
- `<head>` must include a `<title>` and link to an external CSS file.  
- Each blog post should be wrapped in an `<article>` containing:
  - A title (`<h2>`).  
  - Publication date (`<time>`) and author (`<span>` or appropriate element).  
  - Brief content in a `<p>` tag.  
- CSS should ensure:
  - Readable text.  
  - Bold styling for the author.  
  - Italic styling for the date.  
  - Minimal spacing for titles and content.

---

### 📝 Task 5: Single Blog Post with Comments
**Task Description:**  
Create an HTML page that displays a single blog post with main content and a comments section. Use semantic HTML tags such as `<header>`, `<main>`, `<section>`, and `<article>` to structure the content properly.

**Requirements:**
- Valid HTML5 document with all standard tags.  
- `<head>` must include a `<title>` and link to an external CSS file.  
- Main content should include:
  - Blog post title (`<h1>`) with author and publication date.  
  - Main text of the post in `<main>` or suitable container.  
- Comments section (`<section class="comments">`) should include:
  - Individual comments, each within an `<article>`.  
  - Author and date in `<header>` of each comment.  
  - Comment text in `<p>`.  
- CSS should ensure:
  - Readable font and background color.  
  - Styling for headings, authors, and dates.  
  - Visual separation of comments using background, spacing, rounded corners, and light shadow (`box-shadow`).
