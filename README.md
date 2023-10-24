# Robot_ThymioII, piCamera + Lidiar Sensor (Slam Simluation + controller)

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

# Thymio Speed and Angle Test

This test involves running the Thymio robot straight for 10 seconds and measuring both the distance it traveled and the off-angle.

## L(100, 100)R Speed Test, 10 seconds

- Distance: 32.5 cm
  - Angles:
    - Front of robot: 1 cm
    - Back of robot: 0.4 cm

- Distance: 33.1 cm
  - Angles:
    - Front of robot: 0 cm
    - Back of robot: 0 cm

- Distance: 33.2 cm
  - Angles:
    - Front of robot: 0 cm
    - Back of robot: 0 cm

- Distance: 33 cm
  - Angles:
    - Front of robot: 0.4 cm
    - Back of robot: 0.3 cm

- Distance: 33.2 cm
  - Angles:
    - Front of robot: 0 cm
    - Back of robot: 0 cm

## L(200, 200)R Speed Test, 10 seconds

- Distance: 64.3 cm
  - Angles:
    - Front of robot: -0.1 cm
    - Back of robot: -0.1 cm

- Distance: 64.1 cm
  - Angles:
    - Front of robot: 0.6 cm
    - Back of robot: 0.5 cm

- Distance: 63.8 cm
  - Angles:
    - Front of robot: -1.2 cm
    - Back of robot: -0.8 cm

- Distance: 64.5 cm
  - Angles:
    - Front of robot: 1.4 cm
    - Back of robot: 0.9 cm

- Distance: 65.2 cm
  - Angles:
    - Front of robot: 0.5 cm
    - Back of robot: 0.4 cm


# Lidiar Tests

cd distanceTestsLidiar

# Image Processing 

• cd image_processing : Image recognition, object detection, colour recognition.
