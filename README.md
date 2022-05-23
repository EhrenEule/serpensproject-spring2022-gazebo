# serpensproject-spring2022-gazebo

This project contains the gazebo model for the serpens robot.

### How to use the software

roslaunch serpent_gazebo serpent2.launch 

This will launch the gazebo world and start the controllers.
The model will then listen to messages on a rostopic. You can publish messages on the rostopic manually through the command 'rostopic pub' 
or you can use the following github repository https://github.com/EhrenEule/serpensproject-spring2022.
