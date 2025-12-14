# Data Weaver Dashboard

A comprehensive analytics dashboard that combines weather data and food order analytics to provide insights into business patterns and environmental correlations.

## Description

The Data Weaver Dashboard is an interactive web application that visualizes both weather information and food order data from Zomato. It helps identify potential correlations between weather conditions and food ordering patterns, providing valuable insights for business decision-making.

## Features

- **Real-time Weather Display**: Current temperature, humidity, and weather conditions
- **Interactive Charts**: 
  - Line chart showing food orders over time
  - Bar chart displaying temperature trends
- **Key Metrics**: Total orders and average temperature
  **Responsive Design**: Mobile-friendly interface that works on all devices
- **CSV Data Integration**: Automatic loading and processing of order data

## Data Sources

### Primary Data Sources
1. **Zomato Orders Data** (`data/zomato_orders.csv`)
   - Contains daily food order counts
   - Date range: January 2024
   - Fields: date, orders

2. **Weather Data** (Simulated)
   - Current weather conditions
   - 7-day temperature history
   - In production: Would integrate with weather APIs like OpenWeatherMap

### Sample Data Structure
```csv
date,orders
2024-01-01,45
2024-01-02,52
2024-01-03,38
```

## Tools and Technologies Used

### Frontend Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Grid and Flexbox layouts
- **JavaScript (ES6+)**: Data processing and interactive functionality

### Libraries and APIs
- **Chart.js**: Interactive chart library for data visualization
- **Fetch API**: For loading CSV data and future weather API integration
- **CSS Grid & Flexbox**: Responsive layout system

### Development Tools
- **Vanilla JavaScript**: No framework dependencies for lightweight performance
- **CSV Parser**: Custom implementation for data processing
- **Responsive Design**: Mobile-first approach

## Project Structure

```
├── index.html              # Main HTML file with dashboard layout
├── style.css               # CSS styling for responsive design
├── script.js               # JavaScript logic for data processing and charts
├── README.md               # Project documentation
├── data/
│   └── zomato_orders.csv   # Sample food order data
└── .kiro/
    ├── prompts.md          # AI assistant prompts
    └── context.json        # Project context configuration
```

## Getting Started

1. **Clone or Download**: Get the project files
2. **Open Dashboard**: Open `index.html` in your web browser
3. **View Data**: The dashboard automatically loads data from the CSV file
4. **Explore**: Interact with charts and view real-time weather simulation

## Future Enhancements

- Integration with real weather APIs (OpenWeatherMap, WeatherAPI)
- Additional data sources (delivery times, customer ratings)
- Advanced analytics (correlation analysis, predictive modeling)
- User authentication and personalized dashboards
- Export functionality for reports and data

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

This project is open source and available under the MIT License.