# obelisk-api

RESTful API for the Obelisk Project in EngSciMath.

## About Obelisk

Obelisk is an attempt to create an alternative to the market for operating an economy. It works by modeling the economy as a set of recipes (eg, to make 3 books you need 5 papers and 0.5 electricity), each connecting to pools of resources, and attempts to figure out how these resources should be allocated to maximize utility (goodness, as numarically defined). Mathematically, this falls under operations research — usually either linear programming or, more generally, convex optimization, though there's also the more pragmatic problems of collecting and dispatching data, which this project also tackles.

Right now, the architecture consists of Obelisk-Planner, which does the math, and Obelisk-API, which will communicate with planned future user intefaces. Both will draw from and write to a central SQL database.
