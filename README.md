# Building_a_Gazebo_World

To Build

```
cd /location_of_the_project/Building_a_Gazebo_World
mkdir build
cd build/
cmake ../
make 
export export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/location_of_the_project/Building_a_Gazebo_World/build
```

To Run
```
cd /location_of_the_project/Building_a_Gazebo_World/world/
gazebo my_world.world
```
