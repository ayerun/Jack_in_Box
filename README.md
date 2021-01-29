# Jack in Box Simulation
### Author: Arun Kumar

#### Usage Instructions:
1. Jack_Box.ipynb contains the full simulation in a jupyter notebook.
1. 3config.ipynb containst half the simulation in a jupyter notebook (jack moves box is stationary).
1. Animation must be run in a browser.
1. writeup.pdf describes the project and the math used.

#### Configuration Instructions:
1. Modify F matrix in Jack_Box.ipynb to modify external forces. Matrix is in form [Fx_jack,Fy_jack,T_jack,Fx_box,Fy_box,T_box].
1. Modify s0 array to change initial conditions. Array is in form [x_jack,y_jack,theta_jack,x_box,y_box,theta_box,vx_jack,vy_jack,w_jack,vx_box,vy_box,w_box].