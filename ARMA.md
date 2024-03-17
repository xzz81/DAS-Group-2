# MA process  
## To MA(2)  
calculate ACF  


$$\gamma(\tau) = \text{cov}(X_t, X_{t+\tau}) = 
\begin{cases} 
(1 + \theta_1^2 + \theta_2^2)\sigma^2 & \text{for } \tau = 0, \\
(\theta_1 + \theta_1\theta_2)\sigma^2 & \text{for } \tau = \pm1, \\
\theta_2\sigma^2 & \text{for } \tau = \pm2, \\
0 & \text{for } |\tau| > 2.
\end{cases}$$

$$\rho_t = \gamma_t/\gamma_o$$

MA process is always stationary  

Use characteristic equations to solve Invertibility  

Use acf to determine the order

characteristic polynomial

test
