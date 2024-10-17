# Track to Walk

This project is a web-based application that tracks and displays the user's current geographical position on a map in real time. The user can view details such as latitude, longitude, speed, and heading, and their path is drawn on the map as they move.

## Features
- **Real-time Position Tracking**: Uses the browser's Geolocation API to track the user's position in real time.
- **Google Maps Integration**: Displays the user's current location and tracks their movement on a Google Map.
- **Path Drawing**: As the user moves, the path they take is shown on the map with a polyline.
- **Location Details**: Shows details such as latitude, longitude, altitude, speed, and heading.

## How It Works
1. **Geolocation**: The app uses `navigator.geolocation.watchPosition()` to continually get the user's position.
2. **Google Maps**: The Google Maps JavaScript API is loaded dynamically and initialized with a default zoom level and center.
3. **Path Tracking**: Each new position is added to an array that stores the path, and a polyline is drawn on the map to represent the user's journey.
4. **Details Display**: The `#details` div shows updated information about the user's accuracy, location, altitude, heading, and speed.

## Usage

1. Open the HTML file in a browser.
2. Allow the browser to access your location when prompted.
3. Watch as your location is tracked and displayed on the map, with your path drawn in red.

## Requirements

- A modern browser with support for the Geolocation API.
- An active internet connection to load the Google Maps JavaScript API.

## Setup

1. Clone the repository or download the HTML file.
2. Replace the `YOUR_API_KEY` in the script URL with your Google Maps API key.
3. Open the HTML file in your browser.

## Important Notes

- This project uses the Google Maps API, so you need to have an API key with the appropriate permissions.
- Geolocation tracking accuracy depends on the device and browser being used.

## License

This project is licensed under the MIT License.
