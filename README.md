# SLAM_Robot_ThymioII

# thymio

- username: pi

- Hostname: Robo

- kode: RoboRobo

# Connect to Rasberry Pi Server

- ssh pi@Robo.local

- Password : RoboRobo 

# Inside Rasberry Pi  (terminal 1)

- flatpak run --command=thymio-device-manager org.mobsya.ThymioSuite

# Inside Rasberry Pi (terminal 2)

- cd ~/BreezySLAM/python/breezyslam

- python3.11 SLAM.py

# visualizer (terminal 3 )

- cd visualizer 
- python3.11 Visualizer.py

# Adding files directly to the raspberry pi (simulators, controllers)

- run the server pi@Robo:
- open another terminal locally and run : scp <path_of_the_file> pi@192.168.0.11:/home/pi/
- add password : RoboRobo 
