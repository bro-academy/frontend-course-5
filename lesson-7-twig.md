# Lesson 6. Twig

**[Presentation 1](presentations/presentation-7-twig.pdf)**<br />
<!-- **[Manual](manuals/manual-8-twig.pdf)**<br />  -->

<!-- **Part 1: Bundlers** <br /> 
**[Group 1 video](https://drive.google.com/file/d/13g9c_Y1nAfJNX3lQchftC__sRSakatnw/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/14EYym_Eg5LRRFxnx80nVRvoYIiwMafGz/view?usp=sharing)**<br />

**Part 2: Templating** <br />
**[Group 1 video](https://drive.google.com/file/d/13mKjLyg4L1_QlAwEC5E000fvellJZpUQ/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1XcdMFg4ms5o1UeBWwBnT8S2LnnKThdG1/view?usp=sharing)**<br />  -->

# Homework
1. Set up the templates folder structure:
- `src/templates/` → Main folder for all `.twig` files.
- `src/templates/layouts/` → Base structure for pages (`base.twig`).
- `src/pages/` → Separate folder for each page (`index.twig`, `about.twig`, etc.).
- `src/templates/partials/` → Components (e.g., header, footer, product cards).
- `src/data/common.json` → Store dynamic data for all pages
- `src/data/index.json` → Store dynamic data for specific page

2. Implement the Twig templating system:
- Create a base template (`base.twig`) with `{% block %}` sections for content.
- Use `{% extends %}` to inherit the layout structure.
- Include reusable components (header, footer) with `{% include %}`.
- Work with variables and loops (`{% for %}`, `{% if %}`) to generate dynamic content. 

## Criteria 

❤️ **The project is structured using Twig templates**  
   - **Layouts (`layouts/`)** contain the base structure (`base.twig`).  
   - **Partials (`partials/`)** store reusable components (header, footer, product cards, etc.).  
   - **Text content is moved to `data.json`** for better management of dynamic data.  

💛 **Loops, variables, and dynamic data are used in Twig**  
   - **Variables are created** using `{% set %}` or fetched from `data.json`.  
   - **Loops (`{% for %}`)** are used to generate lists of elements (e.g., products, reviews).  
   - **Conditional statements (`{% if %}`)** are used to check for data presence or to display different blocks.  

# Additional Materials

**[Benefits of Template Engines – PDFBolt (Top HTML Template Engines article)](https://pdfbolt.com/blog/html-template-engines)**  
A **comprehensive overview** of key benefits—including separation of concerns, code reusability, automatic HTML escaping (security), productivity gains, and collaboration facilitation across teams.

## Twig 

**[Twig Templating (Official Docs)](https://twig.symfony.com/doc/3.x/)**  
A **beginner’s guide** to **Twig syntax**, variables, loops, and integrating it with PHP projects.

**[Getting Started with Twig in PHP Projects – Dev.to](https://dev.to/dedoussis/getting-started-with-twig-in-php-projects-2do2)**  
A **step-by-step tutorial** on installing Twig via Composer and using it in a plain PHP environment without a framework.

**[Twig Template Engine Crash Course (YouTube)](https://www.youtube.com/watch?v=U3jZ3V2lRwU)**  
A **video walkthrough** for beginners to understand the basics of Twig and how to build a simple templated site.

**[Templating Engines Explained – SitePoint](https://www.sitepoint.com/templating-engines/)**  
A **general introduction** to **templating engines**, why they are used, and how they help separate concerns in web development.

**[Twig in 5 Minutes – SymfonyCasts](https://symfonycasts.com/screencast/twig)**  
A **quick video-based intro** to the Twig engine, syntax, and usage, part of the official Symfony learning platform (free intro).

**[Twig vs Blade vs Smarty – Kinsta Blog](https://kinsta.com/blog/php-templating-engines/)**  
A **comparative overview** of popular PHP templating engines to help you understand Twig’s strengths and use cases.

**[TwigFiddle – Online Twig Sandbox](https://twigfiddle.com/)**  
An **interactive playground** to experiment with Twig syntax and templates directly in the browser.

## Json

**[JSON (MDN Web Docs)](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)**  
A **beginner-friendly explanation** of what JSON is, how it relates to JavaScript objects, and how to work with it in practice.

**[Introduction to JSON – W3Schools](https://www.w3schools.com/js/js_json_intro.asp)**  
A **simple, interactive guide** to learning JSON syntax, structure, and basic use cases with examples.

**[What is JSON? – freeCodeCamp](https://www.freecodecamp.org/news/what-is-json-a-json-tutorial-for-beginners/)**  
A **plain English tutorial** covering what JSON is, where it’s used, and how to read and write JSON data.

**[JSON Tutorial for Beginners (YouTube – Programming with Mosh)](https://www.youtube.com/watch?v=9NRY5r0b3oI)**  
A **clear video tutorial** that explains JSON structure, syntax, and how it's used in real-world applications.

**[JSON Formatter & Validator](https://jsonformatter.org/)**  
An **online tool** to format, validate, and visualize JSON data — great for learning and debugging.

**[JSON Syntax – JSON.org](https://www.json.org/json-en.html)**  
The **official reference** for JSON structure and grammar with helpful visual diagrams.

**[Working with JSON in JavaScript – DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-work-with-json-in-javascript)**  
A **developer-focused tutorial** on parsing and generating JSON using JavaScript.

**[JSONPlaceholder – Fake Online REST API](https://jsonplaceholder.typicode.com/)**  
A **free mock API** that serves JSON data — ideal for practicing how to fetch and handle JSON responses.

**[Introduction to APIs and JSON (Codecademy)](https://www.codecademy.com/learn/learn-intermediate-javascript/modules/requests-with-fetch/cheatsheet)**  
Part of a course that offers a **practical look** at using JSON when working with APIs using `fetch()` in JavaScript.




