# Lesson 8. Preprocessors: SCSS

**[Presentation](presentations/presentation-8-scss.pdf)**<br />
<!-- **[Manual](manuals/manual-8-preprocessors.pdf)**<br />  -->

<!-- **Part 1:** <br /> 
**[Group 1 video](https://drive.google.com/file/d/1hBCsdvxIbdhecLFR4KcMBZteI8-4MiG-/view)**<br />
**[Group 2 video](https://drive.google.com/file/d/1prSqmuVYZK6fx991ONGvsKFB60cObMgS/view)**<br />

 **Part 2:** <br />
**[Group 1 video](https://drive.google.com/file/d/149SD52OFdwtjEThymFBr-QFRL2M2ss19/view)**<br />
**[Group 2 video](https://drive.google.com/file/d/1thzc5jSf31wwtRRH4fnxz0JJQ5vlj96I/view)**<br />  -->

# Homework

1. **Split your styles into multiple SCSS files**
- One BEM block = one SCSS file
- Use separate files for:
    - variables
    - mixins
    - base styles
    - components
2. **Move repeated values into SCSS variables**
3. **Use SCSS nesting**

## Criteria 

❤️ **SCSS preprocessor is used** <br />
❤️ **Styles are split into components** <br />
❤️ **SCSS variables are used for colors and fonts** <br />
💛 **Mixins are used where appropriate** <br />
💛 **No magic numbers (all values are explained or reusable)** <br />

# Demos 

## Mixins 

🟢 [SCSS Mixin Button Variations (CodePen by glitchworker)](https://codepen.io/glitchworker/pen/OMGqKG?editors=1100):  
A neat example of using mixins to create different button styles with minimal code repetition.

🟢 [Responsive Typography Mixin (CodePen by Reissue1125)](https://codepen.io/Reissue1125/pen/ZqzOJK?editors=1100):  
Shows how to build a mixin for fluid, responsive typography across breakpoints.

🟢 [SASS Grid with Mixins (CodePen by irvingarmenta)](https://codepen.io/irvingarmenta/pen/zNyqBY?editors=1100):  
Demonstrates how to create a flexible grid system using SCSS mixins.

🟢 [Breakpoint Mixins (CodePen by striketype)](https://codepen.io/striketype/pen/RwVrNvQ?editors=1100):  
A clean implementation of breakpoint-based mixins for responsive layout control.

🟢 [Mixins for Card UI (CodePen by creativeo)](https://codepen.io/creativeo/pen/dyQrvOZ?editors=1100):  
Uses SCSS mixins to define and reuse styles across different card components.

🟢 [SCSS Mixins for Box Shadows (CodePen by xxx41)](https://codepen.io/xxx41/pen/BVbRbx?editors=1100):  
Shows how to simplify repetitive shadow effects using mixins with parameters.

🟢 [Media Query Mixins (CodePen by draft123)](https://codepen.io/draft123/pen/OJPwLwg?editors=1100):  
Illustrates how to define and apply media query mixins for a cleaner responsive design workflow.

🟢 [Button States with Mixins (CodePen by arch_ira)](https://codepen.io/arch_ira/pen/ZjELjx?editors=1100):  
A practical example of styling button states (hover, active) using mixins.

🟢 [SASS Utility Mixins (CodePen by bsx)](https://codepen.io/bsx/pen/vYKNWYN?editors=1100):  
Includes utility-style mixins for margins, paddings, and more, promoting reusability.

🟢 [Basic Mixin Usage (CodePen by lethrgio)](https://codepen.io/lethrgio/pen/NWWPZmB):  
A simple intro to how mixins work in SCSS with examples for text styles.

🟢 [Grid System with Mixin Looping (CodePen by nguyenthanhdong)](https://codepen.io/nguyenthanhdong/pen/YzVLPBB?editors=1100):  
Combines `@for` loop and mixins to generate grid classes automatically.

🟢 [Reusable Button Styles with Mixins (CodePen by marek-coder-ui)](https://codepen.io/marek-coder-ui/pen/LYBZZMO?editors=1100):  
Mixins are used here to define consistent button styles with different color schemes.

🟢 [SCSS Mixins for Theme Variables (CodePen by ylaana)](https://codepen.io/ylaana/pen/gOzqVBO?editors=1100):  
Demonstrates using mixins together with variables to manage theming and color logic.

🟢 [Styled Inputs with Mixins (CodePen by Hasan G. KÜSEL)](https://codepen.io/Hasan-G-KSEL/pen/ExGZZVg?editors=1100):  
Applies mixins to inputs and form fields for consistent spacing and borders.

# Additional Materials

## Courses 

**[Learn Sass: Mixins and Parent Selector (Codecademy)](https://www.codecademy.com/learn/learn-sass-mixins-and-the-parent-selector)**: A course dedicated to advanced features of the Sass preprocessor, including using mixins and the parent selector.

**[Learn Sass: Best Practices (Codecademy)](https://www.codecademy.com/learn/learn-sass-best-practices)**: A course that teaches best practices and techniques for working with Sass, improving the structure and organization of styles.

**[Learn Sass: Functions and Operations (Codecademy)](https://www.codecademy.com/learn/learn-sass-functions-and-operations)**: Learning functions and operations in Sass, allowing for the creation of more dynamic and adaptive styles.

**[Learn Sass: Fundamentals (Codecademy)](https://www.codecademy.com/learn/learn-sass-fundamentals)**: An introductory course on Sass, covering the basics of this powerful CSS preprocessor.

**[Learn Sass (Codecademy)](https://www.codecademy.com/learn/learn-sass)**: A comprehensive course on Sass, covering all aspects of working with this preprocessor, from basics to advanced techniques.

**[Store Data with Sass Variables (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/store-data-with-sass-variables)**:  
An introduction to using variables in Sass for storing values like colors, fonts, and sizes for more maintainable and scalable stylesheets.

**[Nest CSS with Sass (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/nest-css-with-sass)**:  
Learn how to nest selectors in Sass to reflect the structure of your HTML and keep related styles organized.

**[Create Reusable CSS with Mixins (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/create-reusable-css-with-mixins)**:  
Understand how to use mixins in Sass to avoid code repetition and create flexible, reusable style patterns.

**[Use @if and @else to Add Logic to Your Styles (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-if-and-else-to-add-logic-to-your-styles)**:  
A guide to adding conditional logic to your Sass styles using `@if` and `@else` statements for more dynamic CSS.

**[Use @for to Create a Sass Loop (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-for-to-create-a-sass-loop)**:  
Learn how to use `@for` loops in Sass to generate repetitive styles automatically and reduce manual code duplication.

**[Use @each to Map Over Items in a List (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-each-to-map-over-items-in-a-list)**:  
Explore how to loop over a list of values with `@each` to apply styles dynamically based on a set of predefined items.

**[Apply a Style Until a Condition is Met with @while (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/apply-a-style-until-a-condition-is-met-with-while)**:  
Use `@while` loops in Sass to repeatedly apply styles as long as a given condition remains true.

**[Split Your Styles into Smaller Chunks with Partials (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/split-your-styles-into-smaller-chunks-with-partials)**:  
Learn how to organize your SCSS by splitting your styles into partial files and importing them into a main stylesheet.

**[Extend One Set of CSS Styles to Another Element (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/extend-one-set-of-css-styles-to-another-element)**:  
Discover how to use `@extend` to share and reuse styles between selectors without repeating the same code.

[Learn CSS: Variables and Functions](https://www.codecademy.com/learn/learn-css-variables-and-functions): An online course on learning CSS variables and functions to create more dynamic and adaptive styles.

## 🧱 **CSS Preprocessors (Overview & Docs)**

**[What are CSS Preprocessors? (Raygun)](https://raygun.com/blog/css-preprocessors-examples/)**  
Intro article with examples of Sass, LESS, and Stylus, comparing syntax and use cases.

**[How to Use CSS Preprocessors (Medium)](https://medium.com/@aicontentpace/how-to-use-css-preprocessors-953ebc521e94)**  
A beginner-friendly guide on why and how to use preprocessors like Sass.

**[Sass Docs](https://sass-lang.com/)**  
The official Sass documentation — the go-to source for all features.

**[LESS Docs](http://lesscss.org/)**  
Official documentation for the LESS preprocessor.

**[Stylus Docs](http://stylus-lang.com/)**  
Official docs for Stylus — known for its minimal syntax.

### 💡 **Sass Features & Logic**

**[How to Write Loops with Preprocessors (CSS-Tricks)](https://css-tricks.com/how-to-write-loops-with-preprocessors/)**  
Examples of `@for`, `@each`, and `@while` in Sass.

**[The Main Features of Sass (Dev.to)](https://dev.to/timothyrobards/the-main-features-of-sass-47k2)**  
Overview of core Sass features: variables, nesting, mixins, functions, inheritance.

### 🧱 **BEM + Preprocessors**

**[BEM and SASS? What Are They And How To Use Them (PullRequest Blog)](https://www.pullrequest.com/blog/bem-and-sass-whats-the-difference-and-how-to-use-them/)**  
An overview of BEM methodology and the SASS preprocessor — explaining the difference between them and how to use both together to write cleaner, more maintainable CSS.

## 🎨 **CSS Custom Properties**

**[Using CSS Custom Properties (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties)**  
The official MDN guide — everything you need to know about `--vars`.

**[A Complete Guide to Custom Properties (CSS-Tricks)](https://css-tricks.com/a-complete-guide-to-custom-properties/)**  
Deep dive with examples on theming, dynamic styles, fallbacks, and more.

**[7 Uses for CSS Custom Properties (CSS-IRL)](https://css-irl.info/7-uses-for-css-custom-properties/)**  
A list of creative, real-world use cases for CSS variables.

### 🧠 **Advanced CSS Logic (Inline Conditionals)**

**[CSS Conditionals (Lea Verou, part 1)](https://lea.verou.me/blog/2024/css-conditionals/)**  
Introduction to new inline conditionals in CSS — like `@if`, but natively.

**[CSS Conditionals Now (Lea Verou, part 2)](https://lea.verou.me/blog/2024/css-conditionals-now/)**  
Examples of what’s possible with the latest conditional CSS syntax.

### ⚖️ **CSS Custom Properties vs SCSS Variables**

**[CSS Custom Properties vs SCSS Variables (Frontendly)](https://frontendly.io/blog/css-custom-properties/)**  
Great breakdown comparing runtime (CSS) vs compile-time (SCSS) variables.

🟢 [7 Uses for CSS Custom Properties](https://css-irl.info/7-uses-for-css-custom-properties/): Highlights seven practical ways to use CSS custom properties in development.

[Relative Grid Items with CSS Variables](https://css-irl.info/relative-grid-tracks/): Explores the use of CSS variables to create adaptive grid elements.

[Super-Powered Grid Components with CSS Custom Properties](https://css-tricks.com/super-power-grid-components-with-css-custom-properties/): Shows how to create powerful grid components using CSS variables.

🟢 [Practical Tips for Working with CSS Variables](https://css-irl.info/practical-tips-css-variables/): Offers practical tips for working with CSS variables.

[Super-Powered Layouts with CSS Variables + CSS Grid](https://css-irl.info/super-powered-layouts/): Combining CSS variables and grid to create dynamic layouts.

🟢 [Global and Component Style Settings with CSS Variables](https://www.sarasoueidan.com/blog/style-settings-with-css-variables/): A guide to using CSS variables for setting styles at both global and component levels.

🟢 [A Complete Guide to Custom Properties](https://css-tricks.com/a-complete-guide-to-custom-properties/): A comprehensive guide to using custom properties in CSS.

🟢 [A User's Guide to CSS Variables](https://increment.com/frontend/a-users-guide-to-css-variables/): A detailed user guide on CSS variables, their features, and ways to apply them.

[Proportional Resizing with CSS Variables](https://ishadeed.com/snippet/proportional-resizing-css-variables): Using CSS variables for proportional resizing of elements.

🟢 [Practical CSS Variables](https://ishadeed.com/article/practical-css-variables): A practical approach to using CSS variables in web development.

<!-- [Start Using CSS Custom Properties](https://www.smashingmagazine.com/2017/04/start-using-css-custom-properties/): An introduction to using custom properties in CSS and their benefits. -->

<!-- [CSS Custom Properties: A Strategy Guide](https://www.smashingmagazine.com/2018/05/css-custom-properties-strategy-guide/): A strategic guide to applying CSS variables in projects. -->

🟢 [Declaring CSS Variables](https://www.samanthaming.com/tidbits/4-declaring-css-variables/): Explains how to declare and use CSS variables.

[A Complete Guide to CSS Variables](https://webdesign.tutsplus.com/the-complete-guide-to-using-css-variables--CRS-201043c): A complete guide to using variables in CSS.

[CSS Vars 101](https://ishadeed.com/article/css-vars-101): Basics of working with CSS variables for beginners.

## 🧬 **CSS Nesting**

**[Using CSS Nesting (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_nesting/Using_CSS_nesting)**  
Official browser support and syntax guide.

**[CSS Nesting (Chrome Developers)](https://developer.chrome.com/docs/css-ui/css-nesting)**  
Overview of native CSS nesting, limitations, and best practices.

**[CSS Nesting Explained (Pivale)](https://www.pivale.co/blog/css-nesting)**  
Beginner-friendly explanation of how native CSS nesting works.

**[CSS Nesting (Ahmad Shadeed)](https://ishadeed.com/article/css-nesting/)**  
Detailed guide with examples and thoughts on real use cases.

**[CSS Nesting & UX (Ahmad Shadeed)](https://ishadeed.com/article/css-nesting-ux/)**  
How CSS nesting can affect user experience and maintainability.

## ❗ **Magic Numbers in CSS**

**[Magic Numbers in CSS (CSS-Tricks)](https://css-tricks.com/magic-numbers-in-css/)**  
A classic article explaining what magic numbers are, why they’re problematic, and how to avoid them with better layout techniques and thinking in context.

**[Magic Numbers in CSS (Code Readability)](https://www.codereadability.com/magic-numbers-in-css/)**  
A practical look at magic numbers in everyday CSS and how they hurt maintainability. Includes common causes and how to refactor your code to remove them.

## New CSS features

### 📏 **Container Queries**

**[CSS Container State Queries (Ahmad Shadeed)](https://ishadeed.com/article/css-state-queries/)**  
What container state queries are and how they can improve responsive design.

**[Complete Guide to Container Queries (Ahmad Shadeed)](https://ishadeed.com/article/css-container-query-guide/)**  
A full guide to working with `@container` rules and responsive components.

### 🔍 **`:has()` Pseudo-Class**

**[Guide to :has() (Ahmad Shadeed)](https://ishadeed.com/article/css-has-guide/)**  
Learn how the powerful `:has()` pseudo-class can replace JavaScript for some interactivity.

