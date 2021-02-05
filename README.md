# Fitts-Law-demonstration-in-python
Fitts' law states that the amount of time required for a person to move a pointer (e.g., mouse
cursor) to a target area is a function of the distance to the target divided by the size of the target.
Thus, the longer the distance and the smaller the target’s size, the longer it takes.
The mathematical formula behind Fitts’ law is :
                              
T (Time) = a + b log2 (2 D (Distance)/ W (Width)
➢ a : Start / Stop time of the device (y intercept)
➢ b : Inherent speed of the device (slope of line)
➢ D : Width of the target measured along the axis of motion, which corresponds to accuracy
➢ A : Distance from the starting point to the center of the target
The term log 2( 2D / W ) is called the index of difficulty (ID). It describes the difficulty of the
motor tasks.
                                                
GUI Designed to illustrate the Fitts’ Law :
  ➔ A circle will be displayed on the screen which is to be clicked as it appears.
  ➔ After clicking on the circle, another circle with random size, color and position will
  appear on the screen.
  ➔ This process repeats for 21 circles.
