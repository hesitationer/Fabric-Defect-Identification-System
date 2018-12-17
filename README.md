# Fabric-Defect-Identification-System
Generate the file retrained_graph.pb(Refer in web) using Tensorflow library and training data-set(about 250 images) of non-defective fabric images.
The conveyor belt system has the fabric on it.
Connect the conveyor belt's motors to motor-driver and the motor-driver to arduino. Power the motor-driver from power-supply.
Connect arduino and camera to PC via USB.

Using the file retrained_graph.pb...Run the code python motor_cam_2_pattern_no_pat.py 
using the command: python motor_cam_2_pattern_no_pat.py

NOTE:
#if any usb problem arises in STEP 2, execute these two commands in terminal and try STEP 2 again...

sudo usermod -a -G dialout "USERNAME OF THE SYSTEM"
sudo chmod a+rw /dev/ttyACM0

Refer the ppt and https://www.linkedin.com/pulse/iiitdm-students-find-way-automate-fabric-inspection-placement-cell-/ for more details.




