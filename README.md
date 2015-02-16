# Quadcopter-MethaneSensor
This project is based around a quadcopter built from scratch with a multiwii board with an onboard methane sensor and gps unit.
The gps unit will be connected to the methane sensor reading output and whenever the methane sensor reads a value higher than
a certain limit, the gps coordinate will essentially snapshot it's coordinates and keep it within a window on the arduino.
After the quadcopter is reobtained from the air, we plug in the arduino, open up the GUI and see what we have and we can then
make a hotspot mapping of where the most hazardous gases are which can help in air pollution cleanup in many areas. Can be used in rural and urban areas
