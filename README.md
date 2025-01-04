# Quadruped (alpha)
This is a 4 legged walking mechanical animal


This is a lasercut base image intended to be an inexpensive way to make a walking animal like device.

<image>

Steps:
- Tools and Materials
- Make Parts
- Build / Assemble
- Program
- Run


# Tools and Materials
- Tools:
  - Access to a laser cutter
  - mini screw driver
  - Laptop (to code and program)
- Materials:
  - 1/8" thick plywood (12"x12") (maybe 1/4" thick)
  - (N) mini servos (SG90)
  - mini screws
  - Microcontroller
     - (TBD: one of) Esp8266, Nodemcu, Arduino, RPI zero 2 w, RPI pico 2 w
  - servo controller board (ex. PCA9685)
     - https://learn.adafruit.com/16-channel-pwm-servo-driver/overview
     - https://learn.adafruit.com/16-channel-pwm-servo-driver/python-circuitpython
  - USB Battery (see example)
     - https://www.amazon.com/LOVELEDI-Portable-Charger-Power-Bank-15000mAh-Compatible-Smartphones/dp/B0CF3WGHWN/

# Make Parts
  1. Use/borrow a laser cutter (or order from an online laser cutter store) all of the parts for a robot.
  2. Validate you have all of the parts
     - 2 x body sides
     - 1 x body bottom
     - 1 x body top
     - 4 x upper legs
     - 4 x lower legs

# Build / Assemble
  1. Attach servos to body sides
  2. Attach body sides to top and bottom, secure with rubber band
  3. Attach servos to the lower legs
  4. Attach servo horns over each of the holster in the upper legs
  5. Attach upper legs to lower legs and attach screw to make leg unit.  Be sure to make two left and two right
  6. Attach leg units to body
  7. Run wires to body
  8. Add PCA9685 to body
  9. Attach all servo wires to PCA9685 (see diagram)
  10. Attach PCA9685 to microcontroller
  11. Connect microcontroller to laptop to program

# Program
open programming tool
load code

# Code References
Below are links to similar projects and code
 - 
