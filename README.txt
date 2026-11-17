# RideShare Simulation

A Java-based rideshare simulation that models passenger transportation along a linear road system. The program uses object-oriented programming to simulate cars picking up and dropping off passengers based on their destinations, travel directions, and vehicle capacity.

## Overview

The simulation consists of 32 stations along a straight road. Cars and passengers are randomly assigned starting locations and destinations, and cars travel along the road while picking up eligible passengers.

Each car has a maximum capacity of three passengers. Passengers can board a car only if they are traveling in the same direction and have not yet reached their destination.

The project explores how the number of available cars affects the percentage of passengers who successfully reach their destinations.

## Features

- **Object-Oriented Design:** Uses separate classes to represent cars, passengers, stations, and the road system.
- **Randomized Simulation:** Generates random starting locations and destinations for cars and passengers.
- **Passenger Management:** Handles passenger pickup and drop-off based on destination, direction, and available vehicle capacity.
- **Simulation Results:** Tracks the number of passengers who successfully reach their destinations.

## Technologies

- Java
- Object-Oriented Programming
- ArrayLists and Arrays
- Randomized Simulation

## Project Structure (File -> Description)
`Car.java` -> Represents vehicles, manages passenger capacity, and handles movement. |
`Person.java` -> Represents passengers and stores their starting locations and destinations. |
`Station.java` -> Manages passengers waiting at individual stations. |
`Road.java` -> Coordinates the stations, cars, passenger transportation, and simulation. |
`RideShareTester.java` ->  Runs the simulation and displays the results. |

## Results & Observations

To explore the relationship between vehicle availability and passenger transportation, I ran five simulations for each scenario with 50 passengers.

Number of Cars : Average Passengers Reaching Destination
20 : 38.0% 
40 : 44.4% 

The results showed a higher average passenger completion rate in the scenario with 40 cars compared to 20 cars.

Note: Results are based on five randomized simulation runs per scenario. Individual results may vary.
