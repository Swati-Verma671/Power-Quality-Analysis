# Power quality analysis of AC voltage controller
## Objective
- To observe the load voltage and voltage across the SCR waveforms of a single-phase ac voltage controller, supplying (a) R load (b) R L load
- Compute Vrms in each case and compare it with observed value.
- To observe the power quality parameters in MATLAB/Simulink.
## Procedure
- Connect the circuit diagram as shown in Figure 4.1 with resistive load (100Ω, 5A).
-  Auto transformer is adjusted for about 100 V.
-  Switch on the single-phase bridge firing circuit & check for the line synchronization of trigger circuit. If they are not synchronized, interchange the source connections of either power circuit or the trigger circuit.
-  Then trigger the SCRs by selecting a suitable firing angle.
-  Observe load voltage and voltage across the SCR waveforms.
-  Repeat steps 2-5 for R-L load
- Figure 4.1 is developed in MATLAB/SIMULINK software.
- Observe the waveforms of source voltage, source current, output voltage and output current.
- Observe the FFT analysis of source current and source voltage different values of firing angle.
