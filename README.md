# Power quality analysis of AC voltage controller
## Objective
- To observe the load voltage and voltage across the SCR waveforms of a single-phase ac voltage controller, supplying (a) R load (b) R L load
- Compute Vrms in each case and compare it with observed value.
- To observe the power quality parameters in MATLAB/Simulink.
## Circuit Diagram
![image](https://user-images.githubusercontent.com/86883449/226311106-b60a56fa-dc4b-4c28-a041-a72fad3c1b64.png)

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

## Theoretical Calculations
- RMS load voltage for R load<br />
![image](https://user-images.githubusercontent.com/86883449/226312550-f0e2c941-57fc-43c8-8aa2-34a776c5b88c.png)
- RMS load voltage for R-L load<br />
![image](https://user-images.githubusercontent.com/86883449/226312627-dc3410c8-2b63-4f1c-aca2-5622c15a7b51.png)

## Observed Graph
- For RL load:<br />
![image](https://user-images.githubusercontent.com/86883449/226313429-22689f37-29a8-49f5-baa0-54f88189fb9a.png)
- For R load:<br />
![image](https://user-images.githubusercontent.com/86883449/226313689-98dbcc5b-8d82-4d76-8158-318e6ba844a9.png)
