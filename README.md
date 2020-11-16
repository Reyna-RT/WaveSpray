# WaveSpray
Data Repository for Droplets created from a Breaking Focusing Wave Train

This repository contains the results of experiments performed in the wave tank of the Hydrodynamics Laboratory of the University of Oslo.

The data of droplets dynamics after a breaking wave is obtained by means of 3DPTV. The data is stored in the file "particles056.csv"

This set of data is organized as a Pandas DataFrame containing the next labels:

- 'wind': speed of wind applied (0,5.2,6.2 m/s)

- 'A': maximum apmplitude o f the breaking wave (0.062, 0.075, 0.087 m)

- 'time': time where the droplet is presented (in seconds)

- 'x': position in x direction along the tank (in meters)

- 'y': position in y direction along the vertical axis (in meters)

- 'z': position in z direction perpendicular to the tank direction (in meters)

- 'u': velocity in the x direction (in m/s)

- 'v': velocity in the y direction (in m/s)

- 'w': velocity in the z direction (in m/s)

- 'acc_x': acceleration in the x direction (in m/s)

- 'acc_y': acceleration in the y direction (in m/s)

- 'size': Droplets equivalent diameter (in mm)
