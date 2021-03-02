# Inverted Pendulum
A system which has it's centre of mass above it's pivot point. It is a highly unstable system (at topmost position). To prevent it from falling over, a controller is needed to 
balance the pendulum even in presence external disturbances (in the form of impulse / weight change / wind / etc.)

The mass may be distributed in the form of

1. A linear/nonlinear mass density rod
2. Concentrated in a solid shape and attached at the end of light rod

Firstly, in the IP_conc section, I will consider a system with mass concentrated in a ball attached at the end of rod joining pivot and the mass.

The controller in IP_conc/IP_1 section will aim to stabilise the above system in the vertically up position in the presence of impulse disturbance by use and tuning of an approporiate 
LQR controller.

The IP_conc/IP_2 section will use the PID controller.

The comparison of both controllers will be added in the following section upon completion - 
