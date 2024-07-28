<div align="center">

# RuleEngine

</div>

This repository contains a full-stack project developed using Node.js with TypeScript, Next.js with TypeScript, and PostgreSQL with Prisma. The project focuses on creating a Rule Engine with Abstract Syntax Tree (AST) for defining and evaluating complex business rules. Moreover it includes following features as well :-

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

The frontend is built using Next.js with TypeScript, providing server-side rendering and static site generation. It includes pages for managing rules and visualizing rule evaluations.

Next.js: Handles routing and rendering of components.
TypeScript: Ensures type safety and better development experience.
Styled Components: For styling the application with ease.

## Backend

The backend is developed using Node.js with TypeScript, acting as the core engine for rule evaluation and management. It interacts with the PostgreSQL database using Prisma.

Node.js: Provides a robust and scalable runtime environment.
TypeScript: Ensures type safety and maintainability.
Express.js: Handles API requests and serves the frontend.
Prisma: ORM for PostgreSQL, enabling efficient data querying and management.

## Database

The project uses PostgreSQL for reliable and efficient data storage. Prisma ORM is used to interact with the database, providing a type-safe and intuitive API for database operations.

## Installation and Setup


# Running App

**Frontend-side Application**

```bash
  cd frontend
```

```bash
  npm install
```

```bash
  npm run dev
```

**Backend-side Application**

```bash
  cd backend
```

```bash
  npm install
```

```bash
  npm start
```

## Video Explanation Of The Assignment

Please visit : [Video Explanation](https://drive.google.com/file/d/1Gmr292HTE99D8xuSmoLqQz1bbKAwzD9h/view?usp=sharing).



## Tech Stack

**Frontend:** Next.js, TypeScript

**Backend:** Node.js, TypeScript, Express.js

**Database:** PostgreSQL, Prisma


## Feedback

If you have any feedback, please reach out to me at ahujad2808@gmail.com
