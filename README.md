# Laplace Transform
Modeling [mechanical](https://github.com/fardinabbasi/Laplace_Transform/blob/main/Part2.slx) and [electrical](https://github.com/fardinabbasi/Laplace_Transform/blob/main/Part1.slx) systems using Laplace transform in MATLAB.

## Part 1: Electrical System
Simulation of the following RLC Circuit Using the Laplace Transform.

<img src="/readme_images/rlc.jpg">

The relationship between the inductor's current $(I_L)$ and the input current $(I_s)$ is obtained using the Laplace transform through the following procedure.

<img src="/readme_images/kcl.jpg">

Finally, here is the final equation:
$$I_L = \frac{{128I_s - 128I_L}}{{s^2}} - \frac{{32I_L}}{s}$$

The **block diagram** below illustrates the system response when a step input is applied as the input current.

<img src="/readme_images/block.jpg">

## Part 2: Mechanical System
Simulation of the following Spring-Mass-Damper System Using the Laplace Transform.

<img src="/readme_images/damper.jpg">

