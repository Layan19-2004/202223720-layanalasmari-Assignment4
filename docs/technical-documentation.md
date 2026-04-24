# Technical Documentation

## Project Overview

This project is a personal portfolio web application developed for Assignment 4, the final project of the course.

It combines all previous assignments into one complete and polished website. The application demonstrates front-end development skills using HTML, CSS, and JavaScript through a responsive, interactive, and professional portfolio.

The website presents personal information, technical skills, projects, GitHub repositories, completed courses, and contact details.

---

## Project Structure

```
202223720-layanalasmari-assignment4/
│── index.html
│── README.md
│── .gitignore
│
├── css/
│   └── styles.css
│
├── js/
│   └── script.js
│
├── assets/
│   └── images/
│
└── docs/
|    ├── technical-documentation.md
|    └── ai-usage-report.md
└── presentation/
    ├── slides.pdf
    └── demo-video.mp4

```

---

## System Design Approach

The project uses a clear front-end file structure:

- index.html for structure and content
- styles.css for design and responsiveness
- script.js for dynamic behavior and logic

This separation improves readability, maintenance, debugging, and scalability.

---

## HTML Implementation

Semantic HTML elements were used to organize content clearly.

### Main Sections

- Header / Hero Section
- Navigation Bar
- About Me
- Skills Dashboard
- Projects
- GitHub Repositories
- Online Courses
- Contact Form
- Footer

### Header Section

Contains:

- Name
- Short introduction
- Dynamic greeting
- Theme toggle button
- Quick action buttons
- Visitor name input
- Site timer

### Navigation Bar

Sticky navigation allows fast movement across all sections.

---

## CSS Implementation

The stylesheet was organized into reusable components.

### Main Styling Areas

- Layout
- Header
- Navigation
- Cards
- Buttons
- Forms
- Skills Bars
- Footer
- Responsive Design
- Animations

### CSS Variables

Variables were used for:

- Colors
- Backgrounds
- Borders
- Text colors
- Button colors

This improves consistency and makes dark mode easier to manage.

---

## Dark Mode System

Dark mode is controlled by adding or removing:

body.dark-mode

When active, colors automatically update across:

- Background
- Cards
- Text
- Inputs
- Buttons
- Navigation

The selected theme is saved using localStorage.

---

## Responsive Design

The website was tested for different screen sizes.

Responsive adjustments include:

- Wrapping navigation links
- Full-width buttons on mobile
- Flexible grid layouts
- Resized spacing and text
- Mobile-friendly controls

---

## JavaScript Implementation

All interactivity is handled in script.js.

---

## 1. Smooth Scrolling Navigation

Navigation links scroll smoothly to sections using browser scrolling behavior.

Benefit:

- Better user experience
- Modern navigation feel

---

## 2. Dynamic Greeting

The website checks the current time and displays:

- Good morning
- Good afternoon
- Good evening

Benefit:

- Personalized experience

---

## 3. Theme Toggle

Users can switch between light and dark mode.

Features:

- Dynamic button text
- Saved preference using localStorage

---

## 4. Visitor Name Memory

Users can enter their name.

The name is saved in localStorage and displayed again on future visits.

Benefit:

- Personalization
- Demonstrates browser storage

---

## 5. Site Timer

A live timer counts how long the visitor has stayed on the website.

Updated every second.

---

## 6. Skills Dashboard

A new Assignment 4 feature.

Displays skill progress bars such as:

- HTML
- CSS
- JavaScript
- Cybersecurity

Bars animate when the section becomes visible on screen.

Benefit:

- Visual presentation of strengths
- More professional portfolio appearance

---

## 7. Project Filtering and Sorting

Projects can be filtered by category:

- All
- Academic
- Design
- AI

Projects can also be sorted:

- Default
- Title A-Z
- Title Z-A

The selected filter can be saved using localStorage.

---

## 8. GitHub API Integration

Repositories are loaded dynamically from GitHub API.

Displayed information:

- Repository name
- Description
- Link to repository

Error handling messages are shown if loading fails.

Benefit:

- Real live data
- Automatically updated content

---

## 9. Contact Form Validation

The contact form performs front-end validation.

Checks include:

- Empty fields
- Name length
- Letters only in name
- Valid email format
- Message minimum length

If invalid:

- Error message shown

If valid:

- Success message shown

Note:

This form is front-end only and does not send data to a backend server.

---

## 10. Back To Top Button

A floating button appears after scrolling down.

When clicked:

- Smoothly returns user to top of page

Benefit:

- Better navigation for longer pages

---

## Performance Improvements

Several improvements were applied:

- Clean CSS organization
- Reduced repetition
- Efficient DOM updates
- Lightweight vanilla JavaScript
- Limited API results
- Responsive images
- No heavy frameworks

---

## Browser Compatibility

The website was designed for modern browsers such as:

- Google Chrome
- Microsoft Edge
- Firefox

---

## Challenges and Solutions

### Challenge 1: Dark Mode Consistency

Some elements required separate dark styling.

Solution:

Used CSS variables and targeted dark mode selectors.

### Challenge 2: Sorting with Filtering

Projects needed correct order while keeping selected category.

Solution:

Filter first, then sort visible items.

### Challenge 3: Live External Data

GitHub API requests may fail.

Solution:

Added loading and error feedback.

### Challenge 4: Final Polish

The project needed stronger professional appearance.

Solution:

Added skills dashboard, floating top button, and cleaner layout.

---

## User Experience Decisions

The website focuses on clarity and simplicity.

Features that improve usability:

- Sticky navigation
- Responsive layout
- Clear button labels
- Helpful validation messages
- Saved preferences
- Smooth animations
- Easy section structure

---

## Future Improvements

Possible future upgrades:

- Real backend contact form
- Resume download
- Search projects feature
- Accessibility enhancements
- Multi-language support
- Additional project pages

---

## Conclusion

This final project successfully combines structured HTML, maintainable CSS, and interactive JavaScript into a professional personal portfolio web application.

It demonstrates responsive design, browser storage, API integration, filtering logic, validation, animation, and strong front-end development practices.