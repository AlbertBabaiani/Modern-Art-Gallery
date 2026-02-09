# Skilled eLearning Landing Page

<div align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass" />
  <img src="https://img.shields.io/badge/Responsive-Mobile_First-green?style=for-the-badge" alt="Responsive" />

  <br />
  <br />

  <a href="https://albertbabaiani.github.io/Skilled-eLearning-landing-page/">
    <img src="https://img.shields.io/badge/View_Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="View Live Demo" />
  </a>
  
  <a href="https://www.figma.com/design/jItGARVJG8ZiiihK1vCn7N/art-gallery-website?node-id=0-1&p=f&t=95DflI5QITGF4tH5-0">
    <img src="https://img.shields.io/badge/Figma_Design_File-000000?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Design" />
  </a>

</div>

---

## About The Project

This is a responsive landing page for **"Skilled eLearning"**, a modern online course platform focused on high-demand skills like Animation, Design, and Business. The project features a vibrant, gradient-rich UI with a **mobile-first** architecture, ensuring a seamless experience from smartphones to wide-screen desktops.

It demonstrates the use of semantic HTML5, complex CSS Grid layouts for the card section, and the `<picture>` element for art direction—serving different hero image crops depending on the device viewport.

### Key Features

- **Mobile-First Workflow:** Styles are developed for mobile first, then enhanced for Tablet (`768px`) and Desktop (`1440px`) using min-width media queries.
- **CSS Grid Layout:** A responsive grid system that transforms the course cards from a single column on mobile to a 2-column (Tablet) and 3-column (Desktop) layout.
- **Art Direction:** Implementation of the `<picture>` tag to switch between specific image crops (mobile, tablet, desktop) and high-density versions (`@2x`, `@3x`) for sharper visuals.
- **Modern CSS Syntax:** Utilizes native CSS nesting (or SCSS) and CSS Variables (`:root`) for easy theme management (colors, gradients, spacing).
- **Interactive Elements:** Hover states with smooth transitions and gradient shifts for buttons and links.

---

## Screenshots

### Home Page

<div align="center">
  <img src="./assets/previews/home/home-desktop-preview.png" alt="Home Page Desktop" width="700"/>
</div>

<br/>

<div align="center" style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <img src="./assets/previews/home/home-tablet-preview.png" alt="Home Page Tablet" height="300"/>
  <img src="./assets/previews/home/home-mobile-preview.png" alt="Home Page Mobile" height="300"/>
</div>

<br/><br/>

### Location Page

<div align="center">
  <img src="./assets/previews/location/location-desktop-preview.png" alt="Location Page Desktop" width="700"/>
</div>

<br/>

<div align="center" style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <img src="./assets/previews/location/location-tablet-preview.png" alt="Location Page Tablet" height="300"/>
  <img src="./assets/previews/location/location-mobile-preview.png" alt="Location Page Mobile" height="300"/>
</div>

---

## Built With

- **[HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)** - Semantic structure (Header, Main, Section, Footer) and accessibility.
- **[SCSS / CSS3](https://sass-lang.com/)** - Uses modern nesting syntax, variables, and media queries.
- **[CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)** - Primary layout engine for the "Popular Courses" card section.
- **[Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)** - Used for the header, footer alignment, and internal card layouts.
