# Box Model Containers and Flexbox – Front-End Test Automation 🧑💻

This folder contains tasks from the **Box Model Containers and Flexbox** section of the _Front-End Test Automation_ course at SoftUni. Below are the tasks with professional descriptions.

## 🔧 Tasks Overview


### 📝 Task 1: [Box Model Visualised]  
**Problem Statement:**  
Create an HTML page that **visualises the CSS box model** using nested containers, showing the different layers: **margin**, **border**, **padding**, and **content**. The page should demonstrate how these layers interact and use colors and text for clear visual separation.  

**Requirements:**  

- Valid HTML5 document with all standard tags (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
- `<head>` should contain a `<title>` and a link to an external CSS file.  
- `<body>` should include:
  - Page title (`<h1>`).  
  - Nested `<div>` elements representing the box model layers:
    - `.margin` – shows the outer margin.  
    - `.border` – shows the border around the content.  
    - `.padding` – shows the inner padding.  
    - `.content` – the actual content of the element.  
- CSS should provide:
  - Different background colors for each layer for easy visualisation.  
  - Alignment and spacing via `padding` and `margin`.  
  - Clear text labels for each layer.  
  - Demonstration of how margin, border, padding, and content affect element size and layout.  

**Goal:**  
To visualise and understand the CSS box model and how different layers of an element influence its overall size and page layout.

---

### 📝 Task 2: [Layout Centered Container]  
**Problem Statement:**  
Create an HTML page that demonstrates a **centered container layout** with nested blocks using CSS Flexbox. The page should show how containers can be horizontally and vertically aligned in the viewport, containing structured sections (header, main, footer).  

**Requirements:**  

- Valid HTML5 document with all standard tags (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
- `<head>` should contain a `<title>` and a link to an external CSS file.  
- `<body>` should include:
  - Outer container `.green-container` for visual framing.  
  - Inner container `.blue-box` for arranging the blocks.  
  - Inner elements `.black-box` labeled as Header, Main, and Footer.  
- CSS should provide:
  - Centering of the outer container in the viewport (`display: flex`, `justify-content: center`, `align-items: center`).  
  - Different background colors for visual distinction of containers.  
  - Column layout for the inner blocks with spacing between them (`flex-direction: column`, `gap`).  
  - Centered text inside each block (`justify-content: center`, `align-items: center`).  
  - Clear visual hierarchy for header – main – footer structure.  

**Goal:**  
To visualise a centered container layout with nested blocks and understand how Flexbox facilitates alignment and arrangement of elements in columns and rows.
