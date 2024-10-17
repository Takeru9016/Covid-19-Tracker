# Covid-19 Tracker

This project is a React-based COVID-19 tracking application that displays real-time updates on COVID-19 cases worldwide. Users can view global and country-specific case data, along with detailed visual representations via charts and maps.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Real-Time Case Tracking**: View live COVID-19 statistics including total cases, recoveries, and deaths.
- **Country-Specific Data**: Check country-wise statistics using clickable markers on an interactive map.
- **Dynamic Line Charts**: Track trends over time for Covid-19 cases with interactive line charts.
- **Map Visualization**: Visual representation of Covid-19 data on a world map with country-specific stats.

## Technologies

- **Frontend**:
  - React.js
  - Material-UI (for styling and UI components)
  - Chart.js (for charting Covid-19 data trends)
  - Leaflet (for rendering the interactive world map)
  
- **Backend**:
  - Firebase (for deployment and hosting)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Takeru9016/Covid-19-Tracker.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Covid-19-Tracker
   ```
3. **Install the dependencies**:
   ```bash
   npm install
   ```
4. **Run the application**:
   ```bash
   npm start
   ```
   This will start the development server. To view the app, navigate to `http://localhost:3000` in your browser.

## Usage

1. **View Global Stats**: The app displays global Covid-19 cases, recoveries, and deaths at a glance.
2. **Search for Specific Countries**: Use the map or search functionality to view Covid-19 data for individual countries.
3. **Visualize Trends**: The line chart shows how cases, recoveries, and deaths have changed over time.

## Contributing

Contributions are welcome! If you'd like to improve the project or fix bugs, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.
