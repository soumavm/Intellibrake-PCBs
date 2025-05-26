# Intellibrake-PCBs
PCB files used for all designs for the Intellibrake automated braking go-kart

# Controller Board
Directly connects to other PCBs through Mezzanines. Does GPIO, I2C, ADC, and PWM tasks. Communicates with the Jetson (master) through SPI

# Motor Controller
36V input Brushed DC Motor controller with estop and current sensing. Allows for fwd, rev, and regen braking states.

# DC/DC
36V input to 5V output @ 10A high-efficiency buck converter. Allows for individual cutoff of downstream PCBs. Has current and temperature monitoring.

# 'SLAP' Board
'Steering, Lights, Accelerometer, Pedal' Board. Interfaces with all sensors on the kart, and contains a 7-segment display to display driving speed.

# Radar Board
mmWave Radar board used for object detection and sensing. Based on the AWRL6432BOOST dev board.

# SPI Interconnect Board
General-purpose SPI signal booster to avoid SI issues at longer distances. Also features a 3.3V to 5V SPI step up to allow for 5V SPI as well.



