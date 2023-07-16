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

Furthermore, the simulation result obtained from **Simulink** is provided below.

<img src="/readme_images/s1.jpg">

## Part 2: Mechanical System
Simulation of the following Spring-Mass-Damper System Using the Laplace Transform.

<img src="/readme_images/damper.jpg">

The relationship between the input force $(F)$ and the output distance from the wall $(X)$ can be derived using the **Laplace transform** by following the procedure outlined below.

<img src="/readme_images/force.jpg">

The minimum value for parameter $B$, which ensures that the transfer function's poles are real, is 2.

$\Delta = B^2 - 4 \rightarrow \beta = B_{\text{min}} = 2$
