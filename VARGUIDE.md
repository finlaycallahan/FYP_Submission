# Variable Guide
This document contains a detailed guide for what all of the variables in the robot poses array mean.

Handover information:
R4c_ProgID: Describes which function is being called in the software uploaded to the robot (110 = normal handover, 111 = error handover)
R4c_int1: Represents the piece number being handed over. The pnum_Guide describes what number each part has. For parts with two pnum's, one defines the error frame for grabbing it by the fragile part.
R4c_int2:
R4c_int3: If the piece is in the jig or not. 1 represents in jig and 0 represents out of jig.
R4f_Ready: Boolean flag for if the robot is ready. True is ready and false is not ready.
R4c_Start: If start is true, a handover situation is happening.
R4c_err: Char representing error type. Also used to terminate the data recording matlab script. (11 is execution major and 12 is assembly point)
	PE:
	EE:
	SNV:
	ENV:
	NO ERROR:
	COLLABORATION FINISHED:
R4c_sev: Integer representing severity for error scenarios. 1 for major and 0 for minor.

Robot position:
