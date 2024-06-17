Dynamic elevator system

System planning

The system consists of two main classes: building and elevator.

Building class

The building class represents the entire building and contains all its floors and elevators. Each building is defined with a number of floors and a number of elevators.
Floors: Each floor includes an elevator call control. Pressing the button will order the elevator to that floor.
Elevators: the list of elevators in the building. Each elevator is run independently but managed by the building to ensure optimal coordination.

Elevator class

The elevator class represents one elevator in the building and includes the following characteristics:
Current Floor: The floor where the elevator is currently located.
Elevator status: Is the elevator running, moving, or free.

system function

Call for an elevator: When a user presses the call button on a floor, a request is sent to the building to order an elevator.
Locating a nearby elevator: the building calculates which elevator is closest to the requested floor and sends it.

Screenshot:
![Main Screen](https://github.com/Sassi1000/ElevatorChallenge/blob/master/ScreenShot1.png)
