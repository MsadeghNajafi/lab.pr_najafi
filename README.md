**the title of project:Footballer robots**
**developer:Mohammadsadegh Najafi and Mohammadhosein fatehi **
**The project included two robots.
**forward robot that was in charge of sadegh and a defender robot that was in charge of hosein.because webots dont work in  my laptop i do this project with mrabbasalipoor.**
In the relevant code, the movement of the robots is controlled by implementing the PID class.This is impelimented in PID.py .
Both angular and linear velocities are controlled by controllers.
The P controller has low speed and accuracy because its speed decreases as the robot approaches the desired state.
The integrator is used to improve the accuracy and the derivative is used to improve the speed of reaching the desired state.Due to the derivative property in increasing noise, a filter has been used next to it.
All controllers are discrete by the backward discretization method.In this way, the iddar controller may become unstable, but instability does not become stability.
The strategy of the attacking robot is that it is constantly chasing the ball and the defending robot goes to the goal after the start of the game and after settling there, follows the angle of the ball.
