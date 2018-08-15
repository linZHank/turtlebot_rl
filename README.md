# Setup Turtlebot Reinforcement Learning Simulation Environment
Assume you have set up an ros workspace at `/home/yourname/ros_ws`, and ready to config the environment in it. 


## Config Turtlebot
`$ sudo apt install ros-kinetic-turtlebot-gazebo`

## Config [openai_ros](http://wiki.ros.org/openai_ros)
`$ cd ~/ros_ws/src` <br/>
`$ git clone https://bitbucket.org/theconstructcore/openai_ros.git` <br/>
`$ cd ~/ros_ws && catkin build openai_ros` <br/>
`$ source devel/setup.bash` <br/>
`$ rosdep install openai_ros`

## Config OpenAI_ROS Examples
`$ cd ~/ros_ws/src` <br/>
`$ git clone https://bitbucket.org/theconstructcore/openai_examples_projects.git` <br/>
`$ cd ~/ros_ws && catkin build openai_ros` <br/>
`$ source devel/setup.bash` <br/>