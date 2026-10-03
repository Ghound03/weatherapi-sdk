# WeatherAPI Python SDK

An open-source Python SDK project for [WeatherAPI.com](https://www.weatherapi.com/), created using the Voxgig SDK Generator.

This project was created as part of an evaluation of the Voxgig SDK generation workflow and is licensed under the MIT License.

## API

WeatherAPI provides weather and geolocation data through a REST API, including:

- Real-time weather
- Weather forecasts
- Historical weather
- Marine weather
- Location search
- Time zone information
- Astronomy data

The API definition used for this project is Weather API version 1.0.2 (Swagger 2.0).

## SDK Generation

The project was scaffolded using the Voxgig SDK Generator with Python as the target language.

The API definition was supplied using:

```bash
npm create @voxgig/sdkgen -- weatherapi --def weatherapi.json --target py 

The generator successfully began creating the project structure, but encountered an issue when automatically running npm install.

