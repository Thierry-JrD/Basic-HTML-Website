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
```

### Middle Page

The middle page is divided into three main columns:

Projects: A list of recent projects with links.
- **Work Experience**: Details about work experience and open-source contributions.
- **Education**: Information about educational background and courses taken.

```
<section id="middle-page">
    <div class="projects">
        <p class="project-list-el"><a href="#">HTML Only Portfolio</a></p>
        <p class="project-list-el"><a href="#">Calculator</a></p>
        <p class="project-list-el"><a href="#">Quiz App</a></p>
        <p class="project-list-el"><a href="#">Counter Timer</a></p>
        <p class="project-list-el"><a href="#">Product Upcoming Page</a></p>
    </div>

    <div class="wk-exp-op-src">
        <div class="wk-exp">
            <p>Work Experience</p>
            <p>roadmap.sh: Solved all frontend projects.</p>
            <a href="#">Visit my profile</a>
        </div>
        
        <div class="op-src">
            <p>OpenSource Work</p>
            <p>Contributed to 50 opensource projects. Make my own projects with 200 GitHub stars.</p>
            <a href="#">Visit my Github profile</a>
        </div>
    </div>

    <div class="education">
        <p>Education</p>
        <ul>
            <li>Object-Oriented Programming</li>
            <li>Data Structure and Algorithms</li>
            <li>Web Engineering</li>
        </ul>
    </div>
</section>
```

### Reviews

The reviews section highlights feedback from professors:

```
<section id="reviews">
    <p>Reviews from my teachers:</p>
    <div class="reviews-blocks">
        <div class="r-block">
            <p>Thierry Dohouin was a brilliant student, always stood out with his assignments.</p>
            <div>
                <span>Mark Aurel</span>
                <span>Assistant Professor</span>
            </div>
        </div>
    </div>
</section>
```

### Footer

The footer contains a copyright message:

```
<footer>
    <p>ⓒ all right reserved 2025</p>
</footer>
```

### Conclusion
This website demonstrates a simple, clean layout using basic HTML and CSS. It can serve as a base for more complex front-end projects, with options for further customization and styling.

Click here for Demo : 
