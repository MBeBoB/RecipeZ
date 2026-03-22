# RECIPEZ – Digital Recipe Sharing Web Application

**ICT 2204 / COM 2303 – Web Technologies & Web Design**  
Rajarata University of Sri Lanka | Department of Computing  
**Students:** ICT/2023/047 & ICT/2023/008

---

## Project Overview

RECIPEZ is a community-driven recipe sharing web platform where users can browse, discover, and submit recipes. It is organised into categories, features a popularity ranking section, and allows users to add their own recipes with video links.

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | index.html | Hero slider, quick cards, latest recipes |
| Categories | categories.html | 10 category cards + overview table |
| Inside Category | category.html | Filtered recipes by category |
| Popular | popular.html | Most-viewed recipes with filter buttons |
| Recipe Detail | recipe.html | YouTube embed, ingredients table, steps, comments |
| Add Recipe | add-recipe.html | Form with JS validation + lab demos |
| Login | login.html | JS login with alert + redirect |

---

## Lab Coverage

| Lab | Topic | Covered In |
|-----|-------|-----------|
| Lab 01 | HTML – tags, headings, paragraphs, images, hyperlinks, lists, tables | All HTML files |
| Lab 02 | CSS – inline, embedded, external; color, font-family, font-size, border, padding, margin | styles.css + HTML files |
| Lab 03 | JS Basics – variables (var/let/const), DOM, innerHTML, alert, console.log | main.js |
| Lab 04 | JS Operators – arithmetic, comparison, logical; if/else/nested-if/if-else-if ladder | main.js |
| Lab 05 | JS Loops (for/while/do-while), Functions | main.js |
| Lab 06 | JS Arrays, Objects, Strings | main.js |
| Lab 07 | PHP Basics (referenced in comments) | main.js comments |

---

## JavaScript Features (Project Requirements)

1. ✅ Dynamic Content Updates – Live search, filter buttons
2. ✅ Interactive Image Slider – Auto-play hero slider with manual controls
3. ✅ Form Validation – Add recipe + login validation with error messages
4. ✅ Smooth Scrolling – Back to Top button
5. ✅ Event Handling – Hover effects, click events, keyboard events
6. ✅ Custom Animations – Fade-in on scroll, slide transitions

---

## Login Credentials (Demo)

| Username | Password |
|----------|----------|
| ICT047   | recipez  |
| ICT008   | recipez  |
| admin    | recipe123|

---

## File Structure

```
recipez/
├── index.html          ← Home Page
├── categories.html     ← Categories Page
├── category.html       ← Inside Category Page
├── popular.html        ← Popular Page
├── recipe.html         ← Recipe Detail Page
├── add-recipe.html     ← Add Recipe Form
├── login.html          ← Login Page (JS)
├── css/
│   └── styles.css      ← External CSS (Lab 02)
├── js/
│   └── main.js         ← All JavaScript (Lab 03-06)
└── README.md
```

---

## Tech Stack

- **HTML5** – Semantic structure (Lab 01)
- **CSS3** – External, embedded, inline (Lab 02)
- **JavaScript (Vanilla)** – DOM, arrays, objects, loops, functions (Lab 03–06)
- No frameworks – pure HTML/CSS/JS as per lab requirements
