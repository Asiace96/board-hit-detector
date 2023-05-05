# board-hit-detector 
Small script for visuazlizing where the ball hit the board in real time for final project of robot juggling arm in univeristy.

The setup is a board with 4 microphones (2 for the x and y axes respectively), connected to an arduino board.

 By measuring the time difference between the arrival of the signal (the peak of the amplitude for a threshold voltage we determine) for each microphone pair and mapping it to the location on the board we can determine where the ball hit the board it real time.

 This information will be parsed and sent to the controller of the robot arm for closed loop feedback control.