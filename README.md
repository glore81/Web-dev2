# Assignment #2: Advanced CSS (Flexbox & Grid)
**Student:** Aldiyar Temkeshev  
**Group:** SE-2527
**Live Demo:** [Click here to view live site](https://glore81.github.io/Web-dev2/) 
---
## Project Overview
This project demonstrates modern, responsive CSS layout techniques using **Flexbox** and **CSS Grid**.

---

## Tasks Breakdown

### Part 1: Flexbox Layouts
* **Task 0: Navigation Bar (`task0.html`)**
  * Built a horizontal navigation header using `display: flex`.
  * Utilized `justify-content: space-between` to position the logo on the left and navigation links on the right.
  * Applied `align-items: center` for vertical alignment.
* **Task 1: Card Row (`task1.html`)**
  * Created a row of cards using a Flexbox container.
  * Ensured equal card height and consistent spacing using `gap`.
  * Added smooth hover effects (`transform` and `box-shadow`).

### Part 2: Grid Systems
* **Task 2: Page Layout with Grid Areas (`task2.html`)**
  * Built a complete page layout using `display: grid` and `grid-template-areas`.
  * Defined structural areas: `"header header"`, `"sidebar main"`, and `"footer footer"`.
  * Assigned `grid-area` properties to corresponding layout elements.
* **Task 3: Image Gallery (`task3.html`)**
  * Constructed a 3x3 grid for 9 landmark images using `grid-template-columns: 1fr 1fr 1fr`.
  * Integrated an animated overlay caption on `:hover` showing image titles.

### Part 3: Integrated Layout
* **Task 4: Portfolio Page (`task4.html` / `index.html`)**
  * Combined **Flexbox** and **Grid** within a single webpage featuring historic world inventions.
  * **Header:** Flexbox navigation bar with logo and links.
  * **Main Content:** CSS Grid layout splitting the page into a primary content section (`1fr`) and an `About Me` sidebar (`400px`).
  * **Project Cards:** Individual project cards structured vertically using Flexbox (`flex-direction: column`) to align buttons cleanly at the bottom.
  * **Footer:** Full-width footer spanned across the bottom.

---

## Tech Stack
* **HTML:** Semantic markup (`<header>`, `<main>`, `<section>`, `<aside>`, `<footer>`).
* **CSS:** Advanced Flexbox alignment, CSS Grid Areas, hover transitions, and responsive styling.
