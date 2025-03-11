# CubeSat-Simulation
CubeSat Pointing, Detumbling and Attitude Estimation
Mission: Model a CubeSats pointing and detumbling simulation. Compare effectiveness of EKF, UKF, and maybe particle filter.

Dynamics:
-	Attitude dynamics & kinematics (rk4 for propagation)
    - Equations of motion
-	Orbital mechanics
-	Disturbance Torques
    - Atmospheric Drag
	  - Solar Radiation Pressure
	  - Earths Mag field
	  - Gravity Gradient
    - J2,3,4

Sensors: 
-	Magnetometer
-	Sun Sensor-
- Star Tracker- 
- Horizon Sensor (maybe)
-	IMU – accelerometer and gyroscope
-	GNSS for Attitude determination (maybe)

Actuators:
-	Reaction Wheel
-	Magnetorquer

Algorithms
-	Estimation
   - Davenports q-method
	 - MEKF
   - MUKF
   - Particle Filter (maybe)
   - OEKF 
Controllers
- B-dot detumbling ( bang-bang control)
	   - B-dot filter using least squares or low pass filter
PID pointing controller
     - Gains tuned using robust control theory
