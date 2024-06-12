# RobustAdaptiveControl

The aircraft's short-period dynamics is given by:
```math
\begin{aligned}
& \left(\begin{array}{c}
\dot{alpha} \\
\dot{q}
\end{array}\right)=-\left[\left(\begin{array}{c}
\Z_alpha/V_0 \1+ Z_q / V_0 \\
M_alpha M_q \\
\end{array}\right) \times\left(\begin{array}{c}
alpha \\
q
\end{array}\right)\right]+\left(\begin{array}{c}
Z_dele \\
M_dele\\
\end{array}\right) \times dele 
\end{aligned}
```

References: 

[1] Lavretsky Eugene, Wise A. Kevin. Robust and Adaptive Control with Aerospace Applications. Springer, 2013.
