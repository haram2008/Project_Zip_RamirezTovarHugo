# Project_Zip_RamirezTovarHugo
Formula 1 and the art of aerodynamics
	Author: 	"Hugo Andres Ramirez Tovar"
	Date: 		"2025-11-21"        
	University: 	Florida Politechnic University 
	Email:		haramireztovar3473@floridapoly.edu
	StudentID:	3473
--------------------------
FILES
--------------------------
1. F1_race_traces.csv (23 variables, 878 observations)
2. constructors_wind_tunnel.csv (6 variables, 10 observations).
--------------------------
OTHERS
--------------------------
1. Data dictionary

The "F1_race_traces" dataset includes variables such as race results, race locations, team, driver's and his position and time, with summary of the condition in which each driver finished the race. These variables are divided into two types: character and numeric.

The variables for type character including:
circuit(combining urban tracks, historical routes and spectacular settings),
Track(track limits'),
Drivers(official name of pilot number),
surname(official last name of pilot number),
constructor(official number of team),
Team(official name of team),
positionText(position of race),
time(real-time of race),
fastestlapTime(faster turnaround time)",
status(race status).

The set of numerical data in my database is made up of the following data:
results (Id Dataset),
year (year the datos),
round (race classification round),
No of Drivers(official pilot number),
grid(position of the cars on the circuit),
position(starting position),
positionOrder(order in which the drivers are classified on the grid),
points(points system),
laps(turning removal procedures),
miliseconds(duration of races and pit stops),
fastestLap(faster turnaround time),
rank(driver classification),
fastestlapSpeed(fastest race time).
 
The "f1_wind_tunnel" dataset includes variables such as constructor position, the team, the nationality of the team with summary of the income that every team had and their wind tunnel hours. These variables are divided into two types: character and numeric.

The variables for type character including:
constructor (the official identifier of the racing team),
Team (the official name of the constructor),
nationality (the country of origin associated with the team),

The set of numerical data in my database is made up of the following data:
constructor position (the team's ranking in the constructor standings
tunnel_hours (the number of hours allocated for wind tunnel testing)
income_2024 (the projected or reported income for the 2024 season)
