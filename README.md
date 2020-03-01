# Autonet Sim

```

      ___           ___           ___           ___           ___           ___           ___     
     /\  \         /\__\         /\  \         /\  \         /\__\         /\  \         /\  \    
    /::\  \       /:/  /         \:\  \       /::\  \       /::|  |       /::\  \        \:\  \   
   /:/\:\  \     /:/  /           \:\  \     /:/\:\  \     /:|:|  |      /:/\:\  \        \:\  \  
  /::\~\:\  \   /:/  /  ___       /::\  \   /:/  \:\  \   /:/|:|  |__   /::\~\:\  \       /::\  \ 
 /:/\:\ \:\__\ /:/__/  /\__\     /:/\:\__\ /:/__/ \:\__\ /:/ |:| /\__\ /:/\:\ \:\__\     /:/\:\__\
 \/__\:\/:/  / \:\  \ /:/  /    /:/  \/__/ \:\  \ /:/  / \/__|:|/:/  / \:\~\:\ \/__/    /:/  \/__/
      \::/  /   \:\  /:/  /    /:/  /       \:\  /:/  /      |:/:/  /   \:\ \:\__\     /:/  /     
      /:/  /     \:\/:/  /     \/__/         \:\/:/  /       |::/  /     \:\ \/__/     \/__/      
     /:/  /       \::/  /                     \::/  /        /:/  /       \:\__\                  
     \/__/         \/__/                       \/__/         \/__/         \/__/        liom  2020

```
### Launch
 * std_sim.launch - стандартный запуск Gazebo с полем 
 * nogui_sim.launch - no gui mode
 * rviz.launch - запуск rviz для симулятора 
 * spawn.launch - создание модели робота в сцене 
### Запуск 
```bash
roslaunch autonet_sim std_sim.launch
roslaunch autonet_r1 nav_sim.launch
roslaunch autonet_r1 lane_ros.launch
rosrun autonet_r1 <прога.py>
```
### Установка 
```bash
export ROS_PYTHON_VERSION=3
mkdir autonet_ws
cd autonet_ws
mkdir src
cd src
git clone https://github.com/vas59/autonet_sim.git
git clone https://github.com/vas59/autonet_r1.git
cd ../
catkin_make
```
Для работы необходимо прописать в .bashrc 
```bash
export ROS_PYTHON_VERSION=3
export PYTHONPATH=$PYTHONPATH:~/Projects/autonet_ws/src
source ~/autonet_ws/devel/setup.bash --extend
```


### Roadmap
#### TODO

\
by Vasily
```
    ___       ___       ___       ___   
   /\__\     /\  \     /\  \     /\__\  
  /:/  /    _\:\  \   /::\  \   /::L_L_ 
 /:/__/    /\/::\__\ /:/\:\__\ /:/L:\__\
 \:\  \    \::/\/__/ \:\/:/  / \/_/:/  /
  \:\__\    \:\__\    \::/  /    /:/  / 
   \/__/     \/__/     \/__/     \/__/  

```

