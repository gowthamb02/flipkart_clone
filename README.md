

# 🛒 Flipkart Clone: Responsive E-commerce Homepage

## Project Overview

This project is a detailed, responsive clone of the Flipkart e-commerce homepage, built primarily using **HTML5 and CSS3 (with media queries)**. The goal was to accurately replicate the user interface, including complex layout patterns, navigation elements, product display sections, and a CSS-only automated carousel/banner.

The structure is highly modular and utilizes advanced CSS techniques for responsiveness across desktop, tablet, and mobile devices.

## 🌟 Key Features & Technical Highlights

This project demonstrates proficiency in modern front-end development through the following features:

  * **Responsive Layout Design:** Implemented a multi-level responsive design using custom media queries to adapt the layout across various screen widths (`> 1192px`, `> 768px`, and `< 768px`).
  * **CSS-Only Carousel/Banner:** Features a custom image slider implemented purely with **CSS `@keyframes` and `transform` properties**, ensuring smooth, infinite horizontal loop animations without relying on JavaScript.
  * **Complex Grid and Flexbox Layouts:** Utilized `display: grid` and `display: flex` extensively to create intricate page sections, including:
      * The main product category bar.
      * The 3-column promotional card grids (`.category__grid`).
      * The desktop-only "Best Deals" section with its unique layout (`.bestdealsection__grid`).
  * **Modular Product Lists (Mobile Optimization):** Implemented distinct mobile layouts for horizontal scrolling lists (`.bdphone__scroll`, `.topdeals__scroll`) which transform into vertical, full-width, single-item lists at the mobile breakpoint.
  * **Interactive UI Details:** Replicated hover effects for the login button, animated dropdown icons, and button styling to match the Flipkart aesthetic.
  * **Semantic HTML5 Structure:** Structured the page using appropriate elements like `<header>`, `<nav>`, `<div>`, and `<footer>` for better accessibility and SEO (Search Engine Optimization).

## 💻 Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Core structure and content organization. |
| **CSS3** | Styling, layout (Flexbox & Grid), responsiveness, and animations. |
| **Google Fonts** | Imported the "Inter" typeface for typography. |
| **Font Awesome** | Used for icons (e.g., search icon). |

## 📐 Responsive Breakpoints

| Device View | Breakpoint (`max-width`) | Key Changes Implemented |
| :--- | :--- | :--- |
| **Desktop** | \> 1192px | Full 6-item nav bar, 3-column grids, static product lists. |
| **Tablet** | 900px to 1192px | Cart and Seller text is hidden. Horizontal scrolling is enabled for categories and deal sections. Banner buttons are hidden. |
| **Mobile** | \< 768px | Header transforms (search hidden, menu bar visible). Product sections switch from horizontal scroll to **vertical list layout with full-width items**. Footer is hidden. |

## 🚀 Future Enhancements

  * **BEM Implementation:** Refactor all CSS classes to follow the BEM (Block-Element-Modifier) naming convention for increased modularity and maintainability (as started with the Navbar).
  * **JavaScript Interactivity:** Implement actual logic for the banner scroll buttons (`<` and `>`) and add dynamic behavior to the login/dropdown menu.
  * **Accessibility (A11Y):** Enhance ARIA attributes, especially for navigation and interactive elements, to ensure full keyboard navigation support.
  * **CSS Variables:** Utilize CSS custom properties (variables) for colors, fonts, and spacing to streamline global style changes.

## 🤝 How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR_GITHUB_REPO_LINK]
    ```
2.  **Navigate to the folder:**
    ```bash
    cd flipkart-clone
    ```
3.  **Open in Browser:**
    Open the `index.html` file directly in your web browser (e.g., by right-clicking and selecting "Open with Chrome").

## 📸 Screenshots

Desktop view
<img width="1920" height="1080" alt="Desktop view" src="https://github.com/user-attachments/assets/2a61d515-81a1-40c1-ad1c-6cb8b904812c" />
<img width="1920" height="1080" alt="Desktop view" src="https://github.com/user-attachments/assets/f88db95b-32c8-4332-a579-f21c809354d7" />
<img width="1920" height="1080" alt="Desktop view" src="https://github.com/user-attachments/assets/ddfac072-9d04-49b7-af74-d1c5d6166873" />
<img width="1920" height="1080" alt="Desktop view" src="https://github.com/user-attachments/assets/2c1c3e75-edde-41a6-b795-ae67cab0c857" />

Mobile View
<img width="401" height="814" alt="iPhone-13-PRO-127 0 0 1" src="https://github.com/user-attachments/assets/ffda9d12-40e8-4edf-ab63-3e84c96d5c8d" />
<img width="401" height="814" alt="iPhone-13-PRO-127 0 0 1 (1)" src="https://github.com/user-attachments/assets/3e4e4558-e961-4f1c-8cd9-85ee235ad95f" />







-----

## **Note:** Since this is a UI-only clone, all navigation links and buttons are non-functional and for visual presentation only.
