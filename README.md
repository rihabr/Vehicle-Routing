This project creates an optimal vehicle routing schedule based on real data and a real-world scenario faced by a logistics company. This project was completed in partnership with the logistics company as well as fellow MIT colleagues.

The aim was to decide which pickup stops would be on which route, the order of the stops, and the arrival time. This was subject to constraints such as traveling to all the stops, number of cars, start and end locations, availability windows.

There were multiple components to this project:

(1) Clean data in order to derive list of pickup stops and average daily demand per pickup stop (R)
(2) Obtain travel distance between all pickup stops using Google Maps API (JavaScript)
(3) Formulate optimization model (Julia, JuMP, Gurobi)
(4) Visualize the routes suggested by the model (Tableau)
