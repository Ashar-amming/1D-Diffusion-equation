The one-dimensional diffusion equation is:


![image](https://github.com/user-attachments/assets/fa960e42-c622-4b89-a2e3-47db74a89ea8)


 We will discretize the second-order derivative with a Central Difference scheme: a combination of Forward Difference and Backward Difference of the first derivative.


 ![image](https://github.com/user-attachments/assets/f5c3134c-b2b7-4d45-bf2c-85bfa7383883)


discretized version of the diffusion equation in 1D:


 ![image](https://github.com/user-attachments/assets/bf946bd7-077d-4f81-ac5e-c33cd04a72da)


  re-arrange the equation solving for our unknown:


  ![image](https://github.com/user-attachments/assets/628dbbd0-131e-4086-a1c2-0cf3c0850b36)


The above discrete equation allows us to write a program to advance a solution in time. But we need an initial condition. Let's continue using our favorite: the hat function. So, at t=0 , u=2 in the interval 0.5≤x≤1 and u=1 everywhere else. 


