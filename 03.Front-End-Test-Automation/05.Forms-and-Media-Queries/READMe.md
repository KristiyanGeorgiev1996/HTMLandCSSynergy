# Forms and Media Queries – Front-End Test Automation 🧑💻

This folder contains tasks from the **Forms and Media Queries** section of the _Front-End Test Automation_ course at SoftUni. Below are the tasks with brief descriptions.

## 🔧 Tasks Overview:

### 📝 Task 1: [Responsive Blog Layout with Header, Navigation, Articles, and Sidebar]

**Problem Statement:**  
Create a responsive HTML page that demonstrates a blog-style layout with a header, horizontal navigation, multiple articles, and a sidebar. The page should adapt to different screen sizes, including tablet and mobile views, while maintaining readability and proper alignment of content.

**Requirements:**

- The HTML document must be valid HTML5 with standard tags (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
- Include `<meta>` tags for charset, viewport, and compatibility, a `<title>`, and a link to an external CSS file.  

**Page Structure:**

- **Header (`<header class="mainHeader">`):**
  - Contains a site title (`<p>`) aligned to the left.
  - Contains a navigation menu (`<nav>`) with an unordered list (`<ul>`) of links (`<li>`), displayed horizontally and aligned to the right.

- **Main Content (`<main>`):**
  - Contains three articles (`<article>`), each with a `<header>` and a `<section>`.
  - **Article One:** Includes heading `<h1>`, paragraphs `<p>` and an image `<img>` positioned alongside the text.
  - **Article Two:** Includes heading `<h2>`, paragraphs, a `<div>` with a paragraph and a `<blockquote>` element with author attribution.
  - **Article Three:** Includes heading `<h2>`, paragraphs, and an image positioned alongside the text.

- **Sidebar (`<aside>`):**
  - Contains sections with navigation lists for categories and social links (`<ul>` with `<li><a>`).  

**CSS Requirements:**

- Use Flexbox to align header elements (site title and navigation) with space between.  
- Style headings with a serif font (`Georgia, serif`).  
- Layout articles and sidebar side by side for desktop view using inline-block or flex layout.  
- Apply proper spacing, padding, borders, and box shadows for images and content.  
- Style blockquotes with left border, italic font style, and author alignment.  
- Sidebar links should have distinct color and no text-decoration.  

**Responsive Design:**

- **Tablet view (`max-width: 900px`):**
  - Sidebar and navigation should be hidden.
  - Articles should occupy full width.
  - Images adjusted for smaller margins.

- **Mobile view (`max-width: 600px`):**
  - Images should become static (no absolute positioning).
  - Text should take full width under images.
  - Flex-direction of combined content blocks should adapt to column layout for better readability.  

**Objective:**  
Demonstrate a professional, responsive blog layout that combines semantic HTML5 elements, Flexbox, inline-block, and media queries to create a readable and visually structured page across desktop, tablet, and mobile devices.

---

### 📝 Task 2: [Responsive Login Form with Icons]

**Problem Statement:**  
Create a responsive HTML login form that demonstrates the use of `<form>`, `<fieldset>`, `<legend>`, and input elements with associated icons from Font Awesome. The form should be visually structured, accessible, and adapt to different screen sizes.

**Requirements:**

- The HTML document must be valid HTML5 with standard tags (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
- Include `<meta>` tags for charset, viewport, and compatibility, a `<title>`, and a link to an external CSS file.  
- Include Font Awesome via CDN to use icon fonts for the input fields.

**Form Structure:**

- **Form (`<form>`):**
  - Contains a `<fieldset>` to group form elements.
  - `<legend>` displays the form title ("Login").
  - Two input fields with labels and icons:
    - **Username:** `<label>` with associated `<input type="text">` and a user icon (`<i class="fas fa-user">`).
    - **Password:** `<label>` with associated `<input type="text">` and a key icon (`<i class="fas fa-key">`).
  - A submit button (`<button>`) labeled "Login".

**CSS Requirements:**

- Set a fixed width for the form for desktop view.
- Style `<legend>` with border, padding, and alignment.
- Align `<label>` elements inline with fixed width for proper form layout.
- Style input fields with padding and spacing for readability.
- Position icons (`<i>`) relative to inputs to visually indicate field type.
- Style the submit button with background color, text color, padding, border-radius, and no border.

**Objective:**  
Demonstrate how to create a clean and responsive login form with semantic HTML elements, inline labels, icon integration via Font Awesome, and visually appealing styling, ensuring usability and proper alignment of form elements.


---

### 📝 Task 3: [Responsive Media Card Component]

**Problem Statement:**  
Create a responsive "card" component using HTML and CSS that visually combines an image with a content section containing a title, description, and a call-to-action button. The card should be visually appealing, include hover effects, and adapt to different screen sizes.

**Requirements:**

- The HTML document must include proper structure with `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, charset, viewport meta tags, `<title>`, and linked CSS files.  
- The card structure should include:
  - A `<section>` element with class `card`.
  - Inside the card:
    - A `div.media` containing an `<img>` element for the card image. Ensure proper aspect ratio and responsiveness.
    - A `div.cnt` containing:
      - `<h3>` for the card title.
      - `<p>` for a short description.
      - `<a>` styled as a button for "See more".
      
**CSS Requirements:**

- The card should have:
  - Minimum and maximum width for responsive layout.
  - Rounded corners and box-shadow for a floating effect.
  - Smooth transition for hover effects on shadow.
- The image should:
  - Maintain its aspect ratio.
  - Fill the width of the card without distortion.
  - Be clipped correctly at the top corners with rounded edges.
- Content section (`.cnt`) should have padding and properly aligned text.
- Button should:
  - Float to the right.
  - Have background color, border-radius, padding, and hover effect with darker shade.
- Typography:
  - Use a clean, readable font for headings and paragraphs.
  - Maintain consistent margins and line spacing.
- Responsive behavior:
  - Card adjusts width according to viewport.
  - Maintain readability and layout without horizontal scroll.

**Objective:**  
Demonstrate the ability to combine images and text in a card layout with semantic HTML, CSS styling for visual hierarchy, hover effects, and responsive design.


---

### 📝 Task 4: [Landing Page with Team Section and Newsletter Signup]

**Problem Statement:**  
Create a simple landing page using HTML and CSS that includes a header with navigation, a main section highlighting a service or offer, a team members section, and a newsletter signup form. The page should be visually structured, responsive, and easy to navigate.

**Requirements:**

1. **Header Section:**
   - Include a header with a title (`h2`) and subtitle (`p`).
   - Add a horizontal navigation menu using `<nav>` and `<ul>` with at least 5 links (`Home`, `About`, `Services`, `Blog`, `Contacts`).
   - Use Flexbox to evenly space navigation links.
   
2. **Main Offer Section (`.need-website`):**
   - Include a two-column layout:
     - Left column: `h3` heading, paragraph text, and a call-to-action button.
     - Right column: an image representing the service.
   - Center content horizontally and add padding for spacing.
   
3. **Team Members Section (`.team-members`):**
   - Display multiple team member profiles as `<article>` elements.
   - Each profile includes:
     - Circular image (`border-radius: 50%`).
     - Name (`h4`), role (`p`), and a short description (`p`).
   - Layout should be responsive using Flexbox, wrapping elements as needed.

4. **Newsletter Signup Section (`.newsletter-ctr`):**
   - Include a form with a heading (`h3`), a horizontal rule (`hr`), an email input field, and a submit button.
   - Style the section with a background color and center the form.

5. **Styling Guidelines:**
   - Use Flexbox for horizontal layouts and spacing.
   - Remove default list styles from navigation.
   - Ensure text is readable with proper font sizes and alignment.
   - Add spacing and padding consistently for visual hierarchy.
   - Make the layout responsive: team members wrap on smaller screens and images resize proportionally.

**Objective:**  
Demonstrate the ability to structure a landing page with multiple sections, apply CSS Flexbox for layout, style images and text, and create a responsive, visually appealing design.


---

### 📝 Task 5: [Responsive Table Design]

**Problem Statement:**  
Create a responsive HTML table that displays tabular data in a standard desktop layout and adapts to smaller screens (mobile devices) by transforming into a stacked, readable format.

**Requirements:**

1. **Table Structure:**
   - Use `<table>` with `<thead>` and `<tbody>`.
   - Include at least three columns: `First Name`, `Last Name`, and `Job Title`.
   - Populate the table with multiple rows of sample data.
   - Use `data-*` attributes on `<td>` elements to store the column headers for responsive view.

2. **Styling:**
   - Apply borders to the table and cells.
   - Alternate row colors for readability.
   - Style the header row differently (e.g., dark background, white text).
   - Add hover effect for table rows (background and text color change).

3. **Responsive Behavior:**
   - On screens smaller than 760px:
     - Hide the table header.
     - Display each row as a block.
     - Show column labels using `content: attr(data-*)` pseudo-elements.
     - Each cell should have its label displayed before the value, aligned to the left or right as needed.
   - Maintain readable spacing and alignment in mobile view.

4. **Optional Enhancements:**
   - Adjust font sizes for different screen widths using media queries.
   - Use a subtle background color for the table body and alternate rows.
   - Keep consistent padding for cells.

**Objective:**  
Demonstrate the ability to create a standard HTML table that is visually appealing, accessible, and fully responsive on both desktop and mobile devices.

---

### 📝 Task 6: [Responsive Timeline Layout]

**Problem Statement:**  
Create a vertical timeline to display historical events or milestones in chronological order. The timeline should visually alternate content between the left and right sides and adapt for mobile screens.

**Requirements:**

1. **HTML Structure:**
   - Create a wrapper for the timeline with class `.timeline`.
   - Each event should be inside a container with class `.container` and either `.left` or `.right`.
   - Each container should include:
     - An `<h2>` for the date.
     - A `<p>` for a brief description of the event.

2. **Timeline Design:**
   - A vertical line should run down the center of the timeline.
   - Each event container should have a circle aligned to the timeline line, with alternating positions left and right.
   - Use a different color for circles on the left and right for visual distinction.
   - Content boxes should be slightly padded and have rounded corners.

3. **Responsive Behavior:**
   - On screens smaller than 600px:
     - The timeline line should shift to the left.
     - All containers should become full-width and align to the left.
     - Circles should remain aligned to the timeline line.
     - Ensure content boxes maintain readability with proper padding.

4. **Styling:**
   - Add subtle borders and background colors to containers.
   - Use appropriate spacing, font sizes, and typography for headings and paragraphs.
   - Maintain a clean and visually appealing layout.

**Objective:**  
Demonstrate the ability to create a visually structured and responsive timeline that adapts to different screen sizes while maintaining the alternating left-right layout on desktop and a unified layout on mobile devices.


---

### 📝 Task 7: [Interactive Comment Form]

**Problem Statement:**  
Create a user-friendly comment form that collects basic information and preferences from a user. The form should include text inputs, a textarea, a dropdown menu, and a datalist for selection.

**Requirements:**

1. **HTML Structure:**
   - Wrap the entire form in a `<form>` element.
   - Use a `<fieldset>` with a `<legend>` to group form fields under the title "Comment form".
   
2. **Form Fields:**
   - Text input for **First Name** with label.
   - Text input for **Last Name** with label.
   - A `<textarea>` for **Comment** input with label.
   - A `<select>` dropdown for choosing a **Spirit Animal**:
     - Options: Dog, Cat, Rabbit.
     - Include a placeholder option that is disabled and selected by default.
   - An `<input>` element with a linked `<datalist>` to allow the user to choose their **Browser**:
     - Options: Edge, Firefox, Chrome, Opera, Safari.
   
3. **Button:**
   - Include a submit button with descriptive text, e.g., "Click me!".

4. **Usability:**
   - Ensure each form element has an associated `<label>` for accessibility.
   - Use proper HTML semantics for inputs, textarea, select, and datalist.
   - Keep the form simple, clean, and readable.

**Objective:**  
Demonstrate knowledge of creating structured, interactive HTML forms with various input types, dropdowns, and datalists while maintaining semantic and accessible markup.


---

### 📝 Task 8: [Simple User Info Form]

**Problem Statement:**  
Create a clean and user-friendly form that collects basic personal information from a user. Style the form with CSS to make it visually appealing and centered on the page.

**Requirements:**

1. **HTML Structure:**
   - The page should have a `<h1>` heading titled "Tag Cardio: Input".
   - Wrap all input fields in a `<form>` element.

2. **Form Fields:**
   - **First Name** – text input with an associated `<label>`.
   - **Last Name** – text input with an associated `<label>`.
   - **Email** – text input with an associated `<label>`.
   - **City** – text input with an associated `<label>`.
   - **Submit Button** – labeled "Submit".

3. **CSS Styling:**
   - Use a clean, sans-serif font for the page (e.g., Arial).
   - Center all content horizontally on the page.
   - Give the form a white background, padding, rounded corners, and a subtle box-shadow.
   - Style the labels to appear bold.
   - Style the input fields with adequate width and padding.
   - Style the submit button with a colored background, white text, rounded corners, and a hover effect that darkens the button.

4. **Usability:**
   - Ensure all input fields are properly labeled for accessibility.
   - Maintain a clear and simple layout with good spacing between fields.

**Objective:**  
Demonstrate the ability to create a basic HTML form and apply CSS styling for a user-friendly and visually appealing interface.


---

### 📝 Task 9: [Simple Textarea Form]

**Problem Statement:**  
Create a simple form that allows users to input a multi-line message using a `<textarea>`. Style the form with CSS to make it visually appealing and centered on the page.

**Requirements:**

1. **HTML Structure:**
   - The page should have a `<h1>` heading titled "Tag Cardio: Textarea".
   - Wrap the textarea field in a `<form>` element.
   - Include a `<label>` for the textarea input with descriptive text, e.g., "Your Message".
   - Include a submit button labeled "Submit".

2. **Textarea Field:**
   - Should have a width of about 400px and height of about 150px.
   - Include padding for better readability.
   - Disable resizing of the textarea by the user (`resize: none`).
   - Add a border and slightly rounded corners.

3. **CSS Styling:**
   - Use a clean, sans-serif font for the page (e.g., Arial).
   - Center all content horizontally on the page.
   - Give the form a white background, padding, rounded corners, and subtle box-shadow.
   - Style the `<label>` as bold.
   - Style the submit button with a colored background, white text, rounded corners, and a hover effect that darkens the button.

4. **Usability:**
   - Ensure the textarea is clearly labeled for accessibility.
   - Maintain spacing between the label, textarea, and submit button.
   - Keep the layout simple and visually balanced.

**Objective:**  
Demonstrate the ability to create a multi-line text input form and apply CSS styling for a clean and user-friendly interface.


---

### 📝 Task 10: [Basic Label and Input Form]

**Problem Statement:**  
Create a simple form that demonstrates proper usage of `<label>` elements associated with `<input>` fields. Style the form to be centered and visually appealing.

**Requirements:**

1. **HTML Structure:**
   - Include a `<h1>` heading with the text: "Tag Cardio: Label".
   - Create a `<form>` element containing:
     - A `<label>` for the "First name" input and a corresponding `<input>` of type `text`.
     - A `<label>` for the "Last name" input and a corresponding `<input>` of type `text`.
     - A submit button labeled "Submit".
   - Ensure that each `<label>` is correctly linked to its `<input>` via the `for` and `id` attributes.

2. **CSS Styling:**
   - Use a clean, sans-serif font for the page (e.g., Arial).
   - Center all content horizontally on the page.
   - Style the form with a white background, padding, rounded corners, and a subtle box-shadow.
   - Bold the `<label>` text.
   - Style the submit button with a colored background, white text, rounded corners, and a hover effect that darkens the button.

3. **Layout:**
   - Add spacing between labels and input fields for clarity.
   - Maintain spacing between input fields and the submit button.

**Objective:**  
Demonstrate understanding of form labels for accessibility, proper linking between labels and inputs, and basic CSS styling for a clean form layout.


---

### 📝 Task 11: [Button Styling Exercise]

**Problem Statement:**  
Create a simple HTML page with a styled button inside a form. Focus on proper button usage, styling, and hover effects.

**Requirements:**

1. **HTML Structure:**
   - Include a `<h1>` heading with the text: "Tag Cardio: Button".
   - Create a `<form>` element containing a single `<button>` element.
   - The button should display the text "Click Me!".
   - Use the `type="button"` attribute for the button.

2. **CSS Styling:**
   - Use a clean, sans-serif font for the page (e.g., Arial).
   - Center all content horizontally.
   - Style the form with a white background, padding, rounded corners, and a subtle box-shadow.
   - Style the button with:
     - Blue background (`#2563eb`)
     - White text
     - Rounded corners
     - Padding and a comfortable font size
     - Smooth hover effect that slightly darkens the button (`#1d4ed8`)
     - Cursor changes to pointer on hover
     - Transition effect for background color

3. **Layout:**
   - Add spacing between the heading and the form for clarity.

**Objective:**  
Demonstrate knowledge of HTML button elements, proper button types, and CSS styling including hover and transition effects.


---

### 📝 Task 12: [Fieldset and Legend Exercise]

**Problem Statement:**  
Create a simple HTML form that uses `<fieldset>` and `<legend>` elements to group related form fields. Focus on proper semantic HTML and styling.

**Requirements:**

1. **HTML Structure:**
   - Include a `<h1>` heading with the text: "Tag Cardio: Fieldset Legend".
   - Create a `<form>` element containing a single `<fieldset>`.
   - Add a `<legend>` inside the fieldset with the text "Personal Information".
   - Inside the fieldset, include two labeled input fields:
     - First Name (`<input type="text">`)
     - Last Name (`<input type="text">`)
   - Include a submit button at the bottom of the fieldset.

2. **CSS Styling:**
   - Use a clean, sans-serif font (e.g., Arial) and center the content horizontally.
   - Style the form with:
     - White background
     - Padding
     - Rounded corners
     - Subtle box-shadow
   - Style the fieldset with:
     - Blue border (`#2563eb`)
     - Rounded corners
     - Padding
   - Style the legend with bold text and the same blue color as the fieldset border.
   - Style the input fields with padding and width of 200px.
   - Style the submit button with:
     - Blue background (`#2563eb`)
     - White text
     - Rounded corners
     - Hover effect darkening the background (`#1d4ed8`)
     - Pointer cursor on hover

3. **Layout:**
   - Ensure proper spacing between input fields and between the fieldset elements for readability.

**Objective:**  
Demonstrate knowledge of semantic grouping in HTML forms using `<fieldset>` and `<legend>` while applying consistent styling.


---

### 📝 Task 13: [Select and Option Exercise]

**Problem Statement:**  
Create a simple HTML form that allows the user to select an option from a dropdown menu. Use semantic HTML with proper labels.

**Requirements:**

1. **HTML Structure:**
   - Include a `<h1>` heading with the text: "Tag Cardio: Select Option".
   - Create a `<form>` element containing:
     - A `<label>` for a `<select>` element with the text "Choose a car:".
     - A `<select>` dropdown with the following options:
       - Volvo
       - Saab
       - Mercedes
       - Audi
     - A submit button at the bottom of the form.

2. **CSS Styling:**
   - Use a clean, sans-serif font (e.g., Arial) and center the content horizontally.
   - Style the form with:
     - White background
     - Padding
     - Rounded corners
     - Subtle box-shadow
   - Style the label with bold text.
   - Style the `<select>` element with:
     - Width of about 220px
     - Padding
     - Rounded corners
     - Border color `#ccc`
     - Font size 14px
   - Style the submit button with:
     - Blue background (`#2563eb`)
     - White text
     - Rounded corners
     - Hover effect darkening the background (`#1d4ed8`)
     - Pointer cursor on hover

3. **Layout:**
   - Ensure proper spacing between label, select dropdown, and the submit button for readability.
   - Align the form content to the left inside the white box while centering the entire form horizontally on the page.

**Objective:**  
Practice using the `<select>` and `<option>` tags for dropdown menus and applying consistent styling for form elements.


---

### 📝 Task 14: [Datalist Input Exercise]

**Problem Statement:**  
Create a simple HTML form that allows the user to select or type a value from a predefined list using the `<datalist>` element.

**Requirements:**

1. **HTML Structure:**
   - Include a `<h1>` heading with the text: "Tag Cardio: Datalist".
   - Create a `<form>` element containing:
     - A `<label>` for an `<input>` element with the text "Choose your browser from the list:".
     - An `<input>` element with the `list` attribute pointing to a `<datalist>` element.
     - A `<datalist>` element with the following options:
       - Edge
       - Firefox
       - Chrome
       - Opera
       - Safari
     - A submit button at the bottom of the form.

2. **CSS Styling:**
   - Use a clean, sans-serif font (e.g., Arial) and center the content horizontally.
   - Style the form with:
     - White background
     - Padding
     - Rounded corners
     - Subtle box-shadow
     - Left-aligned text inside the form
   - Style the label with bold text.
   - Style the `<input>` element with:
     - Width of about 220px
     - Padding
     - Rounded corners
     - Border color `#ccc`
     - Font size 14px
   - Style the submit button with:
     - Blue background (`#2563eb`)
     - White text
     - Rounded corners
     - Hover effect darkening the background (`#1d4ed8`)
     - Pointer cursor on hover

3. **Layout:**
   - Ensure proper spacing between label, input field, and the submit button for readability.
   - Align the form content to the left inside the white box while centering the entire form horizontally on the page.

**Objective:**  
Practice using the `<datalist>` element to provide a list of predefined options that the user can select or type from.


---
