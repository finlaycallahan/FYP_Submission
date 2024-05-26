# Variable Guide
This document contains a detailed guide for what all of the variables in the robot poses array mean.

Handover information:
R4c_ProgID: Describes which function is being called in the software uploaded to the robot (110 = normal handover, 111 = error handover)
R4c_int1: Represents the piece number being handed over. The pnum_Guide describes what number each part has. For parts with two pnum's, one defines the error frame for grabbing it by the fragile part.
R4c_int2: Gripper offset number
R4c_int3: If the piece is in the jig or not. 1 represents in jig and 0 represents out of jig.
R4f_Ready: Boolean flag for if the robot is ready. True is ready and false is not ready.
R4c_Start: If start is true, a handover situation is happening.
R4c_err: Char representing error type. Also used to terminate the data recording matlab script. (11 is execution major and 12 is assembly point)
	PE: 'p'
	EE: 'e'
	SNV: 's'
	ENV: 'n'
	NO ERROR: 'f' 
	COLLABORATION FINISHED (stop recording script): 'd'
R4c_sev: Integer representing severity for error scenarios. 1 for major and 0 for minor.

Robot position:
R4d_Joi1 = Joint 1 position
R4d_Joi2 = Joint 2 position
R4d_Joi3 = Joint 3 position
R4d_Joi4 = Joint 4 position
R4d_Joi5 = Joint 5 position
R4d_Joi6 = Joint 6 position
R4d_Joi7 = Joint 7 position

R4d_Tor1 = Joint 1 torque value
R4d_Tor2 = Joint 2 torque value
R4d_Tor3 = Joint 3 torque value
R4d_Tor4 = Joint 4 torque value
R4d_Tor5 = Joint 5 torque value
R4d_Tor6 = Joint 6 torque value
R4d_Tor7 = Joint 7 torque value

R4d_ForX = 
R4d_ForY = 
R4d_ForZ = 

R4d_PosX = 
R4d_PosY = 
R4d_PosZ = 

R4d_RotA = 
R4d_RotB = 
R4d_RotC = 

R4d_MomX = 
R4d_MomY = 
R4d_MomZ = 

R4c_Vel = 
R4c_GripperControl = 
R4c_GripperAct = 
R4c_GripperSpeed = 
R4c_GripperForce = 
R4c_GripperPos = 