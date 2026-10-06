
# Task 4 - Responsive Web Design

## Web Development Internship

### Objective

The objective of this task is to convert a desktop-oriented website
into a mobile-friendly responsive website using CSS media queries.

## Technologies Used

- HTML5
- CSS3
- CSS Media Queries
- VS Code
- Google Chrome DevTools

## Features

- Responsive navigation
- Mobile-friendly layout
- Responsive images
- Flexible card layout
- Mobile typography
- No horizontal overflow
- Responsive design for different screen sizes

## Media Query

The website uses a CSS media query for screens with a maximum width
of 768px.

Features
1. Responsive Navigation

The navigation menu is displayed horizontally on larger screens and changes
to a vertical layout on smaller screens.

2. Responsive Hero Section

The hero section adjusts its padding and font sizes according to the
screen size.

3. Responsive Columns

The three feature columns are displayed side-by-side on desktop screens
and stacked vertically on mobile screens.

4. Responsive Images

Images automatically scale within their containers using:

img {
    max-width: 100%;
    height: auto;
}
5. Responsive Typography

Font sizes are reduced on smaller screens to improve readability.

6. Mobile-Friendly Layout

The website avoids fixed-width content on smaller screens and is designed
to prevent horizontal scrolling.