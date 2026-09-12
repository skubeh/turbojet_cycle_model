# turbojet_cycle_model

IDEAL TURBOJET CYCLE MODEL - STAGE 1 
A station-by-station (0→2→3→4→5→9) thermodynamic model of an ideal, loss-free
turbojet engine, built in Python. Given flight conditions (Mach number,
altitude) and two design variables (compressor pressure ratio πc, turbine
inlet temperature T04), it computes:

- Temperature and pressure at every station in the engine
- Specific thrust and TSFC
- Thermal efficiency, propulsive efficiency, and overall efficiency

Assumptions at this stage: isentropic diffuser/compressor/turbine/nozzle,
constant-γ gas model (separate values for cold air vs. hot combustion
products), fully expanded nozzle (p9 = p0), no combustor pressure loss.

