# WORK IN PROGRESS

# RobustAdaptiveControl

The aircraft's short-period dynamics is given by:
```math
\begin{aligned}
& \left(\begin{array}{c}
\dot{\alpha} \\
\dot{q}
\end{array}\right)=-\left[\left(\begin{array}{c}
\frac{Z_\alpha}{V_0} & 1+\frac{Z_q}{V_0} \\
M_\alpha & M_q
\end{array}\right) \times\left(\begin{array}{c}
\alpha \\
q
\end{array}\right)\right]+\left(\begin{array}{c}
\frac{Z_{\delta e}}{V_0} \\
M_{\delta e}
\end{array}\right) \times \delta e 
\end{aligned}
```
The lateral-directional models can be writtten as:





References: 

[1] Lavretsky Eugene, Wise A. Kevin. Robust and Adaptive Control with Aerospace Applications. Springer, 2013.
