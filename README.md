🚀 TAILWIND-CSS-WEB-PAGE-CLONE
   A responsive PW skills clone built with HTML5 and Tailwind CSS for responsiveness to understand a frontend framework.

📂 What I Built (Chronological Summary)
• Project Setup: Initialized the project with HTML5 boilerplate. Integrated Tailwind CSS for styling. Configured the viewport meta tags to ensure proper mobile    
  responsiveness across devices.

• Header & Navigation: Built a custom, responsive navigation bar. Implemented a "hamburger" menu for mobile view and a horizontal list for desktop. Used             JavaScript to toggle the visibility of the mobile menu, ensuring a smooth user experience. Added whitespace-nowrap and flexbox properties to keep the logo and     navigation elements aligned during window resizing.

• Responsive Banner Section: Implemented image swapping based on screen size (md: breakpoints). Used standard tags with Tailwind’s visibility utilities (hidden,     block) to serve the correct banner for Desktop vs. Mobile devices.

• Interactive Statistics Section: Created a dark-themed section (bg-slate-900) showcasing key company stats (Courses, Students, Transitions). Added custom design    elements like centered yellow decorative underlines. Used a circular layout with SVG icons to match the design aesthetic.

• Product Showcase Section: Built a 5-column grid layout using CSS Grid (grid-cols-1 sm:grid-cols-2 lg:grid-cols-5). Implemented a clean "hover-to-reveal" border    effect using border-transparent and hover:border-white to prevent layout shifting. Ensured consistent card height using flex-col and h-full to maintain a          uniform design.

• Footer Implementation: Developed a 3-column footer structure. Included link sections for "PW Skills" and "Products". Added hover states for navigation links to    improve interactivity.

💻 How to Run Locally
  Clone the repository:
 
  Bash
  git clone https://github.com/OmDas123/REACT-NATIVE-PROJECTS
  Steps
  Open Terminal and run: npm create vite@latest
  Enter your project name (of your choice).
  Select React, then JavaScript, and press Enter.
  Navigate into your new project folder:

  Bash
  cd your-project-name
  Install the base dependencies:

  Bash
  npm install
  Install Tailwind CSS and its required peer dependencies:

  Bash
  npm install -D tailwindcss postcss autoprefixer
  Generate the configuration files (tailwind.config.js and postcss.config.js):

  Bash
  npx tailwindcss init -p
  Open the newly created tailwind.config.js file and update the content array so Tailwind knows where to look for your classes:

  JavaScript
 /** @type {import('tailwindcss').Config} */
  export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

🛠 Tech Stack
  Across this project, I am actively working with:
 • HTML5: Structure of the web page.
 • Tailwind CSS: Rapid UI styling and responsive framework.
 • JavaScript: Logic for the mobile menu toggle.
 • SVG Icons: Scalable vector icons for high-quality visuals.

💡 Key Design Patterns Used
   ► Mobile-First Design: Ensuring elements stack vertically on mobile and expand into rows on larger screens.
   ► State Management: Using hidden/block classes and JavaScript classList.toggle to handle UI states.
   ► Layout Consistency: Using Flexbox and CSS Grid to handle complex alignments and equal-height containers.
