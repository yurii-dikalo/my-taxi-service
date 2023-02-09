# 🚖 Taxi Service 🚖

## Project description

Taxi Service is a simple web-application that supports authentication and CRUD operations.

## Features

- registration like a driver
- authentication like a driver
- create/update/remove a manufacturer
- create/update/remove a car
- create/update/remove a driver
- display all manufacturers
- display all cars
- display all cars of current driver
- display all drivers

## Structure

In this project 3-layer architecture pattern with Controller <-> Service <-> DAO relations is used.

## How to start application locally

- Install Tomcat and MySQL.
- Use sql script init_db.sql from resources directory to create following tables: manufacturers, drivers, cars, cars_drivers.
- In ConnectionUtil class of util folder change URL, username and password to correspond with yours.
- Edit Tomcat configurations.
- Press run and enjoy the app!
- Should you have any questions, please contact me. 
- May I have the benefit of your thoughts on how to improve the app? Your feedback would be helpful :) 
