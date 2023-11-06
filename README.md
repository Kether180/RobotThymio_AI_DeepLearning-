# Robot_ThymioII: Deep Learning (Q-Learning Algorithm)

- piCamera + Lidiar Sensor + Thymio's Sensors
- Raspberry Pi 4

Q-learning is a machine learning approach that enables a model to iteratively learn and improve over time by taking the correct action. IT is also a type of reinforcement learning.

With reinforcement learning, a machine learning model is trained to mimic the way animals or children learn. Good actions are rewarded or reinforced, while bad actions are discouraged and penalized.

With the state-action-reward-state-action form of reinforcement learning, the training regimen follows a model to take the right actions. Q-learning provides a model-free approach to reinforcement learning. There is no model of the environment to guide the reinforcement learning process. The agent -- which is the AI component that acts in the environment -- iteratively learns and makes predictions about the environment on its own.


# Connect to Rasberry Pi Server

- username: pi

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

## Visualization gnu plot 

- run gnuplot

- load "simple_visualization.gnu"

# Lidiar Tests

cd distanceTestsLidiar

# Image Processing 

• cd image_processing : Image recognition, object detection, colour recognition.

# Simulation-Deep-Learning 

cd simulation-deepLearning > q-learning-simulation.py  

# Controller 

cd Controller  > Robot_Controller.py