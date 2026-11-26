<div align="center">

<!-- Top Tech-Orange & Dark-Slate Animated Wave Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,55:1A1F2E,100:F96400&height=230&section=header&text=🚀%20Tech%20Vantage%20Solutions&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Corporate%20IT%20Agency%20Website%20%7C%20Responsive%20Multi-Page%20Web%20Design&descAlignY=63&descSize=17&animation=fadeIn" width="100%" />

<!-- Animated Typing SVG -->
<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=1000&color=F96400&center=true&vCenter=true&width=780&lines=Modern+Responsive+Corporate+Website+in+HTML5%2C+CSS3+%26+JS;4-Tier+Breakpoint+System+(Mobile+%E2%80%A2+Tablet+%E2%80%A2+Desktop+%E2%80%A2+1440p);Unified+Global+Navigation%2C+Hero+Glassmorphism+%26+Scroll+FX;Team+Lead+%26+Core+Frontend+Architecture+by+YEOW+ZONG+ZHENG" alt="Typing SVG" />
</a>

<br/>

<!-- Tech Stack & Leadership Badges -->
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Responsive-Mobile--First%204%20Breakpoints-F96400?style=for-the-badge" alt="Responsive" />
  <img src="https://img.shields.io/badge/Role-Project%20Lead%20%26%20Frontend%20Dev-1A1F2E?style=for-the-badge" alt="Project Lead" />
</p>

<!-- Quick Navigation -->
<p>
  <a href="#overview">Overview</a> •
  <a href="#leadership">My Role &amp; Contributions</a> •
  <a href="#pages">Site Architecture</a> •
  <a href="#responsive">Responsive Design</a> •
  <a href="#showcase">UI Showcase</a> •
  <a href="#structure">Project Structure</a> •
  <a href="#quickstart">Quick Start</a> •
  <a href="#team">Team</a>
</p>

</div>

---

<a name="overview"></a>
## 🌐 Overview

**Tech Vantage Solutions** is a modern, multi-page corporate website built with **HTML5, CSS3, and Vanilla JavaScript** for a technology consultancy specializing in **Software Development, AI-Powered Services, and Professional IT Training**.

Engineered with a mobile-first approach and a cohesive **Tech Orange (`#F96400`) & Deep Slate (`#1A1F2E` / `#111827`)** visual identity, the platform delivers smooth interactive animations, a unified cross-page navigation system, and seamless responsiveness across mobile, tablet, desktop, and widescreen displays.

---

<a name="leadership"></a>
## 👑 My Role — Group Leader & Core Frontend Architect

As **Project Manager & Lead Frontend Developer** of a 3-person team, I architected the foundational design system, built the landing experience and shared global components, and led final code review and cross-page debugging:

<table align="center" width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🏗️ Core UI &amp; Global Design System</h3>
      <ul>
        <li><b>Landing Page (<code>index.html</code> &amp; <code>home.css</code>):</b> Designed the fixed-attachment hero banner with frosted glassmorphism (<code>backdrop-filter: blur(5px)</code>), staggered JS entrance animations, company profile section, and glowing orange CTA interactions.</li>
        <li><b>Unified Header &amp; Navbar:</b> Engineered the consistent top header, active route highlighting (<code>.nav-active</code>), and responsive mobile hamburger drawer across all 5 pages.</li>
        <li><b>Global Multi-Column Footer:</b> Built the standardized dark-slate footer featuring brand identity, animated social links, support links, and anchor-linked service shortcuts.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🔍 Project Leadership &amp; Code Review (QA)</h3>
      <ul>
        <li><b>4-Tier Breakpoint Standard:</b> Established the shared responsive stylesheet rules covering Mobile (<code>&lt;768px</code>), Tablet (<code>768px</code>), Desktop (<code>1024px</code>), and XL Desktop (<code>1440px</code>).</li>
        <li><b>Cross-Page Integration &amp; Debugging:</b> Audited and refined all teammates' pages for visual consistency, CSS cascade conflicts, and responsive behavior—such as resolving portfolio image height-cropping issues on desktop viewports.</li>
        <li><b>Team Coordination:</b> Managed task delegation, milestone reviews, and final codebase consolidation across the 3-developer squad.</li>
      </ul>
    </td>
  </tr>
</table>

---

<a name="pages"></a>
## 📑 Site Architecture & Page Features

| Page | Files | Key UI &amp; Interactive Highlights |
| :--- | :--- | :--- |
| **🏠 Home** | `index.html`<br/>`home.css` | Full-width hero banner with parallax effect &amp; glassmorphism overlay, staggered fade-up headline animations, company profile section, and global Header/Navbar/Footer system. |
| **💼 Services** | `services.html`<br/>`services.css` | 6-card responsive CSS Grid (*Web Dev, Mobile Apps, Cloud, Cybersecurity, Data Analytics, IT Consulting*) featuring `@keyframes icon-shake` hover animations, checkmarked specs, and CTA banner. |
| **🗂️ Portfolio** | `portfolio.html`<br/>`portfolio.css` | Case study showcase (*Retail E-Commerce Platform, Smart AI Chatbot, HR Management Dashboard*) with staggered banner reveal, technology tags, and uncropped responsive media cards. |
| **🏢 About Us** | `about.html`<br/>`about.css` | Company Story, Vision &amp; Mission, and 3-member Team grid with circular avatar zoom hovers and `IntersectionObserver` scroll-triggered reveal animations (`.scroll-animate`). |
| **📞 Contact Us** | `contact.html`<br/>`contact.css` | Interactive inquiry form with JS modal confirmation popup (`#contactPopup`), office address &amp; contact details, and embedded responsive Google Maps `<iframe>`. |

