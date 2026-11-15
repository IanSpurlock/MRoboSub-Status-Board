# MRoboSub-Status-Board
## Situation
The demand for this project came from an issue that had to do with several features of the submarine having messy and/or crude solutioms:
1. The battery voltage monitor and display was a self-contained unit with a proprietary microcontroller that could not be communicated with.
2. An Arduino Mega was dedicated to the depth and hall effect sensors, which took up a lot of space for the task.
3. State-machine status LEDs were also connected to the Arduino, but they did not function.
## Task
The purpose of the status board is to fix and centralize these features to allow for space efficiency, simpler communication, and flexibility for future expansion.
## Action
I was initially the only team member assigned to this project. During this time, I explored the previous solutions and worked with other team members across electrical, software, and mechanical subteams in order to determine the requirements and specifications for the board. Next, I began sketching rough designs for the PCB. 
Then, another member was assigned to the project and they helped with making prototypes for each unit to ensure that the design would succeed. Once we had a full prototype, we created the actual PCB design and had it fabricated by JLCPCB. Upon the board arriving, we added the board's components and tested it.
