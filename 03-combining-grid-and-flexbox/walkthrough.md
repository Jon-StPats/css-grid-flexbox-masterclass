# Walkthrough: Combining Grid and Flexbox

## Key Rule

> Grid for the page. Flexbox for the pieces.

## Where Grid Is Used

The `.container` element uses CSS Grid to control the main webpage sections:

- Header
- Navigation
- Main content
- Sidebar
- Footer

This is a two-dimensional layout because it uses both rows and columns.

## Where Flexbox Is Used

Flexbox is used in:

- `nav` to align links in one row.
- `.button-group` to align buttons in one row.

These are one-dimensional layouts because the content is mainly arranged in a single direction.

## Responsive Design

The media query changes the layout on smaller screens:

- The page becomes one column.
- Navigation links stack vertically.
- Cards stack vertically.
- Buttons stack vertically.
