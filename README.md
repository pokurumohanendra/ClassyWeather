# Classy Weather

A small React weather app. Type a location, press **Get Weather**, and see its daily forecast with the country flag next to the place name.

**Live demo:** [classy-weather6.netlify.app](https://classy-weather6.netlify.app/)

![Classy Weather](https://raw.githubusercontent.com/pokurumohanendra/My-Portfolio/main/public/projects/classy-weather.jpg)

## Features

- Look up any location by name
- Daily forecast showing the weather code with minimum and maximum temperatures
- Country flag shown beside the location
- No API key needed: it uses the free [Open-Meteo](https://open-meteo.com/) geocoding and forecast APIs

## Tech stack

React (class components), Open-Meteo APIs, Create React App.

## Getting started

You need Node.js (LTS).

```bash
npm install
npm start
```

| Script | What it does |
|--------|--------------|
| `npm start` | Run the development server |
| `npm run build` | Create a production build |
| `npm test` | Run the tests |

## Project structure

```
src/
├── App.js      main component and the Weather and Day components
├── Count.js    small practice component
└── index.css   styling
```

## Roadmap

- Map Open-Meteo weather codes to icons and descriptions instead of showing the raw code

## About

Built as a learning project to practise class components, lifecycle methods and fetching from two APIs in sequence.

## Author

[Pokuru Mohanendra](https://github.com/pokurumohanendra) · [LinkedIn](https://www.linkedin.com/in/pokuru-mohanendra/)
