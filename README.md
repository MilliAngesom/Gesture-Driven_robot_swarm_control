# How to run the file

- Clone the repo 
- roscore
- rosrun hri_sphero_stage start.py (Run the simulation)
- rosrun hri_sphero_stage call_without_face.py (Hand gesture and landmark detection)
- rosrun hri_sphero_stage control_swarm.py (Control the swarm)

# With face recognition 

Firstly, Install the face detection module with the command below

pip3 install face_recognition

Then, type the below commands on terminal

- roscore
- rosrun hri_sphero_stage start.py (Run the simulation)
- rosrun hri_sphero_stage face_recog_stream (For face recognition) (Dont forget to put your image in facemodel folder and replace the name in in the code)
- rosrun hri_sphero_stage call.py (Hand gesture and landmark detection)
- rosrun hri_sphero_stage control_swarm.py (Control the swarm)

<!-- ![Alt text](relative%20path/Images/Big_c.png?raw=true "Title") -->
<!-- ![Getting Started](sphero_stage/Images/Big_c.png) -->

# Equidistant points
<div style="text-align:center">
  <img src="sphero_stage/Images/Heart_curve.png" alt="Getting Started" width="500"/>
</div>

# Flowchart: Gesture-Driven Robot Swarm Control workflow
<div style="text-align:center">
  <img src="sphero_stage/Images/HRI flowchart.png" alt="Getting Started" width="500"/>
</div>

# Depth-Like Perception in Two Dimensions
<div style="text-align:center">
  <img src="sphero_stage/Images/Scaled.jpg" alt="Getting Started" width="500"/>
</div>

# Gesture Controlled patterns
<div style="text-align:center">
  <img src="sphero_stage/Images/collages_photos.jpg" alt="Getting Started" width="500"/>
</div>