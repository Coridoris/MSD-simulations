# MSD-simulations
Here we are going to perform simulations of confined Brownian motion trajectories and then calculate their MSD. 
The code is designed to be used in Colab and includes a function for simulating trajectories of confined Brownian motion (distribution). 

Initially, there is a plot with a simulation of MSD behind the measured MSD data. The measured data is imported from Drive and should be stored in a folder where each trajectory is saved as a separate .txt file (one column for x position and another for y position). The average MSD of the trajectories is calculated, and the MSD of each trajectory is plotted in the background in gray. The expected MSD for Brownian motion is plotted in yellow, and for confined Brownian motion in green. The area occupied by the average MSD from a number of simulations (n_simulations) is shown in red.
For the simulations, you can choose the number of simulations (n_simulations) and the number of trajectories in each simulation (n_trajectories, in this case 472 as that was the number of trajectories measured in our experiment). The maximum deviation of the simulated average MSD is calculated to plot the area it occupies.

Then, a separate graph is created to show the influence of the statistical sample size on the probability of obtaining an MSD close to the theoretical one. As the size of the sample set (n_trajectories) increases, it becomes more likely for the MSD to approach the predicted value from the model.
