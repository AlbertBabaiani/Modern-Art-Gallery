# Modern Art Galerry

<div align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass" />
  <img src="https://img.shields.io/badge/Responsive-Mobile_First-green?style=for-the-badge" alt="Responsive" />

  <br />
  <br />

  <a href="https://albertbabaiani.github.io/Modern-Art-Gallery/">
    <img src="https://img.shields.io/badge/View_Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="View Live Demo" />
  </a>
  
  <a href="https://www.figma.com/design/jItGARVJG8ZiiihK1vCn7N/art-gallery-website?node-id=0-1&p=f&t=95DflI5QITGF4tH5-0">
    <img src="https://img.shields.io/badge/Figma_Design_File-000000?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Design" />
  </a>

</div>

---

## About The Project

This project is a responsive, two-page website built with **semantic HTML5** and **SCSS**. The goal was to build a pixel-perfect implementation of a provided design, focusing on layout stability and maintainable CSS architecture.

The site features a **Home page** and a **Location page**, both sharing consistent global styles and typography. It uses a mobile-first workflow, ensuring the layout adapts smoothly from a single-column stack on mobile devices to complex, asymmetrical grids on desktop screens.

### Key Features

- **Multi-Page Navigation:** Seamless linking between the Landing Page and Location Page.
- **Responsive Art Direction:** Uses the `<picture>` element to load different image crops for mobile, tablet, and desktop to maintain visual impact across devices.
- **CSS Grid Layout:** Implements a non-standard grid for the gallery section that rearranges completely at the tablet (`768px`) and desktop (`1440px`) breakpoints.
- **Interactive States:** Custom hover and focus states for buttons and social links, including accessible `:focus-visible` styles for keyboard users.
- **Blend Modes:** Utilizes `mix-blend-mode: difference` on desktop headings to create dynamic text contrast against background images.

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