---

<a name="responsive"></a>
## 📱 4-Tier Responsive Breakpoint System

All pages share a unified responsive layout strategy defined in `home.css` and extended across sub-page stylesheets:

- **📱 Mobile (`< 768px`):** Collapsible hamburger navigation drawer with smooth slide-down transition, stacked single-column cards, and full-width touch buttons.
- **📲 Tablet (`≥ 768px`):** Horizontal inline navigation bar, 2-column service grids, centered hero typography, and balanced footer columns.
- **💻 Desktop (`≥ 1024px`):** 3-column service grids, fixed parallax hero banner with glassmorphic content container, hover scale/elevation transitions, and horizontal 3-column footer.
- **🖥️ Extra-Large Desktop (`≥ 1440px`):** Max-width container scaling (`1400px–1600px`) with expanded typography and generous whitespace for high-resolution monitors.

---

<a name="showcase"></a>
## 📸 UI Showcase

> *Add screenshots or short hover-animation GIFs into `docs/screenshots/` to visually highlight the responsive layout and interactive effects.*

<table align="center" width="100%">
  <tr>
    <td width="50%" align="center">
      <b>🏠 Home Page — Glassmorphic Hero &amp; Global Header</b><br/>
      <img src="docs/screenshots/home.png" alt="Home Page" width="100%" />
    </td>
    <td width="50%" align="center">
      <b>💼 Services — Responsive Grid &amp; Icon Animations</b><br/>
      <img src="docs/screenshots/services.png" alt="Services Page" width="100%" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>🗂️ Portfolio &amp; About — Scroll-Reveal &amp; Team Cards</b><br/>
      <img src="docs/screenshots/about-portfolio.png" alt="Portfolio and About Page" width="100%" />
    </td>
    <td width="50%" align="center">
      <b>📞 Contact — Modal Confirmation &amp; Google Maps</b><br/>
      <img src="docs/screenshots/contact.png" alt="Contact Page" width="100%" />
    </td>
  </tr>
</table>

---

<a name="structure"></a>
## 📂 Project Structure

```text
Tech-Vantage-Solutions/
├── index.html          # Home page (Hero banner, company profile, global header & footer)
├── home.css            # Global stylesheet (Header, Navbar, Footer, Home & 4-tier breakpoints)
├── services.html       # IT services catalog & consultation CTA
├── services.css        # Service grid cards, @keyframes icon-shake & responsive rules
├── portfolio.html      # Project case studies showcase
├── portfolio.css       # Portfolio banner transitions & responsive project cards
├── about.html          # Company story, vision/mission & team roster
├── about.css           # Team card hover effects & IntersectionObserver scroll animations
├── contact.html        # Contact form, confirmation modal & embedded Google Map
├── contact.css         # Form styling, modal popup overlay & map layout
└── images/             # Brand logos, hero banners, portfolio previews & team avatars
```

---

<a name="quickstart"></a>
## 🚀 Quick Start

No build tools or external dependencies are required—the site runs natively in any modern web browser:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yeowzongzheng0215-droid/Tech-Vantage-Solutions.git](https://github.com/yeowzongzheng0215-droid/Tech-Vantage-Solutions.git)
   cd Tech-Vantage-Solutions
   ```

2. **Open in Browser**
   - Double-click `index.html` to open directly in Chrome, Edge, Firefox, or Safari, **or**
   - Launch with the **Live Server** extension in VS Code for local development.

---

<a name="team"></a>
## 👥 Team & Credits

<table align="center" width="100%">
  <tr>
    <td width="34%" valign="top">
      <h3 align="center">👑 Yeow Zong Zheng</h3>
      <p align="center">
        <b>Project Manager &amp; Lead Developer</b><br/>
        <a href="https://github.com/yeowzongzheng0215-droid">@yeowzongzheng0215-droid</a>
      </p>
      <ul>
        <li>Developed <code>index.html</code> &amp; <code>home.css</code>.</li>
        <li>Built unified Header, Navbar &amp; Footer across all pages.</li>
        <li>Led final code review, bug fixes &amp; responsive QA.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">💻 Neo Chang Jie</h3>
      <p align="center">
        <b>Web Project Developer</b><br/>
        <i>Frontend Sub-Pages</i>
      </p>
      <ul>
        <li>Developed sub-page layouts and content modules (<code>services</code> / <code>portfolio</code> / <code>about</code> / <code>contact</code>).</li>
        <li>Implemented sub-page CSS grids and responsive media queries.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">💻 Ng Yi Shen</h3>
      <p align="center">
        <b>Web Project Developer</b><br/>
        <i>Frontend Sub-Pages</i>
      </p>
      <ul>
        <li>Developed sub-page layouts and interactive UI features (scroll reveals, contact modal &amp; map integration).</li>
        <li>Styled sub-page cards and interactive hover states.</li>
      </ul>
    </td>
  </tr>
</table>

---

<div align="center">

<!-- Bottom Tech-Orange & Dark-Slate Wave Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F96400,55:1A1F2E,100:111827&height=120&section=footer" width="100%" />

</div>
