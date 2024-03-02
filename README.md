# Sun Weather App

The **Sun Weather App** is a Go application designed to retrieve weather information for a specified location using the Weather API. It displays the current temperature, condition, and an hourly forecast.

## Building and Installing

1. Ensure you have Go installed and configured on your machine.
2. Clone this repository: `git clone https://github.com/yourusername/sun.git`
3. Navigate to the cloned directory: `cd sun`
4. Build the application: `go build`
5. Move the resulting executable to a directory in your PATH, such as `/usr/local/bin`:
   - Make sure to replace `sun` with the actual name of the compiled binary.
6. Set appropriate permissions: `sudo chmod +x /usr/local/bin/sun`

## Usage

To use the Sun app, open a terminal and type:

```bash
sun [location]
```

Replace `[location]` with your desired location (e.g., "New York" or "London"). If no location is provided, the app defaults to Winnipeg.

## Output

The app displays the following weather information:

- Location name and country
- Current temperature (in degrees Celsius) and weather condition
- Hourly forecast for the day, including:
  - Time
  - Temperature (in degrees Celsius)
  - Chance of snow
  - Feels-like temperature (in degrees Celsius)
  - Weather condition

For temperatures below -10°C, the forecast will be displayed in red for better visibility.

## Note

To use the Weather API, you'll need to sign up and obtain a unique API key. Replace the placeholder API key in the source code with your own to ensure the app functions properly.
