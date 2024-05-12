# Map-navigation-with-ROS

Setup MapViz and close it
Run : sudo docker run -p 8080:8080 -d -t -v ~/mapproxy:/mapproxy danielsnider/mapproxy
Open MapViz

To publish GPS cordinates over ROS :
rostopic pub /novatel/fix sensor_msgs/NavSatFix "{latitude: 38.406222, longitude: -110.792027}"
