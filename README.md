# Joseph's Portfolio Website

## About My Website

For this assignment, I created my own personal portfolio website using HTML5 and CSS3. My website has four different pages which are Home, About Me, Projects, and Contact Me.

I made the website to show some information about myself, some of the projects I have worked on, and a way for someone to contact me. I also added my own picture and an introductory video to my About Me page.

## Website Structure

I used HTML5 semantic tags to organize my website. Some of the main tags I used were header, nav, article, and footer.

I also added a navigation menu to my pages so the user can move between the Home, About Me, Projects, and Contact Me pages.

## Responsive Design

I made my website responsive so that it can work on different screen sizes. I used three separate CSS files for laptop/desktop, tablet, and mobile.

### Laptop / Desktop

For laptop and desktop screens, I used full.css.

The viewport size I used is 961px and above. I used a wrapper width of 90% because there is more screen space available on a laptop or desktop.

### Tablet

For tablets, I used tablet.css.

The viewport size I used is from 481px to 960px. I changed the wrapper width to 95% so that more of the tablet screen is used. I also made the image, video, and contact form larger than they are on the desktop version.

### Mobile

For mobile devices, I used phone.css.

The viewport size I used is 480px and below. I used a wrapper width of 100% so the website can use the available space on a smaller screen.

I also changed the navigation links so they display vertically instead of beside each other. This makes the navigation easier to read on a phone.

I chose these sizes because I wanted to separate smaller phone screens, medium tablet screens, and larger laptop or desktop screens. I started the desktop version at 961px so that it does not overlap with the tablet version, which ends at 960px.

I did not use Flexbox in my website.

## Gradients

I used two different gradients in my website.

For the header, I used this regular linear gradient:

background: linear-gradient(#FFB266, #E58A35);

This changes the header from a lighter orange to a darker orange.

For the footer, I used an angled linear gradient:

background: linear-gradient(45deg, #6B3A1E, #3B2F2F);

The 45deg makes the gradient go across the footer at an angle instead of going straight from one color to another.

## Color Scheme

For my website, I decided to use a warm orange and brown color scheme with cream and white backgrounds.

These are the main colors I used:

- #FFB266 - Light orange
- #E58A35 - Medium orange
- #8A4B08 - Dark orange/brown
- #6B3A1E - Brown
- #3B2F2F - Deep brown
- #FFF4E8 - Light cream
- White - Main content background

I used the orange colors mainly for my header and headings. I used the darker brown colors for text and my footer. I used the light cream color for the page background and white for the main content area.

I chose these colors because I wanted my portfolio to have a warm color theme while still making the text easy to read.

## About Me Page

On my About Me page, I added a short introduction about myself, my own picture, and an introductory video.

For the video, I used the HTML5 video element. I added video controls so the user can play and pause the video, and I also added a poster image that appears before the video starts.

## Projects Page

On my Projects page, I added five projects that I have worked on.

Some of the projects include building an ATM using Python, building a network for a company, learning about music from different cultures, creating a password checker, and creating a number guessing game.

I added a heading and description for each project to explain what I did.

## Contact Me Page

On my Contact Me page, I created a form that asks the user for their name, email, cell number, and comments.

I used HTML5 form elements and validation. I used the required attribute so that the required fields cannot be left empty. I used the email input type for the email field and the tel input type for the cell number.

## Testing

I used the testing tools required in the assignment to check my website.

The tools I used are:

- W3C Markup Validation Service for my HTML
- W3C CSS Validation Service for my CSS
- W3C Link Checker to check my links
- A spelling checker to check my spelling
- WAVE to check the accessibility of my website

I also tested my website at different screen sizes to make sure the laptop, tablet, and mobile layouts worked properly.

## GitHub and Version Control

I used Git and GitHub while creating my website. I made commits at different stages of my project so that my GitHub repository shows the progress I made while building the website.

My repository contains my HTML files, CSS files, images, video, and README file.

I also used GitHub Pages to host my completed portfolio website.

## Sources

I mainly used the HTML5 and CSS3 code and techniques that I learned from the INFR3120 course lectures to create my website.

## Sources

### list-style-type: none;
Source: MDN Web Docs  
Author: Mozilla  
Article: CSS list-style-type

### font-weight: bold;
Source: MDN Web Docs  
Author: Mozilla  
Article: CSS font-weight

### display: inline;
Source: MDN Web Docs  
Author: Mozilla  
Article: CSS display

### input[type="submit"]
Source: MDN Web Docs  
Author: Mozilla  
Article: CSS Attribute Selectors