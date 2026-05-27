# Automation-of-Thermal-Power-Plant-Using-PLC-Ladder-Logic

# Project Overview
- Developed an automated Thermal Power Plant control system using PLC Ladder Logic programming for sequential startup and shutdown of major plant sub-systems.
- Designed industrial automation logic for ID Fan, Boiler-Heater, Burner, Steam Valve, Turbine, Generator, Cooling Pump, Conveyor, and Ash Pump operations.
- Implemented sequential control using Allen-Bradley PLC addressing and On-Delay Timers (TON) with 5-second inter-stage delays for safe plant operation.
- Developed Start/Stop seal-in latch circuits, timer-based interlocking logic, and automated process sequencing using Ladder Logic instructions such as XIC, XIO, OTE, TON, and Done Bits (.DN).
- Applied PLC-based industrial automation concepts to improve operational safety, reliability, scalability, and reduced manual intervention in thermal power plant processes.

# Project Flowchart
1. Operator presses Start button.
2. Control Relay (CR) latch circuit energises and maintains system ON state.
3. ID Fan starts to create airflow inside the boiler furnace.
4. TON Timer t1 introduces 5-second delay.
5. Boiler-Heater Stage 1 activates.
6. TON Timer t2 introduces another 5-second delay.
7. Burner ignites to start fuel combustion.
8. TON Timer t3 stabilises combustion process.
9. Boiler-Heater Stage 2 activates to reach operational temperature.
10. Steam Valve opens to allow steam flow toward the turbine.
11. Turbine starts rotating using high-pressure steam.
12. Generator activates and begins electrical power generation.
13. Cooling Pump starts for condenser cooling operation.
14. Conveyor system starts supplying fuel continuously.
15. Ash Pump activates to remove combustion residue.
16. On pressing Stop button:
   - All outputs de-energise
   - Timers reset
   - Entire plant shuts down safely

# Results & Conclusion
- Successfully implemented PLC-based automation for sequential startup and shutdown of major Thermal Power Plant sub-systems.
- Achieved safe interlocked operation using 9 TON timers with fixed 5-second inter-stage delays between each process stage.
- Demonstrated automated control of ID Fan, Boiler-Heater, Burner, Steam Valve, Turbine, Generator, Cooling Pump, Conveyor, and Ash Pump using Ladder Logic programming.
- Implemented Start/Stop seal-in latch circuits and timer-based process sequencing for reliable industrial automation control.
- Achieved a complete sequential startup cycle of approximately 45 seconds for full plant operation.
- Demonstrated the effectiveness of PLC Ladder Logic for industrial automation applications requiring safety, reliability, fault isolation, and process sequencing.
- Validated that PLC-based automation reduces manual intervention, minimises operational errors, improves safety interlocking, and enhances overall plant efficiency.
- Concluded that PLC automation can be extended further with HMI panels, SCADA systems, remote monitoring, and fault-tolerant industrial control architectures.
