# Basic HTML Website Documentation

This project is a simple HTML-based portfolio website with no external libraries or advanced styling. The layout and structure are implemented using basic HTML and CSS techniques. Below is a breakdown of the project components and structure.

## Table of Contents
- [Structure](#structure)
- [HTML Overview](#html-overview)
- [CSS Overview](#css-overview)
- [Navigation](#navigation)
- [Sections](#sections)
  - [Top Page](#top-page)
  - [Middle Page](#middle-page)
  - [Reviews](#reviews)
  - [Footer](#footer)

## Structure

The website structure consists of the following sections:
- A **Top Page** with navigation and a hero section.
- A **Middle Page** that contains project details, work experience, open-source contributions, and education.
- A **Reviews** section to showcase testimonials.
- A **Footer** with copyright information.

## HTML Overview

The HTML code is divided into semantic sections for clarity and structure:
- `<header>`: Contains the navigation menu and logo.
- `<section>`: Encapsulates distinct parts of the content, including the hero, projects, work experience, open source contributions, education, and reviews.

## CSS Overview

### Global Styles
- The `*` selector is used to reset margin, padding, and box-sizing to ensure consistent styling across browsers.
- The `body` is flex-centered, with a margin to keep the content visually appealing.
- The primary font used is `"Comic Sans MS"`, giving the site a playful and informal look.

### Layout & Design
- The container div (`#container`) is styled to be 70% of the screen width with a solid border.
- Flexbox and CSS Grid are used to layout elements like the navigation bar and content blocks.
- A simple grid layout is applied to the middle page using `grid-template-columns` for a responsive design.

## Navigation

The navigation links allow users to navigate between different sections of the site:
- **Home**
- **Projects**
- **Articles**
- **Contacts**

Each of these links uses the `<a>` tag with a hover effect that changes the link color.

## Sections

### Top Page

This section consists of:
- A header with the **logo** and **navigation** bar.
- A **hero section** with a main title (`<h1>`) and a description (`<p>`).

```html
<section id="topPage">
    <header>
        <div id="logo">
            <span class="logoSharp"></span>
            <span>Thierry DOHOUIN</span>
        </div>
        <nav>
            <ul>
                <li><a href="/homePage.html">Home</a></li>
                <li>/</li>
                <li><a href="/projects.html">Projects</a></li>
                <li>/</li>
                <li><a href="/articles.html">Articles</a></li>
                <li>/</li>
                <li><a href="/contacts.html">Contacts</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>FrontEnd Developer</h1>
        <p>html only with proper layout, no styling</p>
    </section>
</section>
