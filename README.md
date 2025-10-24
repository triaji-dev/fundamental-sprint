This sprint is based on Phillip Choi's https://www.youtube.com/@letphil

# Web Fundamentals with HTML, CSS, Vanilla JavaScript

## Outcome by Day 10

You will build a fully functional CRUD app in vanilla JS (e.g., budget tracker lite, to-do list, habit tracker). You will understand:

- How the web actually works
- DOM manipulation
- Events
- State (arrays/objects)
- Fetch (GET/POST)
- Real problem → real solution in the browser

This makes learning React 10x easier because you'll understand WHY it exists.

---

## Day 1: HTML is Structure (24-10-2025)

**Goal:** Learn how to properly structure a page semantically.

### Learn:
- `<html>`, `<head>`, `<body>`
- Headings, paragraphs, lists
- Forms, inputs, buttons
- Div vs semantic tags (section, article, nav, footer)

### Build:
- Simple static "Profile Page" with text, list of hobbies, a form with name/email

---

## Day 2: CSS is Presentation

**Goal:** Learn how to make things look clean and readable.

### Learn:
- Selectors (class, id, element)
- Box model (margin, padding, border)
- Display types (block vs inline vs inline-block)
- Basic colors, fonts, spacing

### Build:
- Style your profile page
- Add consistent spacing and alignment
- Make it visually appealing (no ugly dev pages)

---

## Day 3: Layout with Flexbox

**Goal:** Learn modern layout (don't float!)

### Learn:
- `display: flex;`
- `justify-content`, `align-items`
- Columns and rows
- Flex-grow / shrink

### Build:
- Responsive navbar
- Side-by-side layout (e.g., sidebar + content)
- Practice real layouts you'll use in apps

---

## Day 4: Responsive Design Basics

**Goal:** Make pages look good on phone + desktop.

### Learn:
- `%`, `vh`, `vw`
- Media queries (`@media (max-width:...)`)
- Mobile-first vs desktop-first

### Build:
- Make profile page responsive
- Hamburger-style collapsing nav (even if simple)

---

## Day 5: JavaScript Basics (Data & Logic)

**Goal:** Learn how to think like a programmer.

### Learn:
- Variables (`let`, `const`)
- Data types (string, number, boolean, array, object)
- Conditionals (`if`, `else`)
- Loops (`for`, `.forEach`)
- Functions (declaration, parameters, return)

### Build:
Write 3 functions:
1. Sum of numbers in array
2. Average of array
3. Format string (e.g., "Hello, Phil!")

---

## Day 6: DOM Manipulation

**Goal:** Connect JS to HTML.

### Learn:
- `document.querySelector`
- `.textContent`, `.innerHTML`, `.value`
- `.style`
- Creating/removing elements (`createElement`, `appendChild`, `remove`)

### Build:
- Build a "click to add item to list" function
- Show how JS can change the page dynamically

---

## Day 7: Events + User Input

**Goal:** Build interactivity.

### Learn:
- `.addEventListener("click", ...)`
- `submit` event on forms (`preventDefault`)
- Reading input values

### Build:
- Interactive form that captures and displays user input
- Button click handlers that modify the page