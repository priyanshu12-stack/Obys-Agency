🖥️ Project Technical Details
📌 Overview

This project is a frontend-only website inspired by modern creative agency portfolios (Obys). It delivers a visually rich, interactive, and fully responsive experience. The site showcases projects, an about section, awards, and dynamic animations to engage users.

🛠️ Tech Stack
HTML5 → Provides the structure of the website (semantic tags: <section>, <nav>, <video>, etc.).

CSS3 → Handles styling, responsive design, typography, layout (Flexbox, Grid, Media Queries).

Responsive CSS (responsive.css) → Ensures smooth mobile-first design using @media (max-width: 640px).

JavaScript (Vanilla JS) → Manages animations, cursor interactions, preloader functionality.

External Libraries:

Locomotive Scroll → Smooth scrolling & parallax effects (data-scroll, data-scroll-speed).

Shery.js → Adds high-end transitions and page motion effects.

Remix Icons → Used for icons (e.g., play button).

🎨 Features
🔹 Loader Screen

Custom preloader with timer (0 - 100) and animated text.

Smooth entry transition into the main content.

🔹 Hero Section

Large animated headings (WE DESIGN UNIQUE WEB/GRAPHIC EXPERIENCE).

Parallax scrolling (data-scroll-speed="1.5") for depth effect.

Interactive flag image for added motion.

🔹 Video Section

Preview thumbnail + hover play cursor.

Plays embedded MP4 video on interaction.

🔹 Projects Section

Image containers (.parentImg) that swap between two images on hover.

Circular hover elements (.imgCircle) display fun interactive messages.

Responsive scaling of project grid into a vertical column on small screens.

🔹 About Section

Split layout: image + text side by side on desktop, stacked on mobile.

Includes award showcase table with modern typography.

🔹 Works With (Ticker Animation)

Continuous text ticker animations: SPORT - TECHNOLOGY - FASHION etc.

Implemented with CSS keyframes + duplication for infinite loop.

🔹 Footer

Responsive layout with links, contact, and info.

Mobile version collapses into stacked sections.

📱 Responsive Design Highlights

Navbar shrinks, hides .menus on mobile, leaving only logo & brand.

Hero text scales dynamically (font-size: 12vw for smaller screens).

Projects stack vertically instead of grid on mobile.

Images scale to full width for readability.

About text font size adjusts (5.5vw for headings, 4.2vw for body).

Footer links convert into a column with larger touch-friendly fonts.

✨ Key Design Choices

Fluid Typography → All vw units ensure text adapts to any device.

Hover Interactions → Every project image has hover effects, creating engagement.

Micro Animations → From loader to cursor effects, all movements feel natural.

Performance → Lightweight frontend, uses CDN-based libraries, optimized assets.

🚀 How It Works

Preloader animates to give branding experience.

Locomotive Scroll initializes for smooth scrolling.

Hero + Projects leverage parallax speed differences for depth.

Responsive.css ensures seamless adaptation from desktop → tablet → mobile.

Shery.js + custom JS enhance transitions & animations.
