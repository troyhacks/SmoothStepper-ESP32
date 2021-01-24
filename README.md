
# EspSmoothStepper 
ESP32 smooth stepper library.

The aim of this library is to prevent rough speed evolutions.
The speed will evolve between 2 speed limits (min and max) which are specified by the user.
The acceleration will be calculated thanks the "ramp time", the time between these two speeds which is also specified by the user.

## Speed Evolution
![Alt text](SmoothStepper-ESP32/ressources/SpeedEvolutionChart.jpg?raw=true "SpeedEvolution")

## Position Evolution
![Alt text](ressources/PositionEvolutionChart.jpg?raw=true "PositionEvolution")

## Position Evolution comparison
![Alt text](ressources/Evolution plot.jpg?raw=true "EvolutionPlots")





