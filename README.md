# Mohammad Bilal Sikandar — Personal Portfolio

## Colour Scheme

I created a custom colour palette using Adobe Color to give my portfolio a professional, cybersecurity-inspired appearance.

The five main colours are:

- **Dark Navy (`#0B1426`):** Main website background.
- **Navy Blue (`#172554`):** Header and gradient backgrounds.
- **Blue (`#2563EB`):** Navigation highlights and buttons.
- **Teal (`#5EEAD4`):** Headings, links, and accents.
- **Light Grey (`#E2E8F0`):** Main text for readability.

I selected a custom colour harmony in Adobe Color because I wanted to combine dark blue backgrounds with contrasting teal accents and light text.

## Responsive Design

I used three separate CSS files to make my portfolio responsive on mobile, tablet, and desktop screens.

- **Mobile (`mobile.css`):** 480px and below.
- **Tablet (`tablet.css`):** 481px to 959px.
- **Desktop (`desktop.css`):** 960px and above.

I chose these breakpoints based on the media query examples in the Week 3 lecture.

The mobile layout stacks the navigation links and content cards vertically. The tablet layout displays two highlight cards per row, while the desktop layout displays three.

I used percentage-based widths to create a fluid layout that adjusts to different screen sizes. I did not use Flexbox, as required by the assignment.

## CSS Gradients

I used two types of linear gradients in my portfolio website.

**1. Angle-Based Linear Gradient**

I used `linear-gradient(135deg, #0b1426, #172554, #1e40af)` in the website header. This creates a diagonal colour transition between dark navy and blue.

**2. Direction-Based Linear Gradient**

I used `linear-gradient(to right, #172554, #0f2944)` in the homepage hero section. This creates a horizontal colour transition from left to right.

Both gradients help maintain a consistent blue-themed design throughout the website.

## Project Overview

This is my personal portfolio website for INFR3120 — Web and Scripting Programming at Ontario Tech University.

The website introduces my background as a Networking and IT Security student and highlights my education, technical skills, work experience, and academic projects.

The portfolio contains four HTML pages:

- **Home (`index.html`):** Personal introduction and areas of interest.
- **About Me (`about.html`):** Education, technical skills, work experience, personal photograph, and introduction video.
- **Projects (`projects.html`):** Four projects involving networking, programming, and web development.
- **Contact (`contact.html`):** Contact information and an HTML5 form with required-field, email, and cellphone validation.

The website uses HTML5 and CSS3 techniques covered in the course, including semantic elements, external stylesheets, fluid layouts, media queries, and gradients.

## Code Sources and Attribution

**Course materials:** INFR3120 Web and Scripting Programming, Weeks 1–4 lecture notes.

**AI assistance:** ChatGPT (OpenAI) was used to help draft and explain portions of the HTML, CSS, and README documentation.

The website uses HTML5 and CSS3 concepts covered in the course, including semantic HTML, forms, gradients, fluid layouts, and media queries.

Before submission, the code must be reviewed to ensure compliance with the assignment's maximum 10% external-code allowance. Any retained external code must be attributed and explained in code comments.

## Testing and Validation

The following checks are required before submission:

- **HTML Validation:** Passed W3C validation for all four HTML pages (index.html, about.html, projects.html, contact.html).
- **CSS Validation:** Passed W3C validation for all three stylesheets (desktop.css, tablet.css, mobile.css).
- **Link Testing:** W3C Link Checker — Pending
- **Spelling:** Spelling review — Pending
- **Accessibility:** WAVE Accessibility Checker — Pending
- **Responsive Layout:** Mobile, tablet, and desktop — Pending final verification

### Contact Form Testing

- Required-field validation — Passed
- Email format validation — Passed
- Cellphone number validation — Passed
- Reset button — Passed