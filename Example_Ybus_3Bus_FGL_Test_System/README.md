# Example: Admitance Matrix (Ybus): FGL 3-Bus Test System
Considers the FGL 3-bus test system shown in Figure 1.
![image](https://github.com/fglongatt/MY_MATLAB_Simulink/assets/16779213/c0753e27-c920-47cb-9cbc-9a7be712425a)
The system data is presented below.
BUS DATA                               
Bus          Voltage(KV)   Load(MW)    Load(MVAR)      
----------------------------------------------------------------------------
BUS_1           115.0            0.00       0.00
BUS_2           115.0         400.00      200.00
BUS_3           115.0           0.00       0.00
BRANCH DATA
From Bus    To Bus         MVA      Long(Km) r(Ω/km)  x(Ω/km)   g(us/km)   b(nF/km)
----------------------------------------------------------------------------------------------
BUS_1      BUS_2          100.0       1.0       2.645      5.290      0.000      0.000
BUS_1      BUS_3          100.0       1.0       1.322      3.967      0.000      0.000
BUS_2      BUS_3          100.0       1.0       1.653      3.306      0.000      0.000
Consider <sub>subscript</sub>  and  
Build the network model using the admittance matrix (Ybus).
