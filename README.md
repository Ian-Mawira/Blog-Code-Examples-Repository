# Blog Code Examples

Welcome to the Blog Code Examples repository! This repository contains reusable code snippets and customizations for WordPress, including CSS tweaks, JavaScript interactions, and example PHP functions.

## Contents

- **CSS**: Styling snippets for custom layouts and design improvements.
- **JavaScript**: Simple interactions to enhance user experience.
- **PHP Functions**: Useful PHP functions for additional WordPress functionality.

## Example Usage

### CSS
```css
/* Centered header styling */
header {
    text-align: center;
    padding: 10px;
    background-color: #f4f4f4;
}
JavaScript
javascript
// Basic click event for menu toggle
document.getElementById('menu-toggle').addEventListener('click', function() {
    document.getElementById('menu').classList.toggle('open');
});
PHP
php
// Custom excerpt length for blog posts
function custom_excerpt_length($length) {
    return 20;
}
add_filter('excerpt_length', 'custom_excerpt_length');
