# Qubilo Weather App Challenge

## Overview

Welcome to the Weather Forecast App challenge! This challenge is designed to assess the skills of junior/mid-level front-end developers in React, custom hooks, lifecycle methods, programming logic, and styling.

## Challenge Description

You are tasked with building a simple Weather application using React. The application should allow users to enter a city name, and it will display the current weather conditions for that city.

### Requirements

1. **User Interface:**

   - Create a visually appealing and responsive user interface for the application. You can use any CSS framework or styling method you prefer. Tailwind has been installed. 

2. **Weather API:**

   - Utilize https://open-meteo.com/ to display countries current weather, time zone, latitude, longitude.

3. **Functionality:**

   - Implement a custom hook called `useWeather` that encapsulates the logic for fetching and managing weather data. This hook should provide the current weather data.

   - Use lifecycle methods (if using class components) or lifecycle equivalents (if using functional components) to manage data fetching and updates.

   - Handle errors gracefully. If the API request fails, display an error message to the user.

4. **User Input:**

   - Include a text input field where users can enter the name of the city for which they want to retrieve the weather. use countries_data.json to display those options on the input. 

   - Implement a search button or automatic submission to trigger the weather data fetching.

5. **Extra Features (Optional):**

   - Add a toggle for switching between Celsius and Fahrenheit temperature units.

   - Deploy the app and share the link. 

### Evaluation Criteria

Candidates will be evaluated based on the following criteria:

1. **React Knowledge:** Assess the candidate's ability to create functional and class components, manage state, and use lifecycle methods or hooks effectively.

2. **Custom Hook:** Evaluate the implementation of the `useWeather` custom hook, including its ability to handle data fetching, state management, and error handling.

3. **Programming Logic:** Examine how the candidate manages the data from the API response, including data parsing and error handling.

4. **Styling:** Evaluate the candidate's ability to create an attractive and responsive user interface.

5. **Overall Quality:** Assess the completeness, correctness, and functionality of the Weather Forecast application.

6. **Code Quality:** Look at the clarity, organization, and readability of the code, including naming conventions and comments.

## Getting Started

To get started with this challenge, clone this repository to your local development environment. You can use the following commands:

```bash
cd weather-forecast-app-challenge
npm install
npm run dev
