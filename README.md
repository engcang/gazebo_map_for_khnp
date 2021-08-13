# gazebo_map_for_khnp
gazebo_map_for_khnp


## How to use
+ Clone the git
~~~shell
$ git clone git@github.com:engcang/gazebo_map_for_khnp
~~~

+ Add Gazebo Path
~~~shell
$ cd gazebo_map_for_khnp
$ echo "export GAZEBO_MODEL_PATH=:$(pwd)/map_four:$(pwd)/map_one:$(pwd)/common"
$ . ~/.bashrc
~~~

+ Run Gazebo
~~~shell
$ roslaunch gazebo_ros empty_world.launch world_name:=$(pwd)/competition_one.world
~~~
