# Capstone-Responsive Website Project

## **Title:** Wanderlust-Travel Agency Website 
## **Theme:** A single-page, responsive landing page for a fictional Indian travel agency, focusing on high visual appeal, smooth navigation, and clear presentation of tour packages and destinations.

## Sections Implemented

### Header/Navigation

> Sticky navigation bar with responsive hamburger menu for mobile devices.

### Hero Banner

> High-impact full-width banner with overlay and a clear Call-to-Action (CTA).

### Popular Destinations

> A grid showcasing 6 key travel locations (including Goa, Jaipur, Varanasi, and Sundarbans).

### Curated Tour Packages

> A responsive grid presenting 6 distinct tour packages with pricing and duration.

### How It Works

A simple 3-step guide using a pseudo-glassmorphism effect.

### Traveler Testimonials

A grid of customer reviews with avatars and star ratings.

### The Yatra Blog

> Preview section for three travel blog posts.

### Stats Counter

> A dynamic section highlighting key agency statistics (e.g., travelers, packages).

### Newsletter Signup

> Input form integrated into a dark background section with a decorative pattern.

### Contact

> A detailed contact form area paired with a mock-up map visualization.

### Footer

> Detailed footer providing navigation links and copyright information.

## Layout and Responsiveness

This project is built following a mobile-first philosophy, ensuring readability and usability across all devices.

Main Layout Techniques

CSS Grid (grid-template-columns): Used extensively for the dest-grid, package-cards, and testimonial-grid to ensure content wraps naturally and maintains visual balance across different screen sizes.

CSS Flexbox (display: flex): Used for micro-layouts like the steps and stats sections, and for aligning items in the header and newsletter sections.

object-fit: cover: Applied to all destination and blog images to ensure they fill their container without distortion, maintaining a consistent height (220px).

Sticky Header: The main navigation (<header>) uses position: sticky; to remain visible while scrolling.

Breakpoints Used

The responsiveness is primarily managed by two major media query breakpoints:

Breakpoint

Technique

Purpose

max-width: 768px

Full mobile styling.

Hides the desktop navigation and displays the Hamburger Menu. Converts the steps section from a horizontal row to a vertical column.

max-width: 600px

Small mobile/tablet styling.

Adjusts the stats section to wrap onto two rows (50% width per item) and converts vertical separators to horizontal ones.

min-width: 1000px

Large desktop styling.

Ensures the dest-grid and package-cards maintain a dedicated three-column layout for a professional, spacious appearance on wide screens.

How to Open and View Locally

Since this is a single, self-contained HTML file, viewing it is straightforward:

Save the Code: Save the entire code block provided as a single file named index.html.

Save Images (Crucial): If you are using locally saved images (as discussed), create a folder named images in the same directory as index.html. Place all image files (e.g., goa-beach.jpg, your-hero-image.jpg) inside this folder, matching the paths specified in the code.

Open in Browser: Double-click the index.html file. It will automatically open in your default web browser (Chrome, Firefox, etc.).

Note: This file does not require any build tools or server setup to run.

Visual Overview (Screenshots)

To showcase your project's appearance and responsiveness, you can add screenshots directly into this README.md file using standard Markdown image syntax.

Steps to Add Screenshots:

Create a Folder: Create a new folder (e.g., screenshots) in the root of your project directory.

Save Images: Place your captured screenshots (e.g., desktop-view.png, mobile-menu.png) into this folder.

Use Markdown: Insert the image links using the following format:
