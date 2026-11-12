# Blinkfire Frontend Interview: F1 Drivers Dashboard

**Task:**

Build a small dashboard that shows data from a Formula 1 race.

Code goes in `src/components/DriversDashboard.vue`

## Data

We'll use the [OpenF1 API](https://openf1.org/docs/).

## Part 1: API integration

Create a table of the drivers in the race.

- Base URL: `https://api.openf1.org/v1`
- Endpoint: `/drivers`
- Session: the 2026 São Paulo Grand Prix race, `session_key=11412`

**Requirements**

- Fetch the drivers from the API.
- Show these columns: Driver Number, Name, Team, Acronym.

## Part 2: Sorting and search

**Requirements**

- Add a "Sort by Name" button that sorts the drivers alphabetically.
- Add a search box that filters the table by driver name as you type.
