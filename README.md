🚀 Interactive Navigation Menu

A modern, responsive, and animated navigation menu built using HTML, CSS, and JavaScript.
This project features scroll-based UI transformations, smooth interactions, ripple hover effects, and a fully optimized mobile hamburger menu.

⭐ Features
🔥 Dynamic Scroll Effects

Navbar changes background, shadow, and style when the user scrolls.

Active menu item updates automatically based on the current section.

🎨 Advanced Hover Animations

Gradient underline animation

Glow background animation

Ripple effect on hover (JS-powered)

📱 Fully Responsive Navigation

Mobile-friendly hamburger menu

Smooth sliding animation

Body scroll lock when menu is open

⛳ Smooth Section Scrolling

Clicking a navigation link scrolls smoothly with correct offset.

🔐 Keyboard Navigation Support

Arrow keys allow moving between menu items.

🎯 Performance Optimized

Scroll handling uses requestAnimationFrame throttling.

CSS variables and minimal repaints.

📂 Folder Structure
/
├── index.html          # Main HTML file
├── styles.css          # Full UI/animation styling
└── script.js           # All interactivity logic

🛠️ Tech Stack

HTML5

CSS3 (Gradient, animations, transitions, glassmorphism)

JavaScript (Vanilla)

No external libraries. 100% lightweight.

📸 Preview (What It Includes)
✔ Fixed transparent navbar
✔ Scroll transforms (blur, shadow, gradient glow)
✔ Ripple effect on nav items
✔ Animated active link indicator
✔ Modern hero section
✔ Responsive sections (Home, About, Services, Portfolio, Contact)
🚧 How to Run
Option 1: Open directly

Just open index.html in your browser.

Option 2: Use a local server
# VS Code Live Server
Right-click → “Open with Live Server”

🧠 How It Works
🔸 Scroll Detection
if (window.scrollY > 50) {
    navbar.classList.add('scrolled');
}

🔸 Active Section Detection

Each section updates the active nav link when scrolled.

🔸 Mobile Menu
hamburger.classList.toggle('active');
navMenu.classList.toggle('active');

🔸 Ripple Effect

A ripple animation is created dynamically on hover.

🤝 Contributing

Pull requests are welcome — improve animations, add themes, or extend sections.

📜 License

MIT License — free to use, modify, and distribute.
