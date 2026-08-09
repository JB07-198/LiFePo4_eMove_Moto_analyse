# Dashboard CSV File

This project contains a single HTML dashboard for visualizing electric motorcycle telemetry from a CSV file.

## Files

- `analyse_dashboard.html` — main dashboard page.

## Features

- CSV import and validation for telemetry data
- KPI strip with distance, speed, consumption, SOC, battery and GPS quality
- Charts for speed, altitude, power, SOC, cell balance, temperature and drive mode
- Interactive map view of the GPS track using Leaflet and OpenStreetMap

## Usage

1. Open `analyse_dashboard.html` in a modern browser.
2. Select a valid telemetry CSV file or continue with the embedded sample data.
3. The dashboard will render the route, metrics, and charts.

## Notes

- The map uses OpenStreetMap tiles via Leaflet.
- If you want to switch to Mapbox or Google Maps, update the map initialization in `analyse_dashboard.html`.
