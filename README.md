# Transport Board

A real-time public transportation departure board web application that automatically displays upcoming departures from the nearest station based on your current location.

## Features

- Geolocation-based: Automatically finds the nearest public transit station
- Real-time departure information: Shows the next 7 departures with accurate timing
- Responsive design: Optimized for various screen sizes with dynamic font sizing
- Live countdown: Updates continuously with a countdown to the next data refresh
- Visual indicators: Color-coded departure times (red for immediate, orange for soon, green for later)
- Clean, minimalist interface inspired by actual transport information displays

## How It Works

This application uses the Swiss public transport API (transport.opendata.ch) to retrieve real-time departure information. The workflow is:

1. Obtains the user's current location via browser geolocation
2. Finds the nearest public transit station
3. Fetches the upcoming departures from that station
4. Displays the information in an easy-to-read format
5. Automatically refreshes every 20 seconds

## Technical Details

- Pure vanilla JavaScript with no dependencies
- Responsive design using CSS variables and dynamic calculations
- Asynchronous data fetching with proper error handling
- Optimized for mobile devices and variable screen sizes

## Usage

Simply open the application in a modern web browser and grant location permissions when prompted. The app will automatically display departures from your nearest station.

## Privacy

The application only uses your location to find nearby stations. No location data is stored or transmitted beyond what's required for the API calls to function.

## API Credits

This project uses the Swiss public transport API provided by transport.opendata.ch, which is free to use for non-commercial purposes.

## Credits
- generated with the assistance of Claude 3.7 Sonnet, an AI assistant by Anthropic
