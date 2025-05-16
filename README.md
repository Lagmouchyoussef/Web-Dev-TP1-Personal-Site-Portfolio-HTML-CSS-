# TP1: Web Programming

## Exercise 1: Creating a Personal Mini-Site - Basic HTML & CSS

### 1. Basic Site Structure (HTML)
- Create an index.html page containing:
  - Header with a clickable logo (image) linking to home
  - Navigation menu (`<nav>`) to two other pages:
    - about.html
    - portfolio.html
  - Introduction section with:
    - Main `<h1>` title
    - Presentation paragraph
  - Footer with links to:
    - Instagram and Twitter (icons + clickable links opening in new tab)

### 2. About Page
- Include an "About Me" title
- Add:
  - A paragraph describing the student
  - An unordered list of 3 skills

### 3. CSS Styling (style.css)
- Link an external stylesheet
- Apply:
  - Background color `#1F2039` on `body`
  - Titles:
    - Montserrat font
    - Color `#A5B4FC`
  - Paragraphs: Manrope font
  - Links:
    - Remove underline
    - Underline on hover (`:hover`)
  - Right and bottom border for a div containing skills (color `#A5B4FC`)

### 4. Text & Image Formatting
- Add a profile picture
- Formatting:
  - Important words in italic (`<em>`)
  - "View My Portfolio" button with gradient background (`linear-gradient`)

---

## Exercise 2: Dynamic Portfolio with Advanced CSS Effects

### 1. Create portfolio.html page
- Present 3 fictional projects with:
  - Clickable thumbnail that opens original image
  - Brief description in a paragraph

### 2. Apply CSS Box Model
- Frame each project in a `div` with:
  - A border
  - 16px `padding`
  - 30px `margin` between blocks

### 3. Dynamic Visual Effects
- Apply:
  - Drop shadow (`box-shadow`) to projects
  - `:hover` effect on images:
    - Opacity at 0.5
    - `pointer` cursor

### 4. Transitions & Dynamic Appearance
- Create a "Contact Me" button with:
  - Gradient background (`#696484` → `#8788BA`) on hover
  - White text, Montserrat font
  - 50px rounded border

### 5. Organization & Structure
- Properly use:
  - `<section>`, `<header>`, `<footer>`, `<main>` on all pages
- Center content in `about.html` with `margin: auto`
