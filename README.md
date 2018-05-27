# CPII
Cell Phone Ignition Interlock

## Summary
Raspberry Pi based project that uses Cell Phone and Driver's License authentication protocol to actuate vehicle ignition interlock. This project is a preliminary prototype, later revisions will comprise of a full OBDII interfacing system running specialized IC's with minimal power requirements (MCP and STN variants). Additionally, a variety of protocols will be addressed (SAE PWM and VPW J1850, ISO 9141-2, and J1939).

## Objective
The objective of this project is to prove the design concept. Lessons learned will guide future revisions. ]

## Prototype Specifications
Raspberry Pi 3 used to authenticate cell phone, MFRC-522 RFID reader breakout PCB used to read Driver's License (B.C. EDL), in conjunction with a cell phone box with closure detection. Optocoupler used to control ignition signal path. LED UI provides status of authentication.
