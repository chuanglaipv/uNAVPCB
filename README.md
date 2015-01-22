# ![Officine Robotiche][Logo] uNAV PCB
**The first DC motor board in 4cm X 4cm** - PCB boards for uNAV

This is a project in development by [Officine Robotiche] team.

###Join on open firmware project [uNAV.X](https://github.com/officinerobotiche/uNAV.X)!!!

![uNAVPCB top](https://github.com/officinerobotiche/uNAVPCB/blob/master/Image/preview_Top.png)

# Hardware features
- 2 DC motor control (external encoders and double H-bridge are required)
- size: 4cm x 4cm
- Breadboard compliant
- Free 256Kb EEPROM in I2C 
- Voltage input *(Max 23V to 6V)*
- 2 internal regulators:
  - External input -> 5V
  - 5V -> 3.3V
- 4 LEDs
- ICSP programming

## DC Motor control
- 2 PWM outputs to control the speed of the motors
- Encoder input. *You can select 5V input or 3.3V to power on your encoders*: 
  - 2 channels (A, B)
  - 3 channels (A, B and Z axis)
- Analog input for current sensing
- Analog input for temperature sensing
- Pin to enable H-Bridge

## Communications
- 2 serial ports
- 1 I2C port
- 7 GP I/O (You can add feature remapping pins) 
 
# Available Shields
- [uBridge](https://github.com/officinerobotiche/uBridgePCB)

# Graphical tool for PID tuning
- [uNav_PID_Tuner](https://github.com/officinerobotiche/uNav_PID_Tuner)

[Officine Robotiche]:http://www.officinerobotiche.it/
[Logo]:http://2014.officinerobotiche.it/wp-content/uploads/sites/4/2014/09/ORlogoSimpleSmall.png
