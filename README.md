# EARS

### Idea 1:

### Electromechanical Automatic Relief System

Visual Pressure Sensor (for verification)

IC Pressure Sensor

Solenoid (for actuation)

MCU (STM32L152)

This system accepts gas from a pressurized system (air compressor, bike pump etc.) and holds pressure until ~75 psi is reached, at this point the solenoid is actuated in short burts to reduce the pressure in the chamber.  It will be built with PVC and cheap parts as a proof of concept.  A chamber can be made of arbitrary lengths of 1-2" PVC with T's and caps modified to allow sensors be placed inside the pressure chamber.

We've chose this design for it's simplicity, usefullness and scaling capablitity (it could be improved and used in industrial processes).

---

### Idea 2:

### Artificially Intelliget Robot Swarm

IMU For Position and Orientation

Infrared camera array for collision detection

GPS for position

2 DC Motors

MCU (STM32L152)

This system would require that the control system be weighted and placed inside a plastic ball.  The DC motors would control an axis of rotation each.  The control board would be allowed to spin freely via a gyro.  The device could then move itself around by spinning a combination of both DC motors.  In cunjunction with several other similar robots they could be 'trained' to move in unison for carrying loads or moved chaoticly for entertainment.

This is needlessly complicated for questionable value.

---
