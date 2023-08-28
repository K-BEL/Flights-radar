# GeoFlightTracker

GeoFlightTracker is a Python project that focuses on retrieving, managing, and visualizing geographic location, airport, and flight data. The project is designed to provide insights into various aspects of geographical data, such as IP-based location, airport details, and real-time flight information.

## Features

- **Position Module**: Retrieve IP-based location data and convert longitude/latitude to X/Y coordinates.
- **Airport Module**: Load airport information from a CSV file, calculate X/Y coordinates, and focus on nearby airports.
- **Flight Module**: Interact with the OpenSky Network API to fetch real-time flight data, including position and attributes.

## Installation

1. Clone the repository: `git clone https://github.com/K-BEL/GeoFlightTracker.git`
2. Navigate to the project directory: `cd GeoFlightTracker`
3. Install required packages: `pip install -r requirements.txt`

## Usage

1. Open `main.py` to run the program.
2. The program will retrieve and display flight data using the OpenSky Network API.
3. Flight, airport, and location data will be visualized on a map.

## Configuration

- Modify API keys: If needed, update API keys in the appropriate modules.
- Adjust parameters: You can adjust the geographic parameters for airport and flight data retrieval in the respective modules.

## Credits

- IP-based location data retrieved using the ipinfo.io API.
- Airport data sourced from the provided CSV file.
- Real-time flight data fetched using the OpenSky Network API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

