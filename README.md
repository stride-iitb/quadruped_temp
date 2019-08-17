# quadruped_temp

## Aim:
Learn how to use ros controls,etc. with this until the final model is made.

This has 2 branches-

1. <strong>init_branch - </strong>contains model only. (started work from here)
2. <strong> master -</strong> develop bot here.

# Quadruped_urdf3

This is a test model of our hound. It was exported from solidworks using sw2urdf add-in, after 2 unsuccessful attempts. (Hence, the 3)
Roslaunch the file launch/gazebo to spawn the model into an empty world

  ## How to make the model importable via gui-

  add the following to your ~.bashrc file-
  <strong>export GAZEBO_MODEL_PATH=<path/to/your/ws>/src/quadruped_temp</strong>
  and clone the repo inside your src folder of your workspace

  ## How to import the model via gui-

  Go to the insert tab and click on quadruped urdf under the path to your quadruped_temp folder
