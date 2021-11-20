# Bixler_Ardupilot_orbit_wind
Bixler_Ardupilot_orbit_wind

This is a Matlab implementation of an ArduPilot low level controller (i.e. roll, pitch, yaw and total energy control system) combined with a vector field guidance law.

The resulting autopilot has been designed and tuned on Bixler2 type of UAV (fixed-wing UAV). The model of the UAV is designed in Matlab including propulsion dynamics, aerodynamics and actuator dynamics. The gains of the PID controllers have been designed and tested on an actual Bixler2, i.e. the gains are the result of the AutoTune procedure of ArduPilot

"Automatic tuning with AutoTune," https://ardupilot.org/plane/docs/automatic-tuning-with-autotune.html

The initial version of this code was developed within the thesis project:

Stefano Farì, “Guidance and control for a fixed-wing UAV”, MSc Thesis for Automation and Control Engineering at Politecnico Milano, 2017. DOI:10.13140/RG.2.2.24973.28641

(supervised by dr. Simone Baldi at Delft Center for Systems ad Control, TU Delft). Then, the code has been improved by dr. Simone Baldi at Southeast University together with mr. Kang Yang.

In this version of the code, the fixed-wing UAV is requested to loiter around a point in the presence of wind. 

The code has been tested in Matlab R2019b. Compatibility with other Matlab version is not guaranteed.
