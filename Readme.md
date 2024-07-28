<div align="center">

# ZeoWeather

</div>

This repository contains a full-stack project developed using the MERN stack (MongoDB, Express.js, React, and Node.js) that fetches local weather data from weather API and displays it on the dashboard. Moreover it includes following features as well :-

1. Daily Weather Summary:
○ Roll up the weather data for each day.
○ Calculate daily aggregates for:
■ Average temperature
■ Maximum temperature
■ Minimum temperature
■ Dominant weather condition (give reason on this)
○ Store the daily summaries in a database or persistent storage for further analysis.
2. Alerting Thresholds:
○ Define user-configurable thresholds for temperature or specific weather conditions (e.g., alert if temperature exceeds 35 degrees Celsius for two consecutive updates).
○ Continuously track the latest weather data and compare it with the thresholds.
○ If a threshold is breached, trigger an alert for the current weather conditions.
Alerts could be displayed on the console or sent through an email notification
system (implementation details left open-ended).
3. Implement visualizations:
○ To display daily weather summaries, historical trends, and triggered alerts.


## Frontend

The frontend of this project is meticulously crafted using React, a powerful JavaScript library. It serves as the backbone of the application, handling routing and rendering of multiple sub-components, including the visually appealing dashboard page, welcoming page, and the intuitive login/register pages. These pages are thoughtfully designed utilizing a blend of HTML, CSS, and JavaScript, ensuring an engaging and seamless user experience.

To fetch data from the Weather API and interact with the MongoDB database, the project leverages the Axios library. Axios provides a convenient and efficient way to make GET/POST requests, facilitating the retrieval and manipulation of data in a secure manner. By integrating Axios, the frontend seamlessly communicates with the backend, enabling smooth data exchange between the application and external APIs.

## Backend

The backend of this project is built using Express.js and Node.js, serving as a robust bridge between the React frontend and the database. It enables seamless communication and facilitates the retrieval of weather data by leveraging Express's powerful GET/POST functionality.

For efficient data storage and management, the project utilizes a MongoDB database hosted on MongoDB Atlas. The database consists of four collections: "Active Users" for currently logged-in users and "Registered Users" for storing details of registered users like name, email, password, and city, "Daily Weather Data" to store Daily aggregates and rollups, "Hourly Weather Data" to store Hourly temperatures and others.

## Installation and Setup


# Running App

**Backend-side Application**

```bash
  cd backend
```

```bash
  npm install
```

```bash
  npm run dev
```

**Client-side Application**

```bash
  cd server
```

```bash
  npm install
```

```bash
  npm start
```



## Tech Stack

**Frontend:** React

**Backend:** Node, Express 

**Database:** MongoDB


## Feedback

If you have any feedback, please reach out to me at ahujad2808@gmail.com


## Installation

Install WeatherSense with npm after cloning the project

```bash
npm Install
```
    
## Documentation

[React Framework](https://react.dev/)

[Express JS](https://expressjs.com/)

[MongoDB](https://www.mongodb.com/)

[Axios](https://axios-http.com/)
