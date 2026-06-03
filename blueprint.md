# Blueprint: Casino Lotto Machine

## Overview
The "Casino Lotto Machine" is a framework-less web application that provides users with randomized lottery number recommendations (1-45 range). It features both a visually striking "Casino Jackpot" theme and a "Clean Light" theme using modern CSS techniques.

## Project Details

### Features
- **Random Number Generation**: Generates 5 sets of lottery numbers. Each set includes 6 sorted main numbers and 1 bonus number.
- **Theme Toggle**: A fixed button allows users to switch between a "Casino Dark" mode and a "Clean Light" mode.
- **Real-time News Feed**: Fetches the latest 5 posts from the "uspolitics" DC Inside gallery every 60 seconds using a CORS proxy.
- **Affiliate Inquiry Form**: A integrated form using Formspree to collect name, email, and messages for business inquiries.
- **Visual Feedback**: Buttons and cards use interactive gradients, shadows, and hover effects.
- **Color Coding**: Lottery balls are color-coded based on their value ranges (1-10: Yellow, 11-20: Blue, 21-30: Red, 31-40: Gray, 41-45: Green).
- **Responsive Design**: The application adapts to different screen sizes for mobile and web compatibility.

### Design & Aesthetics
- **Themes**:
    - **Dark**: Deep reds, greens, and blacks with vibrant gold accents for a premium casino feel.
    - **Light**: Clean whites, grays, and soft blues for a modern, high-contrast look.
- **Dynamic Styling**: Uses CSS variables and transitions for smooth theme switching.
- **Typography**: Expressive headings with conditional text-shadows.

### Technical Implementation
- **HTML5**: Semantic structure using `div`, `button`, and `span`.
- **CSS3**: 
    - CSS Variables (`:root`) for theme management.
    - Flexbox for alignment.
    - Advanced gradients and box-shadows.
    - Transitions for interactive button states.
- **JavaScript**: 
    - ES6 syntax (arrow functions, template literals).
    - DOM manipulation to dynamically generate and render lottery "tickets".
    - Theme switching logic with class toggling.

## Current Plan: Completed & Deployed
Objective: Finalize the theme toggle feature and ensure it is live.

1.  **Refactor CSS**: Implemented CSS variables for theme-wide color management.
2.  **Add Toggle Logic**: Created a JavaScript `toggleTheme()` function and associated UI button.
3.  **Update Deployment**: Pushed the final version to `gh-pages` branch.
