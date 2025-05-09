# Portfolio-Dashboard-App
Responsive Portfolio Dashboard
A modern, responsive portfolio dashboard built with HTML, CSS, and JavaScript. This dashboard is designed to visualize portfolio performance, asset allocation, and financial transactions with a clean, intuitive interface that works across all device sizes.
Features

Fully Responsive Design: Adapts seamlessly to desktop, tablet, and mobile devices
Interactive Charts: Dynamic data visualization with Chart.js
Dark Theme: Easy on the eyes with a professional dark color scheme
Real-time Data Updates: Toggle between weekly, monthly, and yearly views
Mobile-Friendly Navigation: Collapsible sidebar for smaller screens
Performance Optimized: Lightweight and fast-loading

File Structure
portfolio-dashboard/
├── index.html          # Main HTML file with dashboard structure
├── assets/             # Directory for additional assets (optional)
│   ├── js/             # JavaScript files (if separated)
│   └── css/            # CSS files (if separated)
└── README.md           # Project documentation
Installation

Clone the repository:
git clone https://github.com/yourusername/portfolio-dashboard.git

Open index.html in your web browser.

That's it! No build process or dependencies required.
Usage
Navigation

Use the sidebar menu to navigate between different sections
On mobile devices, click the hamburger menu to open/close the sidebar
Use the search bar to find specific assets or transactions

Dashboard Customization

Click on the time period buttons (W/M/Y) to toggle between weekly, monthly, and yearly data views
Hover over charts to see detailed tooltips with precise values

Customization
Color Scheme
You can easily customize the color scheme by modifying the CSS variables at the top of the style section:
css:root {
    --primary-color: #6366f1;
    --primary-hover: #4f46e5;
    --secondary-color: #10b981;
    --dark-bg: #1e293b;
    --card-bg: #334155;
    --text-primary: #f8fafc;
    --text-secondary: #cbd5e1;
    --text-muted: #94a3b8;
    --border-color: #475569;
}
Adding New Charts
To add a new chart:

Add a new canvas element to your HTML:
html<canvas id="myNewChart"></canvas>

Initialize it in your JavaScript:
javascriptconst newChartCtx = document.getElementById('myNewChart').getContext('2d');
const newChart = new Chart(newChartCtx, {
    // Chart configuration here
});


Browser Compatibility

Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)
Opera (latest)
Mobile browsers (iOS Safari, Android Chrome)

Performance Considerations

The dashboard uses inline SVG icons instead of an icon font to reduce HTTP requests
Charts are rendered efficiently using the Canvas API
Minimal JavaScript dependencies (only Chart.js required)

Development Notes
Future Enhancements

Add data persistence with localStorage
Implement user authentication
Create additional portfolio visualization options
Add PDF report generation
Develop light/dark theme toggle

Credits

Chart.js - Used for data visualization
Feather Icons - SVG icons (manually included)
Google Fonts - Typography


Created with ❤️ by FAISAL FARAAZ SYED
