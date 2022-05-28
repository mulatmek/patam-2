Flight Simulator Control:

This is a project we developed during our advanced software programming course in our 2nd year. 
we separate our project to three main parts .

Agent :

To use the agent we need to connect to it through the server of the flight simulator through the terminal. by using the comand //**Need to add the command//

in this section we create agent for each flight, The agent controls through the movement of the aircraft.

client-side :

Responsible for showing the aircraft map in real time, the monitor panel of all flights, data on each flight, reconstruction of each flight and presentation of the flight

server-side(beckend):

The server side will contain two layers:
1. Mvc layer
2. Worm layer
In addition, we will maintain a sql database with flight data for statistical research.
The server side serves as an intermediary between the agent and the client (in a two-way way). In addition responsible for statistical calculations and retention of information received from the agent.
The server side is the only one with access to the database and it is done with the help of the orm layer.
The orm layer is a layer that allows us to maintain object-oriented programming principles and will serve as an api that will allow us to extract from the database any information we want.

The mvc layer:
Model - will contain the worm layer which is accessible to the database.
It will also contain the simple interpreter which interprets all the parts of the aircraft and how the aircraft actually moves.

View -
The view layer will contain the cli which will be used as a tool with basic functionality that supports capabilities such as: reset, to-do list and list of all open processes. And other parameters decided upon later.
Controller -
Will handle the requests of the agent and the frontend in addition will perform the tasks in parallel programming.
We will use active object design templates, command pattern

 




