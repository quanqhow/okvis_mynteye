

# okvis_mynteye

cd catkin_ws/src

git clone https://github.com/arjunskumar/okvis_mynteye.git

catkin_make --cmake-args -DCMAKE_BUILD_TYPE=Release

roslaunch mynt_eye_ros_wrapper mynteye.launch 
roslaunch okvis_ros okvis_node.launch 



