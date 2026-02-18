## FF Model

![](../../images/components/FF_Model.png)


Create a Fairyfly Model, which can be used for simulation. 



#### Inputs
* ##### shapes 
A list of honeybee Rooms to be added to the Model. Note that at least one Room is necessary to make a simulate-able energy model. 
* ##### boundaries 
A list of fairyfly Boundary objects to be added to the Model. Note that at least two distinct boundary conditions are necessary to make a simulate-able THERM model. 
* ##### name 
Text to be used for the Model name. If no name is provided, it will be "unnamed". 

#### Outputs
* ##### report
Reports, errors, warnings, etc. 
* ##### model
A Fairyfly Model object possessing all of the input geometry objects. 