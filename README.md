# Tailwind-CSS-Web-Page-Clone-
A responsive PW skills clone built with HTML5, Tailwind CSS for responsiveness to understand a frontend framework ...

🚀 What I Built (Chronological Summary)
1. Project Setup
   Initialized the project with HTML5 boilerplate.
   Integrated Tailwind CSS for styling.
   Configured the viewport meta tags to ensure proper mobile responsiveness across devices.

2. Header & Navigation
   Built a custom, responsive navigation bar.
   Implemented a "hamburger" menu for mobile view and a horizontal list for desktop.
   Used JavaScript to toggle the visibility of the mobile menu, ensuring a smooth user experience.
   Added whitespace-nowrap and flexbox properties to keep the logo and navigation elements aligned during window resizing.

3. Responsive Banner Section
   Implemented image swapping based on screen size (md: breakpoints).
   Used standard <img> tags with Tailwind’s visibility utilities (hidden, block) to serve the correct banner for Desktop vs. Mobile devices.

4. Interactive Statistics Section
   Created a dark-themed section (bg-slate-900) showcasing key company stats (Courses, Students, Transitions).
   Added custom design elements like centered yellow decorative underlines.
   Used a circular layout with SVG icons to match the design aesthetic.

5. Product Showcase Section
6. Built a 5-column grid layout using CSS Grid (grid-cols-1 sm:grid-cols-2 lg:grid-cols-5).
   Implemented a clean "hover-to-reveal" border effect using border-transparent and hover:border-white to prevent layout shifting.
   Ensured consistent card height using flex-col and h-full to maintain a uniform design.

6. Footer Implementation
   Developed a 3-column footer structure.
   Included link sections for "PW Skills" and "Products".
   Added hover states for navigation links to improve interactivity.



💻 How to Run Locally
Here is a simplified, step-by-step breakdown of how to follow that specific guide:

Step 1: Initialize the Project
        Open your terminal and run these commands to set up the foundation:
        npm create vite@latest
        Give your project a name (e.g., my-pw-skills-clone).
        Select React with the arrow keys.
        Select JavaScript (or TypeScript if you prefer).
        Navigate into your folder: cd my-pw-skills-clone
        Install the base tools: npm install

Step 2: Install Tailwind CSS
        Now, add Tailwind to your new Vite project:
        Run: npm install -D tailwindcss postcss autoprefixer
        Generate the config files: npx tailwindcss init -p

Step 3: Configure Tailwind
        This step tells Tailwind to look at your HTML and JS files for classes:
        Open the tailwind.config.js file in your editor.
       Replace the content array with the one shown in your screenshot:

   JavaScript
          content: [
            "./index.html",
            "./src/**/*.{js,ts,jsx,tsx}",
            ],
Step 4: Add Directives
        Open src/index.css (or src/App.css depending on your Vite setup). Delete everything currently in that file and paste these three lines at the very top:

#CSS
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
Step 5: Start Development
        Finally, to start the "live" version of your site that updates as you code:



Your terminal will give you a link (usually http://localhost:5173). Click it, and your site will be live!

🛠 Tech Stack
   HTML5 - Structure of the web page.
   Tailwind CSS - Rapid UI styling and responsive framework.
   JavaScript - Logic for the mobile menu toggle.
   SVG Icons - Scalable vector icons for high-quality visuals.

💡 Key Design Patterns Used
   Mobile-First Design: Ensuring elements stack vertically on mobile and expand into rows on larger screens.
   State Management: Using hidden/block classes and JavaScript classList.toggle to handle UI states.
   Layout Consistency: Using Flexbox and CSS Grid to handle complex alignments and equal-height containers.
