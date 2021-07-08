# CMPLXSY-predation-system

*Developed by: Anjelo Antioquia, Erwin Chen, Gabriel Minamedez, Geosef Uy, and Richard Zapanta.*

This is an agent-based model that simulates a prey-predator ecosystem. In partial fulfillment of the Complex Systems (CMPLXSY) course in DLSU.

## Run this on your local machine 👨‍💻 
1. Download or clone this repository: ```git clone https://github.com/gabminamedez/CMPLXSY-predation-system.git```.
2. ```PredatorPrey.nlogo``` is the main file. If you have NetLogo installed, you can double click on the file to open and the interface should display.

## The Model
The model simulates a prey-predator ecosystem between two agents: the blue sheep (prey) and the red wolf (predator). They move within a green field wherein their lives are dependent upon sustaining their energy.

## The Agents
1. **Sheep** = To maintain their energy and stay alive, the sheep munch on the grass in the field. The grass turns black when eaten and regenerate after an amount of time.
2. **Wolves** = The wolves, meanwhile, munch on the poor sheep in their efforts to stay alive. ...and much like the grass, both sheep and wolf can reproduce.

## The Parameters
Upon launch, the model has severable configurable parameters, which are as follows:
1. **num-prey** = Initial number of sheep.
2. **num-predators** = Initial number of wolves.
3. **max-move** = Maximum randomness of movement.
4. **reproduction-chance** = Percentage that depicts the chance of reproduction for both prey and predator.
5. **food-growth** = Counter that signifies the time it takes for the grass to grow.