# Portfolio Landing Page Planning Document

Student Name: Cem Sanli 
Assignment: Web Authoring Assignment 1  
Date: March 9, 2026  

---

# 1. Portfolio Purpose and Audience

## Portfolio Purpose

The purpose of this portfolio landing page is to introduce visitors to my machine learning projects while demonstrating my understanding of web development using HTML and CSS. The website will serve as a central hub where users can learn about me and explore several machine learning projects.


## Target Audience

The main audience for this portfolio is my lecturers who will review my work as part of the Web Authoring module. However, the website is also designed in a way that could be suitable for future employers or collaborators who may want to see examples of my projects.

Understanding the audience influenced the design decisions. The layout is simple and professional so that users can easily navigate the website and quickly understand the content.


# 2. Content Planning

## Header Section

The header will contain the website title and a navigation menu. The navigation menu will allow users to move between the main pages of the portfolio including Home, About, and Contact.


## Introduction Section

This section will briefly introduce who I am and what the portfolio contains.

Drafted introduction text:

Hello, welcome to my portfolio. This site highlights a few machine learning projects I developed while studying the foundations of AI and machine learning. Explore the projects below to learn more about my work.


## Projects Section

The projects section will display four machine learning projects using a card layout. Each card will include:

- Project title  
- Short description  
- Image placeholder  
- Link to the project page  

This layout makes the projects easy to view and visually organized.


## Navigation

Navigation will appear at the top of the page inside the header. The navigation menu will include links to:

1. Home (index.html)  
2. About (about.html)  
3. Contact (contact.html)  



## Footer Section

The footer will include:

- Copyright sign 
- Portfolio name  



# 3. Design Decisions

## Color Scheme

 Primary color: Dark Purple #6a4cff
 Secondary color: Deep Purple #3c2a6b
 Accent color: Light Purple #9d8cff
 Background color: Dark background #0f0b1f
 Text color: Light text #f2f1ff

### Reason for Color Choice

The dark purple theme was chosen because purple is my favourite colour and I wanted the portfolio to reflect my personal style. Using a colour that I like makes the website feel more unique and representative of me. I also chose a dark background with light text because it improves readability and reduces strain on the eyes when viewing the website for long periods of time. This combination also helps important content, such as project cards, stand out clearly on the page.

The colors were selected using the Coolors color palette generator (Coolors, 2024).

Accessibility was considered by checking color contrast using the WebAIM contrast checker to ensure text remains readable for users (WebAIM, 2024).


## Typography

Heading font: Arial, sans-serif  
Body text font: Verdana, Arial, sans-serif  

Web fonts used: No

### Typography Reasoning

Arial and Verdana are widely supported system fonts that are easy to read on most devices. Using simple fonts ensures compatibility across browsers while maintaining a professional appearance.


## Layout

### Overall Structure

The landing page will use a vertical layout with sections stacked from top to bottom:

1. Header
2. Introduction
3. Projects
4. Footer

The projects section will use a grid layout so that multiple project cards can appear side by side.


### Content Width

The page will use a maximum width of approximately 1100px so that the content does not stretch too widely on large screens.


### Spacing

Spacing will be created using margins and padding between sections to make the page easier to read and visually balanced.


### Layout Reasoning

This layout keeps the website simple and structured. A vertical layout allows visitors to scroll naturally through the page while the grid layout helps display projects clearly.


# 4. Navigation Structure

## Navigation Location

Navigation will appear in the header at the top of the page.


## Navigation Links

1. Home -> index.html  
2. About -> about.html  
3. Contact -> contact.html  
 


## Indicating Current Page

The current page will be highlighted using CSS styling such as color changes or hover effects.


## Navigation Reasoning

Top navigation is a common web design pattern that helps users easily move between sections of a website.


# 5. Wireframes

Desktop wireframe: See wireframe-desktop.png  
Mobile wireframe: See wireframe-mobile.png  


## Header Area

The header will contain the portfolio title and navigation menu arranged horizontally.


## Main Content Area

The main content will include:

1. Introduction section  
2. Projects section  


## Projects Section

Projects will be displayed using a grid of cards. Each card will include an image, title, description and link.


## Footer Area

The footer will contain copyright information.


## Responsive Considerations

