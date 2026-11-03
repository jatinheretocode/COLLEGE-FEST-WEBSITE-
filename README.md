# Samrat Utsav 2026 COLLEGE FEST WEBSITE 

Samrat Utsav 2026 is a responsive, frontend-only event website for Samrat Ashok Technological Institute (SATI), Vidisha. It showcases event categories, schedules, registrations, countdowns, and interactive animations.

## Tech Stack

- **HTML5** — Semantic page structure, navigation, sections, forms, FAQ, and footer.
- **CSS3** — Responsive layouts using CSS Grid and Flexbox, custom properties, media queries, gradients, animations, `clip-path`, and safe-area support for mobile devices.
- **Vanilla JavaScript (ES6+)** — Handles event filtering, schedule tabs, form validation, registration-number generation, duplicate registration checks, countdown timer, popup confirmation, receipt download, mobile menu, and animations.
- **Inline SVG** — Custom event graphics and visual elements are built directly into the website.
- **Browser Local Storage** — Saves registration details locally in the user’s browser.
- **Google Fonts** — Uses Anton, Bebas Neue, Manrope, and Noto Sans Devanagari fonts.

## Key Features

- Fully responsive design for desktop, tablet, and mobile
- Animated loading screen and scroll-based hero animation
- Event category and day-wise filters
- Day-wise event schedule
- Client-side registration form validation
- Unique registration-number generator
- Duplicate registration prevention for the same email and event
- Registration confirmation popup and downloadable receipt
- Countdown timer for the festival
- Accessibility support with ARIA labels, keyboard navigation, visible focus states, and reduced-motion support

## Data and Backend

This is a frontend-only project. Event information is stored in JavaScript, while registration data is stored in browser `localStorage`. No backend, database, login system, or payment gateway is currently used.

The project includes an optional `SHEET_URL` configuration. It can be connected later to Google Apps Script, Formspree, or another backend service to store registrations online.

## Future Improvements

- Add a backend using Node.js and Express
- Store registrations in MongoDB, MySQL, Firebase, or Google Sheets
- Add email confirmation
- Add an admin dashboard
- Integrate secure online payments, if required
