# Airlines

## Description

Let's assume that we have a set of airports for which we know the code (ID), city, and country in which it is located, as well as the longitude and latitude. This information is stored in the file airports.csv. There is also a list of available airlines and information about them (code and name) in the file airlines.csv. Finally, the file flights.csv specifies possible flights between airports using the specified airline. The Graph.h library provides a variety of functions that allow retrieving various information from these three files.

## Features

The library implements the following functions:

1. Shortest distance between two nodes. The distance is defined as the number of flights. A node can be an airport, city, or country. The function also allows displaying the path (or paths if there are multiple) that provides this shortest distance. If paths do not exist, the function will return -1 and an empty list of paths.
2. Shortest distance between two coordinates. Given two pairs of points and radii around these points. The function returns the distance between two airports, where the first airport is within the radius from the first point, and similarly for the second airport from the second point.
3. Shortest distance to airports from a specified airport. The distance is defined as the number of flights.
4. The number of airports within a specified radius from a given coordinate.
5. Shortest distance from a node to a coordinate. The distance is defined as the shortest number of flights from a specified airport to the nearest airport to the given point.
6. Shortest distance between two nodes, where the distance is defined not by the number of flights but by changing the airline.
7. List of airports within a specified distance. The distance is defined as the number of flights.
8. Shortest distance between nodes, where only the specified airlines can be used.
9. Shortest distance between nodes, where the same airline cannot be used two or more times in a row.

## Installation

1. Clone this repository
2. Add files to your project directory
3. Include Graph.h file to your source file.

## Contact

r.gabdullin@innopolis.university
