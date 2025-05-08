# COVID-19 Tracker

[React Covid Tracker Wire Frame](https://drive.google.com/file/d/1mxl5wv58Ro9HUmMRcCcHu2KFr-DmFnDL/view?usp=sharing)

<img src="https://github.com/AL-Kaisi/Covid_Tracker-using-ReactJs/blob/main/covid-19-tacker/public/covid%20Tracker.png" width="800" height="800">

The frontend design created using [react Material-UI: A popular React UI framework](https://material-ui.com/)

## Overview

A real-time COVID-19 tracking application built with React.js that provides up-to-date statistics on coronavirus cases worldwide. This project was developed during the global pandemic to help visualize and understand the spread of the virus across different countries.

[Website Live Demo](https://covid-19-tracker-9d33b.web.app/)

## Features

- **Global Statistics**: Track total cases, recoveries, and deaths worldwide
- **Country-Specific Data**: Filter statistics by country with an interactive dropdown
- **Interactive Map**: Visualize the spread with a responsive map interface
- **Historical Data**: View trends over time through intuitive charts and graphs
- **Mobile Responsive**: Fully optimized for all device sizes

## Technologies Used

- **React.js**: Frontend library for building the user interface
- **Material-UI**: React component library for design consistency
- **Chart.js**: JavaScript charting library for data visualization
- **Leaflet**: Open-source JavaScript library for mobile-friendly maps
- **Disease.sh API**: Open API for disease-related statistics
- **Firebase**: Hosting platform for the live application

## Data Source

This application uses the disease.sh API to fetch real-time COVID-19 data:
- Global statistics
- Country-specific information
- Historical data for trend analysis

## Getting Started

### Prerequisites

- Node.js (v12.0 or later)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AL-Kaisi/Covid_Tracker-using-ReactJs.git
   cd Covid_Tracker-using-ReactJs
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
├── covid-19-tacker/
│   ├── public/
│   │   ├── covid Tracker.png
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── src/
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── LineGraph.js
│   │   ├── Map.css
│   │   ├── Map.js
│   │   ├── Table.css
│   │   ├── Table.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── infoBox.css
│   │   ├── infoBox.js
│   │   ├── reportWebVitals.js
│   │   └── util.js
│   ├── .firebase/
│   ├── .github/
│   │   └── workflows/
│   │       ├── firebase-hosting-merge.yml
│   │       └── firebase-hosting-pull-request.yml
│   ├── node_modules/
│   ├── .eslintcache
│   ├── .firebaserc
│   ├── .gitignore
│   ├── README.md
│   ├── firebase.json
│   ├── package-lock.json
│   ├── package.json
│   └── yarn.lock
```

## Application Wireframe

The application follows a clean, intuitive design focused on data visualization and user experience:

- Top section: Global statistics in card format
- Middle section: Interactive country selector and detailed statistics
- Bottom section: Geographical representation with interactive map
- Trend analysis: Historical data visualization with line graphs

## How It Works

1. **Data Fetching**: The application connects to the disease.sh API to retrieve the latest COVID-19 statistics
2. **State Management**: React's state management handles the dynamic data and user interactions
3. **Visualization**: Data is transformed into visual representations using Chart.js (LineGraph.js) and Leaflet map (Map.js)
4. **User Interface Components**:
   - InfoBox.js: Displays key statistics in card format
   - Table.js: Shows country-specific data in a sortable table
   - Map.js: Renders an interactive geographical representation
   - LineGraph.js: Creates trend visualizations over time
5. **User Interaction**: Users can select different countries to view specific statistics and trends
6. **Deployment**: The application is deployed using Firebase hosting with GitHub Actions workflows for CI/CD

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

- **Mohamed Alkaisi** - [AL-Kaisi](https://github.com/AL-Kaisi)

## Acknowledgements

- [Disease.sh](https://disease.sh/) for providing open access to COVID-19 data
- [Material-UI](https://material-ui.com/) for the React components
- [React.js](https://reactjs.org/) team for the amazing library
- All frontline healthcare workers fighting the pandemic

---

*This project was created to help visualize the impact of COVID-19 and provide easily accessible information during the global pandemic.*
