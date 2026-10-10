# Mohammad Bilal Sikandar — Personal Portfolio Website

## About the Project

This is my personal portfolio website for INFR3120 Web and Scripting Programming at Ontario Tech University.

I built the website using HTML5 and CSS3. It has four pages: Home, About Me, Projects, and Contact.

The goal was to create a website where I could introduce myself, share some of my projects, and provide a way for people to contact me.

## Website Pages

- **Home (`index.html`):** A short introduction about me and my interests.
- **About Me (`about.html`):** Information about my education, experience, skills, personal photo, and introduction video.
- **Projects (`projects.html`):** Four projects and assignments I've worked on involving networking, programming, and web development.
- **Contact (`contact.html`):** A contact form with HTML5 input validation.

## Responsive Design

I used three separate CSS files to make the website work on different screen sizes.

- **Desktop (`desktop.css`):** 960px and above.
- **Tablet (`tablet.css`):** 481px to 959px.
- **Mobile (`mobile.css`):** 480px and below.

I based these breakpoints on the examples covered in the Week 3 lecture.

The layout changes depending on the device. On desktop, the highlight cards are displayed three per row. On tablet, they are displayed two per row, and on mobile, they stack vertically.

I used percentage-based widths to help the layout adjust to different screen sizes without using Flexbox.

## Colours and Gradients

I used Adobe Color to help choose a dark blue colour scheme for the website.

The main colours are:

- `#0B1426` — Dark navy, used for the main background.
- `#172554` — Navy blue, used in the header and backgrounds.
- `#2563EB` — Bright blue, used for buttons and highlights.
- `#5EEAD4` — Light teal, used for headings and accents.
- `#E2E8F0` — Light grey, used for the main text.

I chose these colours to give the website a clean design inspired by cybersecurity while keeping the text easy to read.

I also used two types of CSS gradients.

**Angle-based gradient:**

`linear-gradient(135deg,#0b1426,#172554,#1e40af)`

This is used in the header to create a diagonal transition between different shades of blue.

**Direction-based gradient:**

`linear-gradient(to right, #172554, #0f2944)`

This is used in the Home page introduction section to create a left-to-right colour transition.

Both gradients help keep the design consistent throughout the website.

## Code Sources

I used the INFR3120 course materials from Weeks 1–4 as references for HTML5, CSS3, forms, and responsive design.

I also used ChatGPT (OpenAI) for help drafting and understanding parts of the HTML, CSS, and documentation.

## Testing

I tested the website using the following tools:

- **W3C HTML Validator:** All four HTML pages passed validation.
- **W3C CSS Validator:** All three CSS files passed validation.
- **W3C Link Checker:** No broken HTTP links were reported.
- **WAVE:** Home, Projects, and Contact had no reported errors, contrast errors, or alerts. The About Me page had no errors or contrast errors, with one informational alert related to the HTML5 video.
- **Responsive testing:** Checked the layout on desktop, tablet, and mobile screen sizes.
- **Form testing:** Checked required fields, email validation, cellphone number validation, and the reset button.
- **Spelling:** Reviewed all four pages and found no spelling issues.

## GitHub and Live Website

I uploaded the project to GitHub and used GitHub Pages to publish the website.

**GitHub Repository:** https://github.com/Bilal682-7/Bilal-portfolio

**Live Website:** https://bilal682-7.github.io/Bilal-portfolio/