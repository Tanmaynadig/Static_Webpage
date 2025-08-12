Advanced Currency Watch & Comparison App
This project is a static web application that provides a modern, interactive dashboard for tracking and analyzing foreign exchange rates against the Indian Rupee (INR). The application is built with vanilla JavaScript and styled with Tailwind CSS, and it leverages the TradingView Lightweight Charts™ library to deliver a professional charting experience.

The entire application is a single index.html file, designed to be hosted for free on services like GitHub Pages.

Features
This application is split into two main views:

1. Currency Dashboard (Main Page)
At-a-Glance View: Displays a grid of cards for popular currencies (USD, EUR, GBP, etc.).

Live Daily Change: Each card shows the current exchange rate against the INR and the daily movement (gain or loss) in both absolute and percentage terms.

Visual Indicators: Color-coded text (green for gain, red for loss) provides an immediate visual cue of the currency's performance.

Interactive: Clicking on any currency card navigates to a detailed analysis page.

2. Detailed Comparison View
Professional Charting: Features a large, interactive chart powered by TradingView's library that displays historical exchange rate data.

Switchable Chart Types: A "Terminal" button allows users to toggle between a smooth Area Chart and a simulated Candlestick Chart for more detailed analysis.

Dynamic Timeframes: Users can select various timeframes to view historical data, from 1 day (1D) up to 5 years (5Y) and all available data.

Performance Metrics: Displays the total percentage gain or loss for the selected currency and timeframe.

Interactive Tooltip: Hovering over the chart reveals a detailed tooltip showing the exact date and exchange rate for any point in time.

Technologies Used
HTML5: The structure of the web application.

Tailwind CSS: For modern, responsive styling.

Vanilla JavaScript (ES6+): For all application logic, including API calls and DOM manipulation.

TradingView Lightweight Charts™: For rendering the professional-grade financial charts.

Frankfurter API: A free and reliable API for fetching both latest and historical foreign exchange rates.