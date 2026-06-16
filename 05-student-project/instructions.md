# Student Project: Responsive Webpage Layout

## Task

Create a webpage that combines CSS Grid and CSS Flexbox.

You may choose one of these topics:

- A school club website
- An educational website
- A sports team page
- A music or hobby website
- A simple news or blog homepage

## Requirements

Your webpage must include:

- Header
- Navigation
- Main content area
- Sidebar or secondary content area
- Footer
- At least one card section
- At least one button group or link group

## CSS Requirements

You must use:

- CSS Grid for the overall page layout
- CSS Flexbox for navigation or component alignment
- A media query for mobile screens

## Written Explanation

At the bottom of your HTML file, add a comment explaining:

1. Where you used Grid and why.
2. Where you used Flexbox and why.
3. How your layout changes on mobile.

## Extension

Use this responsive Grid pattern for your card section:

```css
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
}
```
