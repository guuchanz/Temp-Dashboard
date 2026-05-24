# Climate Analytics Dashboard

A high-performance, responsive weather visualization dashboard that fetches real-time meteorological data from the Open-Meteo API. This project provides detailed analytics for various Thai provinces, featuring interactive charts and comparative tools.

## 🚀 Features

- **Real-time Data**: Integration with the Open-Meteo API for accurate, up-to-date weather statistics.
- **Interactive Visualizations**: Powered by **Chart.js**, featuring data labels, tooltips, and smooth animations.
- **Province Comparison**: A dedicated comparison engine allowing users to overlay metrics from two different provinces on a single timeline.
- **Dynamic Metrics**: Switch between Temperature, Relative Humidity, and Wind Speed at the click of a button.
- **Customizable Timeframes**: Select specific start dates and view data over 3, 7, or 14-day periods.
- **Unit Conversion**: Seamless switching between Celsius (°C) and Fahrenheit (°F).
- **Glassmorphism UI**: A modern, clean interface built with **Tailwind CSS**.

## 🛠️ Technologies Used

- **Frontend**: HTML5, JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Charting**: [Chart.js](https://www.chartjs.org/) with the [datalabels plugin](https://chartjs-plugin-datalabels.netlify.app/)
- **Data Source**: [Open-Meteo API](https://open-meteo.com/)
- **Fonts**: Inter via Google Fonts

## 📦 Installation & Setup

Since this is a client-side application, no heavy backend installation is required.

1. Clone the repository or download the files.
2. Ensure the files are hosted on a local web server (e.g., Apache, Nginx, or VS Code Live Server) to avoid CORS issues when fetching data.
3. Open `index.html` in your preferred modern web browser.

## 📝 Project Structure

- `index.html`: The main entry point containing the UI structure and core logic.
- `.gitignore`: Standard exclusion list for Git version control.

## ⚖️ License

This project is open-source and available under the MIT License.

---
*Developed as a high-performance analytics tool for climate monitoring.*