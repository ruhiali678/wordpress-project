# WordPress-project
This is my first Git Repository. 
<br>
Author - Ruhi Ali

# Portfolio Website

## Description
This is a portfolio website developed as an assignment project. It showcases web design skills and includes various sections like portfolio, about, contact, and more. The project demonstrates proficiency in front-end development and custom theme customization using WordPress.

Plugins and Tools Used
Yoast SEO: For SEO optimization.
Contact Form 7: To create and manage contact forms.
Elementor: For custom page building.
WP Super Cache: For caching the website.
Elementor Header & Footer Builder
Advanced Custom Fields: Theme Code
FooBox Image Lightbox
FooGallery

Custom Code and Theme Customizations
File: style.css

/* Custom styling for portfolio sections */
.portfolio-item {
    border: 1px solid #ddd;
    padding: 10px;
    margin-bottom: 20px;
}

Custom Functions

File: functions.php

// Function to add a custom footer message
function custom_footer_message() {
    echo '<p>Thank you for visiting my portfolio website!</p>';
}
add_action('wp_footer', 'custom_footer_message');

