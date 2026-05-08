# LaminarPipeflow
A verification study of incom
pressible, fully developed laminar flow in a circular pipe.  

The simulation performed in __Ansys Fluent__ is compared to the analytical Hagen–Poiseuille solution for velocity profile and pressure drop.

## 1. Problem Definition

<img width="1189" height="539" alt="Pasted image 20260507111542" src="https://github.com/user-attachments/assets/60136a45-0bf9-4677-bc17-b2c538a09ea8" />

The length of the pipe, L, is chosen such as to ensure fully developed flow at the outlet

**Flow Regime**  
The Reynolds number is defined as:

$$Re = \frac{\rho U D}{\mu}$$

, where 
- $D$ is the diameter of the pipe, 
- $\rho$ it the fluid density,
- $U$ is the __mean flow velocity__,
- $\mu$ is the __dynamic viscosity__.

The inlet velocity and fluid properties are chosen such that the Reynolds number as given by the equation above, is below 2300. Therefore, the flow remains strictly _laminar_

**Analytical Solution**   

The velocity profile is given by:

$$u(r) = U_{\max}\left(1 - \left(\frac{r}{R}\right)^2\right)$$

The pressure drop as given by the Hagen–Poiseuille equation is:

$$\Delta p = \frac{32 \mu U L}{D^2}$$

, where L is the length of the pipe.

Expression (1) and (2) serves as the reference for validation.
