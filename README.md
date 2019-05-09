# [Weather-Forecast](https://tonik1204.github.io/weather-forecast/)

<!-- TOC -->

Responsive single HTML page displaying a 5 day weather forecast.

- App was created with help of `Create React App`.

- Technology stack used: `React(Hooks), Typescript, styled-components, webpack, npm, axios, moment`.

- API used: [weather-forecast](`https://openweathermap.org/forecast5`), [city-finder](`https://developers.teleport.org/api/`).

Current solution is fully responsive and fits all modern browsers.

## Init

<!-- TOC -->

To start project locally just run `npm install` and then `npm start`, or if you preffer `yarn install` and `yarn start`.

No need to do additional `build` steps, http://localhost:3000/ should be opened automatically in your browser with current page.

To test project run `npm test` or `yarn test`.
Next please follow the instructions in your terminal:

```sh
Watch Usage
 › Press a to run all tests.
 › Press f to run only failed tests.
 › Press q to quit watch mode.
 › Press p to filter by a filename regex pattern.
 › Press t to filter by a test name regex pattern.
 › Press Enter to trigger a test run.
 ```

### The Demo of the project: [weather-forecast](https://tonik1204.github.io/weather-forecast/)

## Motivation

<!-- TOC -->

There are a lot of weather forecast apps with lots of data indicators and parameters. This is most simple and fast solution, based on new React Hooks API. Due to lack of possibility right now to try it on a real project, the curent app looks the best fit.

## Next steps

<!-- TOC -->

### TODO List:

* [] Fully cover code with unit and integration tests.
* [] Include IE 11 support.
* [] Add weather map with help of [weather-map-api](https://openweathermap.org/api/weather-map-2).
* [] Add 16 day / daily weather forecast with help of [weather-forecast-16](https://openweathermap.org/forecast16).
* [] Add login/logout/register system and integrate with some analytical tool.
