This project creates an optimal vehicle routing schedule based on real data and a real-world scenario faced by a logistics company. This project was completed in partnership with the logistics company as well as fellow MIT colleagues.

The aim was to decide which pickup stops would be on which route, the order of the stops, and the arrival time. This was subject to business constraints such as traveling to all the stops, number of cars, start and end locations, availability windows.

There were multiple components to this project:

* Clean data in order to derive list of pickup stops and average daily demand per pickup stop (R)
* Obtain travel distance between all pickup stops using Google Maps API (JavaScript)
* Formulate optimization model (Julia, JuMP, Gurobi)
* Visualize the routes suggested by the model (Tableau)

Further details and findings froms the projects can be found in the final presentation file titled "Logistics Route Optimization - Presentation"
