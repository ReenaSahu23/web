# Typing Speed Tracker Web App

This project is a simple typing speed tracker web application built using HTML, CSS, and JavaScript.  It demonstrates basic DOM manipulation and event handling.  Note that this code creates the entire UI dynamically using JavaScript; there's no pre-existing HTML structure for the elements.

## Functionality

The application dynamically creates a webpage with the following elements:

1. **Container Div:** A central div element acting as a container for all other elements.  It's styled with a background image, borders, and centered on the page.

2. **Heading:** An h1 element displaying the title "Web Technologies" (initially), which can be changed by clicking a button.

3. **Paragraph:** A paragraph element containing a simple description.

4. **Button:** A button that, when clicked, updates the heading text to "Updated Heading".


## Technologies Used

* **HTML:** Used for the basic webpage structure (although the structure itself is generated dynamically by the JavaScript).
* **CSS:** Used (inline within the JavaScript) for styling the elements, including background image, colors, borders, margins, and positioning.  Inline CSS is generally not recommended for larger projects, but is acceptable for a small example like this.
* **JavaScript:** Used to dynamically create the HTML elements (div, h1, p, button), add content to the elements, set attributes, apply styling using inline styles, and handle the button click event to change the heading text.  Features include:
    * `document.createElement()`: To create HTML elements.
    * `appendChild()`: To add elements to the DOM.
    * `setAttribute()`: To set element attributes.
    * `addEventListener()`: To handle user interaction events.
    * `textContent`: To set the text content of elements.
    * `style` object: For inline styling.



## Project Files

The main project file is `task1_webtech.html`.


## To Run the Application

1. Save the provided HTML code as `task1_webtech.html`.
2. Open the HTML file in any web browser.

You should see a webpage with a container, a heading, a paragraph, and a button.  Clicking the button will update the heading.  The styling demonstrates basic CSS capabilities for layout and appearance.  This project provides a foundation for expanding functionality into a true typing speed tracker, such as including a text input area, a timer, and a way to calculate words per minute.
