# Mapty

Mapty is a web application that allows users to map and log their running and cycling workouts using an interactive map. The app uses the browser's geolocation API and [Leaflet.js](https://leafletjs.com/) for mapping functionality.

## Features

- **Geolocation:** Automatically detects your location and centers the map.
- **Workout Logging:** Click on the map to log a new workout (running or cycling).
- **Custom Form:** Enter distance, duration, and cadence (for running) or elevation gain (for cycling).
- **Workout List:** Displays a list of all workouts in the sidebar.
- **Map Markers:** Each workout is marked on the map with a popup showing details.
- **Persistent Data:** Workouts are saved in local storage and persist across page reloads.
- **Responsive UI:** Clean, modern interface styled with CSS.

## Technologies Used

- **HTML5** and **CSS3** for structure and styling
- **JavaScript (ES6+)** for application logic
- **[Leaflet.js](https://leafletjs.com/)** for interactive maps
- **LocalStorage** for data persistence

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/mapty.git
   cd mapty
   ```

2. **Open `index.html` in your browser.**
   - No build step is required; all dependencies are loaded via CDN.

3. **Allow location access** when prompted by your browser.

## Project Structure

```
.
├── index.html
├── script.js
├── style.css
├── logo.png
├── icon.png
├── Mapty-architecture-final.png
├── Mapty-architecture-part-1.png
├── Mapty-flowchart.png
├── other.js
└── .prettierrc
```

- `index.html` – Main HTML file
- `script.js` – Main JavaScript logic (workout classes, app logic, map integration)
- `style.css` – Styling for the app
- `logo.png`, `icon.png` – App icons and logo
- `Mapty-architecture-*.png`, `Mapty-flowchart.png` – Project diagrams
- `other.js` – Example/unused JS file
- `.prettierrc` – Prettier configuration

## Credits

- App concept and original design by [Jonas Schmedtmann](https://twitter.com/jonasschmedtman).
- Use for learning or your portfolio. **Do not use to teach or claim as your own.**

## License

This project is for educational purposes only.

---