On smaller screens the project cards will stack vertically to maintain readability.


# 6. Technologies and Tools

Text Editor: VS Code  
Browser for testing: Google Chrome, Safari, Brave 
Version Control: Git and GitHub  
Wireframing tool: Pen and paper  
Color selection tool: Coolors.co  

### Reason for Tool Choice

VS Code provides helpful features such as syntax highlighting and extensions like Live Server. GitHub allows version control and easy project submission. Chrome, Safari and Brave allow testing across multiple browsers.



# 7. HTML Elements

## `<header>`

Purpose: Defines the header section of a webpage.

Use in this project: It will contain the site title and navigation menu.

Reason: It clearly identifies the introductory section of the webpage.


## `<nav>`

Purpose: Defines a section containing navigation links.

Use in this project: It will organize links to different pages in the portfolio.

Reason: It improves the page structure.

## `<section>`

Purpose: Groups related content together.

Use in this project: It will organize the introduction and projects areas.

Reason: It improves the logical structure of the webpage.


## `<footer>`

Purpose: Defines the footer section of a webpage.

Use in this project: It will contain copyright information.

Reason: It clearly separates footer content from the main page.


# 8. CSS Properties and Techniques

## Flexbox

Flexbox allows flexible alignment of elements in rows or columns. It will be used to align navigation items.


## Margin and Padding

These properties control spacing around elements. They will be used to separate sections and improve readability.


## Border Radius

This property creates rounded corners on elements such as cards and buttons.


## Hover Effects

Hover effects allow styles to change when a user moves the cursor over an element. This will be used for project cards.


# 9. HTML and CSS Evolution

## HTML Evolution

HTML was first developed in the early 1990s as a simple way to structure documents on the web. Early versions of HTML were limited and mainly focused on displaying text and links between pages.

Modern versions such as HTML5 introduced many new features including semantic elements like `<header>`, `<nav>`, `<section>`, and `<footer>`. These elements improve page structure and make websites easier to understand for both developers and assistive technologies (MDN Web Docs, 2024).

HTML5 also introduced support for multimedia content and improved accessibility, making it an important step in modern web development (W3C, 2024).


## CSS Evolution

CSS was created to separate webpage design from HTML structure. Early CSS allowed developers to control colors, fonts and spacing.

Later developments introduced powerful features such as animations, transitions, and advanced layout systems. Modern CSS technologies such as Flexbox and Grid allow developers to build responsive layouts that adapt to different screen sizes (MDN Web Docs, 2024).

These features allow developers to create visually appealing and responsive websites while maintaining clean HTML structure.


## Importance of HTML and CSS Evolution

The evolution of HTML and CSS allows developers to create modern websites that are structured, accessible and visually appealing. Features such as semantic HTML and flexible layouts make websites easier to maintain and improve the user experience.

These improvements allow this portfolio website to present content clearly while using modern design techniques.



# 10. Implementation Plan

1. Create the basic HTML structure.
2. Add the header and navigation menu.
3. Create introduction and project sections.
4. Add project cards and images.
5. Create an external CSS file.
6. Style the layout and colors.
7. Add hover effects and spacing.
8. Test and validate the website.


## Testing and Validation

The website will be tested using:

- W3C HTML Validator  
- W3C CSS Validator  
- Testing in Chrome, Safari and Brave browsers


## Anticipated Challenges

Possible challenges include creating a responsive layout, organizing CSS styles effectively and ensuring the website remains accessible and easy to navigate.



# References

Coolors (2024) *Color Palette Generator*. Available at: https://coolors.co (Accessed: 11 March 2026).

MDN Web Docs (2024) *HTML: HyperText Markup Language*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 11 March 2026).

MDN Web Docs (2024) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 11 March 2026).

WebAIM (2024) *Contrast Checker*. Available at: https://webaim.org/resources/contrastchecker/ (Accessed: 11 March 2026).

W3C (2024) *HTML5 Specification*. Available at: https://www.w3.org/TR/html5/ (Accessed: 11 March 2026).

W3C (2024) *CSS Specifications*. Available at: https://www.w3.org/Style/CSS/specs.en.html (Accessed: 11 March 2026).



Planning completed: 11 March 2026

Ready to begin implementation: Yes

Next step: Create the basic HTML structure.