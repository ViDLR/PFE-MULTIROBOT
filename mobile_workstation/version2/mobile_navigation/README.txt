
ps aux | grep -i apt
sudo kill -9 {nb du processus}
ou
sudo killall apt apt-get

sudo apt-get install ros-kinetic-kobuki ros-kinetic-kobuki-core
sudo apt-get install ros-kinetic-navigation
sudo apt-get install ros-kinetic-turtlebot
sudo apt-get install ros-kinetic-turtlebot-gazebo
sudo apt-get install ros-kinetic-turtlebot-msgs
sudo apt-get install ros-kinetic-turtlebot-apps

export ROBOT_INITIAL_POSE="-x 2.0 -y -3.0 -z 3.2"
