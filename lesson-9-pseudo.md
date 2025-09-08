# Lesson 9. CSS Pseudo-elementa and pseudo-classes

**[Presentation](presentations/presentation-9-pseudo.pdf)**<br />
**[Manual](manuals/manual-9-pseudo.pdf)**<br />

# Homework

1. **Apply all states for links and buttons:** `hover`, `active`, `focus`, according to the UI kit.

- Use pseudo-elements where necessary.

## Criteria CSS+

❤️ **Links and buttons must respond to :hover, :active и :focus.**
If not specified in the design, you can use underline, color change, etc.

❤️ **Interactions( :hover, :active и :focus) should not change the document flow.**
Adjacent elements should not change their position and size unless specified in the style guide.

## Additional Courses:
Complete one of the following courses to reinforce your understanding of the theory:
1. **[Scaler: MODULE 6. Intermediate in CSS. Pseudo Element in CSS](https://www.scaler.com/topics/css/)**
2. **[freeCodeCamp: Learn More About CSS Pseudo Selectors by Building a Balance Sheet](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-more-about-css-pseudo-selectors-by-building-a-balance-sheet/step-1)**
  In this course, you'll build a balance sheet using pseudo selectors. You'll learn how to change the style of an element when you hover over it with your mouse, and trigger other events on your webpage.

# Demo 

## Pseudo Classes 

🟢 [Pseudo Class Selectors](https://codepen.io/russweakley/pen/PoQjomE): An overview and examples of using pseudo class selectors to style HTML elements.

🟢 [first-child](https://codepen.io/russweakley/pen/ZErmEKo): A demonstration of using the `:first-child` selector to style the first child element.

🟢 [last-child](https://codepen.io/russweakley/pen/poaYzOX): An example of using the `:last-child` selector to style the last child element.

🟢 [only-child](https://codepen.io/russweakley/pen/yLvwBQB): Using the `:only-child` selector to style elements that are the sole children in their container.

🟢 [empty](https://codepen.io/russweakley/pen/ZErPzZG): Examples of using the `:empty` selector to select and style empty elements.

🟢 [nth-child](https://codepen.io/russweakley/pen/XWZGrLK): Illustrating the use of the `:nth-child()` selector to style elements based on their ordinal number.

🟢 [nth-last-child](https://codepen.io/russweakley/pen/XWZGrvK): Demonstrating the `:nth-last-child()` selector, which allows styling elements starting from the last one.

## Lists

🟢 **[CSS Counters](http://russmaxdesign.github.io/html-css-tests/sample-counter/01.htm)**: Illustrates how CSS counters can be used to create numbered lists, sections, or other elements that automatically count their items.

**[List Style Position](https://codepen.io/michellebarker/pen/gOeOmje)**: Demonstrates how the `list-style-position` property affects the position of list markers relative to the content.

<!-- **[Alternating List](https://codepen.io/michellebarker/pen/wvmvgPg)**: Shows how to create a list with alternating element styles for better visual perception. -->

**[Reversed and Split List](https://codepen.io/michellebarker/pen/abqrXpP)**: An example of creating a list with reversed order elements and splitting them into parts.

**[::Marker](https://codepen.io/michellebarker/pen/BaYeVBK)**: Using the `::marker` pseudo-element to customize list markers without adding extra code.

<!-- **[List Bullets with ::Before](https://codepen.io/michellebarker/details/qBxGyWO)**: An example of using the `::before` pseudo-element to create custom list markers. -->

<!-- **[Custom Counters with @Counter-Style](https://codepen.io/michellebarker/pen/zYRQjap)**: Shows how to create custom counters for lists using `@counter-style`. -->

<!-- **[Animating ::Marker Gradient](https://codepen.io/michellebarker/pen/wvyNGOZ)**: A demonstration of animating a list marker gradient, works only in Chrome. -->


# Additional materials

## Hover, focus, active

🟢 **[Hover Effects in CSS](https://www.scaler.com/topics/hover-css/)**: This article on Scaler presents various methods of creating hover effects in CSS. You will learn different techniques and tricks that will help you create interesting and attractive animations and effects when hovering the mouse cursor.

🟢 **[CSS Hover Effects for Inline Links](https://webdesign.tutsplus.com/css-hover-effects-for-inline-links--cms-37210t)**: This article on Tuts+ discusses creating hover effects for inline links in CSS. The author presents various methods and techniques for styling links to make them more interactive and attractive for users.

🟢 **[Scale with Pseudo-elements](https://www.joshwcomeau.com/snippets/html/scale-with-pseudoelements/)**: This tutorial on JoshWComeau provides a guide to scaling elements with pseudo-elements in HTML and CSS. You will learn how to use pseudo-elements to create scaling and transformation effects on elements in your web project.

**[Style focus](https://web.dev/articles/style-focus?hl=en)**: This article on web.dev provides a guide on styling focus in web development. You will learn different ways to style the focus of elements to make your interface more accessible and user-friendly.

## Pseudoelements / Pseudoclasses 

🟢 [An Ultimate Guide to CSS Pseudo-Classes and Pseudo-Elements](https://www.smashingmagazine.com/2016/05/an-ultimate-guide-to-css-pseudo-classes-and-pseudo-elements/): An exhaustive guide on pseudoclasses and pseudoelements, helping to understand and effectively apply them in CSS.

🟢 [Unusual Use Cases for Pseudo-Elements](https://ishadeed.com/article/unusual-use-cases-pseudo-elements): Explores unusual and creative ways to use pseudoelements in CSS, expanding the boundaries of conventional usage.

🟢 [CSS Empty](https://ishadeed.com/article/css-empty): Provides an in-depth overview and examples of using the `:empty` selector in CSS to handle empty elements.

🟢 [Conditional CSS with `:has` and `:nth-last-child`](https://ishadeed.com/article/conditional-css-has-nth-last-child): Explores conditional CSS application using the `:has` and `:nth-last-child` pseudoclasses, offering creative ways to style elements.

🟢 [Reducing the Need for Pseudo-Elements](https://www.smashingmagazine.com/2021/09/reducing-need-pseudo-elements/): Discusses how to reduce the need for pseudoelements by using modern CSS techniques.

🟢 [CSS `:not` Selector](https://www.samanthaming.com/tidbits/46-css-not-selector/): Overview and examples of using the `:not` selector in CSS to exclude specific elements from styling.

🟢 [nth-child tester](https://css-tricks.com/examples/nth-child-tester/): A tool to help test if your `nth-child` selector is working correctly.

[Hide and Debug Empty Elements with CSS](https://css-irl.info/hide-and-debug-empty-elements-with-css/): Explains how to hide and debug empty elements using CSS, making debugging more convenient.

[Demystifying CSS Pseudo-Classes: `:nth-child` vs. `:nth-of-type`](https://webdesign.tutsplus.com/demystifying-css-pseudo-classes-nth-child-vs-nth-of-type--cms-34221t): Clarifies the difference between the pseudoclasses `:nth-child` and `:nth-of-type`, offering insights into their functionality and best practices.

[CSS-Only Child](https://www.samanthaming.com/tidbits/64-css-only-child/): Discusses using the `:only-child` selector in CSS to style elements that are the sole children of their parents.

[CSS Empty Selector](https://www.samanthaming.com/tidbits/72-css-empty-selector/): Explains how and why to use the `:empty` selector to style empty elements in CSS.

[A Guide to Supported Modern CSS Pseudo-Class Selectors](https://smashingmagazine.com/2021/04/guide-supported-modern-css-pseudo-class-selectors/): Provides a guide to modern CSS pseudoclasses supported in current browser versions, with examples and usage tips.

[New CSS Functional Pseudo-Class Selectors `:is()` and `:where()`](https://web.dev/articles/css-is-and-where?hl=en): Introduces the new functional pseudoclasses `:is()` and `:where()`, simplifying the writing of cleaner and less repetitive code.

## List Styles

🟢 **[CSS Counters on iShadeed](https://ishadeed.com/article/css-counters)**: A guide to using CSS counters for numbering elements, useful for creating ordered lists without using the `<ol>` tag.

🟢 **[Creative List Styling](https://web.dev/articles/creative-list-styling)**: This article offers ideas and methods for creative list styling in HTML, using CSS to create visually appealing and functional designs.

🟢 [Custom Bullets with CSS ::marker](https://web.dev/articles/css-marker-pseudo-element?hl=en): A guide to creating custom list markers using the CSS ::marker pseudoelement.

🟢 [Quick Tip: Using CSS Counters to Style Incremental Elements](https://webdesign.tutsplus.com/quick-tip-using-css-counters-to-style-incremental-elements--cms-23497t): Tips on using CSS counters to style incremental elements.

🟢 [CSS Counter](https://www.samanthaming.com/tidbits/53-css-counter/): A detailed explanation of working with CSS counters to create numbered lists.

[Centered List Markers](https://css-tricks.com/video-screencasts/202-centered-list-markers/): A video tutorial on centering list markers using CSS.

[Inside Aligned Lists](https://css-tricks.com/video-screencasts/184-inside-aligned-lists/): A video tutorial on aligning lists and their markers inside elements.