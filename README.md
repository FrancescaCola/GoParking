# GoParking 🅿️🚗

GoParking is a small parking management system written in Python.  
It simulates a multi-level parking lot and allows users to:

## Features

- **Car Entry Management**
  - Register car plate and entry time
  - Ask for car brand (e.g. "Panda")
  - Automatically assign a parking level based on availability and brand
    - All Pandas are sent to the 5th floor (if available)
    - Other cars are placed on the most expensive available level

- **Car Exit Management**
  - Calculate total amount due based on entry time and hourly rate
  - Remove the car from the system
  - Update the current availability on the assigned level

- **Data Handling**
  - Uses Python dictionaries to simulate a dynamic database
  - Keeps track of each car's location and parking duration
  - Updates `cars_in` count for each level accordingly

## Technologies Used

- Python 3.x
- `datetime` module for time tracking


