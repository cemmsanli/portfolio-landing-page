# Machine Learning Portfolio Website

## Student Information

Student Name: Cem Sanli 

Assignment: Web Authoring Assignment 1 

Repository: https://github.com/cemmsanli/portfolio-landing-page

Live Site: https://cemmsanli.github.io/portfolio-landing-page/ 



## 1. Portfolio Overview

### What is your portfolio and what does it do? 

This is my personal professional site designed to show off the machine learning projects I’ve been working on. It’s a three page website that introduces who I am, displays my technical work in a clean grid format and gives people a way to get in touch with me.

### What makes your portfolio effective? 

I think the dark purple theme reflects my personality and really fits the subject of AI and Machine Learning. I’m especially proud of how the project cards react when you hover over them it makes the site feel interactive and modern rather than just a static page.

## 2. Page Contents

### Header Section

Content: My name is styled like a signature using a cursive font, followed by a simple navigation list (Home, About, Contact).

Reasoning: I wanted my name to stand out as a brand. Centering the navigation underneath makes it really easy to find on both desktop and mobile.

### Introduction Section

Content: A short "Hello!" and a brief explanation that this site is a collection of my ML studies.

Purpose: It immediately tells the visitor what they are looking at so they don't have to guess my background.

### Projects Section

Presentation: I used a CSS Grid to create a "Card" layout for my four main projects: the Artificial Neuron, Language Detector, Markov Chain Generator and Digit Analyzer.

Details: Each card has a relevant tech image, a title, a short description of how the model works and a link button.

Design Choice: Cards are great because they group information visually. Even if the descriptions are different lengths, the grid keeps everything lined up perfectly.

### Navigation & Footer

Navigation: It’s at the top of every page. It’s a standard horizontal list that stays consistent so the user never feels lost.

Footer: A simple copyright notice with the year 2026 to make the site look official and finished.

## 3. Special Features
Feature 1: Interactive Hover Effects: I added a "scale" transformation to the project cards. When you mouse over them, they grow slightly, which makes the UI feel more responsive.

Feature 2: Responsive Grid: Using auto fit in my CSS means the projects automatically stack into one column on a phone but spread out on a laptop without me needing a million media queries.

Feature 3: Custom Branding: I used a specific cursive font for the header to act as a logo, giving the site a more personal touch.

## 4. Technologies Used
Core Tech

HTML5 & CSS3: The backbone of the entire project.

Development Tools

VS Code: My main editor for writing all the code.

Chrome/Safari/Brave: Used for constant testing and inspecting elements.

Git/GitHub: For version control and hosting the live site.

Key Elements & Techniques

Semantic HTML: I used `<header>, <main>, <section>, and <footer>` to keep the code organized and accessible.

CSS Flexbox: Used for the navigation links and the contact form layout.

CSS Grid: This was the main tool for the project gallery.

## 5. Viewing the Site
Local Setup:

Clone the repo: git clone https://github.com/cemmsanli/portfolio-repo

Navigate to the folder: cd portfolio-landing-page

Open index.html in your browser.

Live Link: https://cemmsanli.github.io/portfolio-repo

## 6. Design Decisions
Color Scheme: I went with a deep purple (#0f0b1f) for the background and a brighter violet (#6a4cff) for accents. I chose this because it's my favorite color palette and it fits the AI theme.

Accessibility: I made sure the text was off-white so that it has a high contrast against the dark background, making it easy to read for everyone.

Typography: I used Arial/Helvetica for the body text because it's clean and professional, while the cursive header adds a bit of personality.

## 7. Credits and Attributions
Images: Placeholders sourced from Pinterest and Vecteezy to represent the ML concepts.

Code: I used MDN Web Docs to help refine the Flexbox logic for my contact form.

Fonts: "Brush Script MT" for the logo.

## 8. Challenges and Solutions
Problem: Initially, my project images were all different sizes, which made the cards look messy.

Solution: I applied width: 100% and specific border-radius rules in CSS to force the images to fit the card containers uniformly.

Lesson: I learned that managing image containers is just as important as the images themselves.

## 9. Learning Reflection
HTML: I learned that using the right tags (like `<nav>` instead of just `<div>`) makes a huge difference in how clean the code looks and how screen readers see the site. It’s all about structure.

CSS: This project really helped me master CSS Grid. Being able to create a layout that "just works" on different screen sizes without breaking was a huge "aha!" moment for me.


## 10. Future Enhancements
Content: I’d love to add actual "Case Study" pages for each project instead of just a summary.

Tech: I want to add a JavaScript "Dark/Light mode" toggle for users who prefer a bright screen.


## 11. Testing and Validation
HTML/CSS: Both files were run through the W3C validators. I had a few stray </div> tags at first, but I've cleared those up for the final version.

Responsive Testing: I tested the site on my phone and my laptop. The grid scales down from 3-4 columns to a single column perfectly.

## 12. Repository Information
Repo Link: https://github.com/cemmsanli/portfolio-repo


## 13. Contact and Feedback
If you have any questions about the code or the ML models, feel free to reach out to me on cem8anli@gmail.com or open an issue in this GitHub repository!

Documentation completed: March 18, 2026
