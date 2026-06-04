# WeatherRadar Rainmeter Skin

A lightweight Rainmeter weather widget built for Windows 11 styling.

## Features
- Default location: Berlin, Germany
- Uses Open-Meteo to fetch current temperature, weather condition, and rain probability
- No system location access required
- No admin rights required
- Editable custom location via configuration file

## Installation
1. Copy the `WeatherRadar` folder into your Rainmeter `Skins` directory.
2. In Rainmeter, refresh all or refresh the `WeatherRadar` skin folder.
3. Load `WeatherRadar.ini`.

## Configure your location
1. Click `Edit location` on the skin.
2. Update `LocationName`, `Latitude`, and `Longitude` in `@Resources\Settings.inc`.
3. Save the file.
4. Refresh the skin in Rainmeter.

## Default values
- `LocationName=Berlin, Germany`
- `Latitude=52.5200`
- `Longitude=13.4050`
- `UpdateInterval=600` (10 minutes)

## Notes
- The skin does not require admin privileges to run.
- If you prefer another location, enter coordinates manually.
