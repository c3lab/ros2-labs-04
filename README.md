# ros2-labs-04
This repository contains the material seen in the ros2-labs-04 lesson. <br>
In particular contains the examples for TF2 usage.

## Description of the workspace (as it should be :) )

- **docker_ws** folder: contains all the necessary docker files and scripts to build docker images.
- **ros_ws** folder: this folder will contain all the packages that we'll create. It is mapped inside our container with docker volumes.
- **chown_me.sh**: bash script to change the owner of files from root to user (just in case docker root user messes around with our files :) ).
- **run.sh**: bash script to run our container with all the capabilities and volumes that we need.
- **exec.sh**: bash script to open a shell to an already running container.

## details on the lab

will update this (contact me if I forgot )