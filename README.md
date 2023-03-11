# Tabula

Welcome to the Tabula repository! 

The actual code for Tabula is within two separate repositories: an Android frontend and a Python backend. The frontend and the backend communicate with each other through the Robot Operating System (ROS).

## Download and Run Tabula Source

Download code for each repository here:

Frontend: https://github.com/Wisc-HCI/TabulaUI

Backend: https://github.com/Wisc-HCI/TabulaSynthesizer 



You can find instructions for running Tabula within each of these repositories.


## Pre-built Version of Tabula

Included within this repository is a dockerfile that you may build and run.

```
sudo docker build -f dockerfile_synthesizer -t synthesizer_image .  # build
sudo docker run synthesizer_image bash run.sh  # run
```
