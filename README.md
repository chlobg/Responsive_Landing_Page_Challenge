# 🚀 Challenge: Build a Responsive Landing Page (HTML/SCSS with BEM)

## 🎯 Objective  
Build a complete landing page according to the given design, using **pure HTML**, **SCSS**, and following **BEM** class naming standards.  
The interface must be **responsive** and compatible with multiple screen sizes.

---

## 🎨 Design Reference  
[Figma Design Link](https://www.figma.com/design/uAnvOIJ9VCXinFtNPJqy8i/FREE-LANDING-PAGE-TEMPLATE---RESPONSIVE--Community-?node-id=6-12528&t=8MdTjvZkqAoUTFE7-1)

---

## 📋 Requirements

### ✅ HTML
- Semantic HTML5 elements (`<header>`, `<section>`, `<article>`, `<nav>`, `<footer>`)
- Clear and organized structure
- Use of **BEM naming convention** (`block__element--modifier`)

### 🎨 SCSS
- Use **SCSS partials** for modularity:  
  `_variables.scss`, `_header.scss`, `_hero.scss`, etc.
- Use **custom variables** like `$primary-color`, `$font-stack`, etc.
- Use **responsive breakpoints** (`@media`) and layout utilities (Flex/Grid)

### 📱 Responsive Design
- Use either **desktop-first** or **mobile-first** approach
- Fully responsive on:
  - Desktop  
  - Tablet  
  - Mobile  

### ✨ Bonus Features (Optional)
- Smooth scroll to sections
- Sticky header
- Scroll animations (e.g. [AOS](https://michalsnik.github.io/aos/) or CSS animations)

---

## 📁 Suggested Folder Structure

landing-page/
├── index.html
├── /scss
│ ├── main.scss
│ ├── _variables.scss
│ ├── _header.scss
│ ├── _hero.scss
│ └── ...
├── /css
│ └── main.css # compiled from SCSS
├── /assets
│ ├── /images
│ └── /icons

yaml
Copy
Edit

---

## 🧪 Evaluation Criteria
- ✅ BEM class naming consistency  
- ✅ Match with the Figma design  
- ✅ SCSS structure & reusability  
- ✅ Fully responsive layout  
- ✅ Clean and semantic HTML structure
