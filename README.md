# web_joy_ros2
## Quick Setup
Install Rosbridge
```
apt-get install ros-humble-rosbridge-suite
```
Jalankan di terminal 1
```
ros2 launch rosbridge_server rosbridge_websocket_launch.xml
```
Jalankan di terminal 2
```
ros2 run joy joy_node
```
Buka Website HTML, cek koneksi dengan 
```
ros2 topic echo /joy
```
