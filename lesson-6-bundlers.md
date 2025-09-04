# Lesson 6. The build 

**[Presentation 1](presentations/presentation-6-build.pdf)**<br />

<!-- **Part 1: Bundlers** <br /> 
**[Group 1 video](https://drive.google.com/file/d/13g9c_Y1nAfJNX3lQchftC__sRSakatnw/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/14EYym_Eg5LRRFxnx80nVRvoYIiwMafGz/view?usp=sharing)**<br />

**Part 2: Templating** <br />
**[Group 1 video](https://drive.google.com/file/d/13mKjLyg4L1_QlAwEC5E000fvellJZpUQ/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1XcdMFg4ms5o1UeBWwBnT8S2LnnKThdG1/view?usp=sharing)**<br />  -->

# Homework
1. Copy the necessary the build configuration files to your project.
2. Organize your project files:
- Copy the styles from your existing CSS file and place them in `src/styles/style.scss`.

## Criteria 

❤️ **The build is used**

❤️ **Folders dist and node_modules should not be in the GitHub repository**
   - The `.gitignore` file is configured to exclude **automatically generated build files**.
  
❤️ **The project builds correctly**
   - After running `npm run build` or `npm run dev`, the project should build **without critical errors**.
   - The final files should be correctly placed in `dist/` **without manual intervention**.

❤️ **No red errors in the console during the build process**
   - The console should not show **red error messages (`error`)**.
   - All dependencies should be installed, and plugins should be correctly configured.

💛 **No warnings in the console during the build process**
   - The console should not show **yellow warning messages**, such as **package incompatibilities or missing dependencies**.
   - The code should follow best practices and be validated with linters (`stylelint`, `eslint`, `prettier`).

# Additional Materials

**[Learn Build Tools (Codecademy)](https://www.codecademy.com/learn/learn-build-tools)**: A course on build tools in modern web development, including Webpack and other systems.

<!-- ## **📌 Nunjucks Basics**
- **[Nunjucks Templating Language (Mozilla)](https://mozilla.github.io/nunjucks/)**  
  Official **Nunjucks** documentation by Mozilla. Covers key concepts such as template inheritance, blocks, includes, variables, and filters.  

- **[Killer Features of Nunjucks (CSS-Tricks)](https://css-tricks.com/killer-features-of-nunjucks/)**  
  A breakdown of **Nunjucks' powerful features**, including `{% block %}`, `{% include %}`, `{% extends %}`, filters, and macros.  

- **[Building a Static Site with Nunjucks (Smashing Magazine)](https://www.smashingmagazine.com/2018/03/static-site-with-nunjucks/)**  
  A practical guide on **using Gulp and Nunjucks** to create a static website.  

- **[Nunjucks Video Course (YouTube Playlist)](https://www.youtube.com/playlist?list=PL_wra5HCV9SlMXNY8PSbht5fbTmAtCccI)**  
  A series of **video tutorials** explaining Nunjucks step by step.  

- **[Getting Started with Nunjucks in Eleventy (Learn Eleventy From Scratch)](https://learneleventyfromscratch.com/lesson/3.html#getting-started-with-nunjucks)**  
  A guide on how **Nunjucks integrates with Eleventy**, a modern static site generator.   -->

<!-- ---

## **⚡ Gulp & Build Automation**
- **[Gulp – A Toolkit to Automate Your Workflow (Medium)](https://medium.com/@niranjanky14/gulp-a-toolkit-to-automate-and-enhance-your-workflow-ec3aa0a101bf)**  
  Introduction to **Gulp**, its advantages, installation process, and essential tasks like compiling SCSS, processing Nunjucks, and live reloading.  

- **[Official Gulp Documentation](https://gulpjs.com/)**  
  The complete **Gulp.js** reference, including examples, API documentation, and setup guides.  

- **[Gulp for Beginners (CSS-Tricks)](https://css-tricks.com/gulp-for-beginners/)**  
  A beginner-friendly tutorial covering **the basics of Gulp**, how to set up `gulpfile.js`, and automate tasks.   -->

---

## **📦 Understanding npm & package.json**
- **[Node.js & npm (Official Site)](https://nodejs.org/en/learn/getting-started/an-introduction-to-the-npm-package-manager)**  
  A **beginner’s guide** to **npm**, package management, and working with dependencies.  

- **[The Basics of package.json (Nodesource)](https://nodesource.com/blog/the-basics-of-package-json)**  
  Explanation of **package.json structure**, including dependencies, scripts, and configurations.  

- **[What is package.json and How to Use It? (HeyNode)](https://heynode.com/tutorial/what-packagejson/)**  
  A detailed overview of **key fields in package.json**, such as `dependencies`, `devDependencies`, and `scripts`.  

- **[Difference Between Dependencies, devDependencies, and peerDependencies (GeeksForGeeks)](https://www.geeksforgeeks.org/difference-between-dependencies-devdependencies-and-peerdependencies/)**  
  How to manage **different types of dependencies** in npm projects.  

- **[Absolute Beginner’s Guide to Using npm (Nodesource)](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm)**  
  A step-by-step introduction to **npm**, including installation, commands, and updating packages.  

- **[A Complete Beginner’s Guide to npm (CSS-Tricks)](https://css-tricks.com/a-complete-beginners-guide-to-npm/)**  
  An in-depth article on **npm features, package management, and best practices**.  

---

## **🔗 Additional Resources**
- **[Source Maps – What They Are and How They Work (Web.dev)](https://web.dev/articles/source-maps)**  
  A detailed guide on **source maps**, explaining how they help **debug minified code**.  

- **[Volta – A Node.js Version Manager](https://docs.volta.sh/guide/getting-started)**  
  A tool for **managing Node.js versions** and dependencies in projects.  

- **[Node.js vs. npm – What’s the Difference? (HostAdvice)](https://hostadvice.com/blog/web-hosting/node-js/node-js-vs-npm/)**  
  Understanding the difference between **Node.js and npm**, and why both are essential in web development.  

Вот твой список материалов про **Vite для новичков**, собранный в формате Markdown с описаниями на английском языке:

---

## Vite Resources

* [**Vite: Getting Started – vite.dev**](https://vite.dev/guide/) – The official guide to Vite, showing how to create your first project, run a dev server, and build for production. Simple, clear, and ideal for first-time users.

* [**Vite.js: A Beginner’s Guide – Better Stack**](https://betterstack.com/community/guides/scaling-nodejs/vitejs-explained/) – Explains what Vite is, why it's fast, and how to use it step by step with examples and clear explanations.

* [**Getting Started with Vite – GeeksforGeeks**](https://www.geeksforgeeks.org/javascript/getting-started-with-vite/) – Covers the basics of using the Vite CLI, choosing templates, and launching the dev server with minimal effort.

* [**How to Build Web Apps Using Vite – Codecademy**](https://www.codecademy.com/article/building-apps-with-vite) – Describes how to use Vite to build modern web apps, including handling CSS, images, and environment variables.

* [**Intro to Vite (Free Course) – Coursera via Scrimba**](https://www.coursera.org/learn/intro-to-vite) – A short hands-on course for beginners that walks through building a simple Vite app with interactive exercises.

<!-- * [**Lightning Fast Builds with Vite – Vue Mastery**](https://www.vuemastery.com/courses/lightning-fast-builds-with-vite/intro-to-vite/) – A video course demonstrating Vite’s power and speed, especially with Vue.js, but still useful to understand the core concepts. -->

<!-- * [**Why Vite is Fast – vite.dev**](https://vite.dev/guide/why) – Explains the technical reasons behind Vite’s performance: esbuild, ESM-based dev server, and optimized dependency handling. -->

