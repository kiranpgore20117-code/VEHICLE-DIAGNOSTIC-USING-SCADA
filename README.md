# VEHICLE-DIAGNOSTIC-USING-SCADA

#	PROBLEM STATEMENT

Modern vehicles contain multiple critical systems such as the engine, brakes, cooling system, and electrical components. When a fault occurs, drivers often have no real-time information about what went wrong, why it happened, or how to fix it. Traditional diagnostic tools require:
•	Professional expertise<br>
•	OBD scanners or garage equipment<br>
•	Time-consuming manual inspection<br>
•	No user-friendly explanation for the driver<br>
As a result, even a minor issue (low brake pressure, overheating engine, loose battery terminal, etc.) can lead to breakdowns or unsafe driving conditions because drivers lack immediate guidance.
There is a need for a real-time, intuitive, SCADA-based vehicle diagnostic system that:
•	Detects sensor abnormalities instantly<br>
•	Displays them visually on a dashboard<br>
•	Provides simple, actionable troubleshooting steps<br>
•	Helps drivers fix minor issues quickly<br>
•	Reduces dependency on mechanics for small faults<br>

#PROPOSED SOLUTION

To address these challenges, a Smart Vehicle Diagnostic System using SCADA is developed. The system integrates:<br>
✔ Real-Time Monitoring
SCADA continuously tracks vehicle sensors (engine temperature, brake pressure, coolant level, battery health, etc.) and detects abnormal values instantly.<br>
✔ Interactive SCADA Dashboard<br>
A customized graphical vehicle model displays components such as the Engine, Brakes, Battery, and Cooling System.<br>
•	Faulty parts blink in red<br>
•	Users can click on the part to view details<br>
✔ Python-Based Troubleshooting Assistant<br>
When a fault is detected, a Python GUI automatically opens showing:<br>
•	Step-by-step troubleshooting guide<br>
•	Do’s & Don’ts<br>
•	Possible causes<br>
•	Repair tools needed<br>
•	Linked YouTube videos for repair assistance<br>
✔ Fault Simulation for Testing<br>
Sensor values are simulated using Python so the system can demonstrate:<br>
•	Engine overheating<br>
•	Brake failure<br>
•	Battery discharge<br>
•	Coolant leakage<br>
•	Fuel system faults<br>
✔ SCADA–Python Integration<br>
Data exchange between SCADA tags and Python enables:<br>
•	Fault triggers<br>
•	Popup hints<br>
•	Real-time updates<br>
•	Logging of fault history<br>



