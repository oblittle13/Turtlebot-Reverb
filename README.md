# Turtlebot-Reverb
Combining the turtlebot and a reverb robotics board to hae open demos quickly and readily available for use

Getting started:
- Connect to Reverb board
  - add steps here
  - here as well

- Build a script that launches the following terminal screens
  - `` roslaunch rero_ros nlu.launch ``
  - On local machine (for working on project you'll need these as well)
  - `` roscore ``
  - In Reverb folder `` ./bin/rero_server ./bin/conf/config.ini ``
  - To check rostopic publisher `` rostpic echo /rero_ros/nlu_results `` **Need to fix this**

- How to actually launch
  - For now, just ssh into the turtlebot board (that will be connected to the turtebot laptop) and launch the nlu
  - Make sure that the nlu has been moved onto the board

- Things to do right now
  - Figure out how to connect to the board
  - Figure out how to have the subscriber built into the turtlebot python script
    - Get intent and entity to do a command on the turtlebot
  - Figure out how to write a script to automatically launch things
  - Figure out a better way to connect to the Reverb board (maybe over wifi? with a usb connector)
  
