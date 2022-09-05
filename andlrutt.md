# Summary
A workplace schedule-maker that takes employee availabilities and workplace needs and generates an optimal employee schedule.

# Problem
If a workplace manager is trying to work out the best way to schedule their employees, that could prove difficult. There could be employees that are only available during certain times, and employees that can perform certain roles, or multiple roles in a workplace, as well as there being varying demand for certain roles at certain times. With all of these variables, it is difficult to put together the best possible schedule by hand. That is what this project will solve.

## Features
- MVP
  - Enter and store the desired number of employees of different roles wanted for each shift for each day of the week
  - Enter and store employees, their roles, and their availability
  - Generate an optimal schedule based on workplace demands, employee roles, and employee availability  

- Stretch
  - Display the schedules for each individual employee in an embedded calendar
  - Create a larger, year-long schedule with employees having deviations from their regular availability
  - Support multiple users/workplaces with login/authentication

## Tech Stack
- Next.js/React
- MongoDB
- Google Calendar (maybe)

## Target
This will be made with restaurants in mind, but can be used in any workplace that has flexible scheduling and different roles within a single workplace.
