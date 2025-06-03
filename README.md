# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). These challenges help me improve my coding skills by building realistic and accessible web interfaces.

For this project, I developed a recipe card for a simple omelet using semantic HTML and modern CSS. I applied the BEM (Block Element Modifier) methodology to maintain clean, scalable code, while ensuring responsiveness and accessibility across devices. The goal was to replicate the original design with precision and to follow best practices for layout, structure, and user experience.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [How to Run Locally](#how-to-run-locally)

### The Challenge

The challenge involved developing a recipe card component using semantic HTML, modern CSS, and a fully responsive and fluid design. The goal was not only to replicate the visual structure, but also to ensure accessibility, consistency, and adherence to web development best practices.

The card was divided into several distinct sections:

- **Image Section:** Showcasing the final dish with appropriate alternative text and accessible `<figure>` / `<figcaption>` markup.
- **Header Section:** Including the recipe title and a short description, styled for prominence and clarity.
- **Preparation Time and Ingredients:** These sections use structured lists and semantic headings, with attention to spacing (padding, margin), list styling, and text hierarchy.
- **Instructions Section:** Implemented as an ordered list, with each step labeled using nested heading tags and paragraph descriptions for clear navigation and screen reader support.
- **Nutrition Table:** A semantic `<table>` displaying nutritional facts, including a caption, proper use of `<thead>`, `<tbody>`, `<th>`, and `<td>`, and scope attributes to enhance accessibility for assistive technologies.

The component’s design adheres to a consistent color scheme (following provided HSL values), typographic scales (based on rem units), and a clean visual rhythm through well-defined spacing and alignment. The layout is responsive, gracefully adapting from desktop to mobile viewports while maintaining readability, hierarchy, and usability.

Every section was carefully styled using the BEM (Block Element Modifier) methodology to promote maintainability, scalability, and clarity in the CSS architecture.

### Screenshot

![Desktop version](./design/desktop-design.jpg)  
_Desktop version of the recipe card._  
The layout features a centered design with generous content width, clear typography, and well-structured spacing. It emphasizes readability and visual balance, making full use of larger screens while maintaining accessibility standards.

![Mobile version](./design/mobile-design.jpg)  
_Mobile version of the recipe card._  
The layout adapts fluidly to smaller viewports, stacking elements vertically with consistent padding and legible text. Despite the reduced space, the interface remains intuitive, visually clean, and fully accessible across devices.

### Links

Below are the links to the project's code repository and the live demo site:

- [Solution on GitHub](https://github.com/OscarE2D/FrontendMentor-recipe-page-main)
- [Live Demo on GitHub Pages](https://oscare2d.github.io/FrontendMentor-recipe-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM (Block Element Modifier) methodology

### What I learned

During the development of this recipe card, I encountered several challenges that led to valuable learning experiences. The most notable takeaways include:

- **Correct application of the BEM methodology:**  
  I learned to implement the BEM (Block, Element, Modifier) methodology consistently in both HTML and CSS. This approach allowed me to clearly identify components without relying excessively on nested selectors, significantly improving the maintainability and scalability of the codebase.

- **Logical and professional CSS organization:**  
  I structured CSS into clearly defined blocks, grouping styles by section in an organized manner. This practice enhanced code readability and simplified future maintenance or feature additions.

- **Semantic and accessible table construction:**  
  I correctly built an HTML table using semantic elements such as `<caption>`, `<thead>`, `<tbody>`, `<th>`, and `<td>`, alongside appropriate `scope` attributes. This ensures better accessibility, especially for screen readers and assistive technologies.

- **Advanced CSS pseudo-elements and properties:**  
  I applied pseudo-elements like `::marker` to customize list markers and used properties such as `text-indent` for better content presentation. Additionally, I improved content structure within `<li>` elements by wrapping text inside elements like `<span>`, `<strong>`, or `<p>` when necessary.

- **Definition and use of CSS variables:**  
  I enhanced visual consistency by defining and reusing CSS custom properties (e.g., `--primary-color`, `--font-size-base`), which simplified styling and maintenance.

- **Responsive and accessible design principles:**  
  I ensured the layout adapts fluidly across devices from mobile to desktop, prioritizing readability and usability. Accessibility considerations included semantic HTML, clear navigation order, and support for users with different abilities.

### Continued development

- **Refining spacing and visual alignment**  
  Fine-tune padding, margins, and element alignment to precisely match design specifications.

- **Improving CSS specificity and cascade control**  
  Strengthen the understanding of how CSS specificity and inheritance affect style application.

- **Expanding use of pseudo-elements and pseudo-classes**  
  Leverage tools like `::before`, `::after`, `:not()`, and `:has()` for more elegant and maintainable solutions.

- **Enhancing accessibility (A11y)**  
  Apply ARIA roles, improve keyboard navigation, and add semantic enhancements to improve usability for all users.

- **Optimizing CSS structure and scalability**  
  Explore modern architecture patterns like ITCSS or the CSS `@layer` rule to ensure maintainable code as projects grow.

- **Advancing responsive design techniques**  
  Implement `clamp()`, container queries, and advanced grid layouts for greater responsiveness and adaptability.

### Useful resources

#### 1. **Git Immersion**

🔗 [https://gitimmersion.com/](https://gitimmersion.com/)  
📘 _A practical, step-by-step guide to mastering Git._  
This site goes beyond listing commands — it walks you through practical exercises and real examples. Perfect for understanding not just the **how**, but the **why** behind Git.

---

#### 2. **Learn CSS Grid**

🔗 [https://learncssgrid.com/](https://learncssgrid.com/)  
📘 _A comprehensive, beginner-friendly guide to mastering CSS Grid._  
Offers a clean, progressive learning path through essential CSS Grid concepts, using clear examples and visual demos to help build strong layout skills from the ground up.

---

#### 3. **CSS-Tricks: A Complete Guide to Grid**

🔗 [https://css-tricks.com/snippets/css/complete-guide-grid/](https://css-tricks.com/snippets/css/complete-guide-grid/)  
📘 _A thorough, visual reference for all CSS Grid properties and features._  
Ideal for both quick lookups and in-depth learning, with diagrams, live examples, and clear explanations of implicit and explicit grid behaviors.

---

#### 4. **Modern HTML Explained For Beginners** – _by HTML Academy_

🔗 [https://htmlacademy.org/blog/html/semantic-html-guide](https://htmlacademy.org/blog/html/semantic-html-guide)  
📘 _Explains how to use semantic HTML in modern development._  
Focuses on current best practices in HTML5, showing how semantic tags improve SEO, accessibility, and structure. Great for strengthening foundational HTML skills with a modern approach.

---

#### 5. **Every Layout – Intrinsic Design Patterns**

🔗 [https://every-layout.dev/](https://every-layout.dev/)  
📘 _Teaches CSS design patterns with a functional and modern approach._  
Learn to use tools like `clamp()`, `flex`, `grid`, and other advanced CSS features through a philosophy of simplicity and adaptability — avoiding over-reliance on media queries.

---

#### 6. **You Might Not Need JavaScript**

🔗 [https://youmightnotneedjs.com/](https://youmightnotneedjs.com/)  
📘 _Shows how many common interactions can be achieved with just HTML and CSS._  
A great resource to learn modern attributes and performance techniques, helping you write simpler, lighter code by reducing unnecessary JavaScript.

---

## Author

- Website – [Oscar Echenique D.](https://github.com/OscarE2D)
- Frontend Mentor – [@OscarE2D](https://www.frontendmentor.io/profile/OscarE2D)

---

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/OscarE2D/FrontendMentor-recipe-page-main.git
```
