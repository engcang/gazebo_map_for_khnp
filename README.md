# Gazebo map for KHNP's KVRC competition
+ Season 1 - [map](https://youtu.be/6oXx2bvzU9Y), [github](https://github.com/Woojin-Seol/KVRC2021)
+ Season 2 - pending

## How to use
+ Clone the git
~~~shell
$ git clone git@github.com:engcang/gazebo_map_for_khnp
~~~

+ Add Gazebo Path
~~~shell
$ cd gazebo_map_for_khnp
$ echo "export GAZEBO_MODEL_PATH=:$GAZEBO_MODEL_PATH:$(pwd)/refracted_corridor_map:$(pwd)/rough_terrain_map:$(pwd)/stair_map:$(pwd)/qr_codes:$(pwd)/manipulator_map:$(pwd)/disturbance_map:$(pwd)/common" >> ~/.bashrc
$ . ~/.bashrc
~~~

+ Run Gazebo
~~~shell
$ roslaunch gazebo_ros empty_world.launch world_name:=$(pwd)/course_A.world
~~~
