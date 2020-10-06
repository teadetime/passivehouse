# Passive Solar House

Work for Passive Solar house for QEA II.

## Goals

* Model a passive solar-heated house in MATLAB
* Use temperature data from 2018 to show how the house would perform in real life throughout the year
* __Max temp in summer__ should be less than 30 degrees Celcius.
* __Min temp in winter__ should be more than 17 degrees Celcius, less than 25 degrees C.

## Modeling

##### Governing ODEs
Qin = Solar Radiation thorugh window
Cf = Heat Capacity of Floor
Rparallel = equivalent resistance of parallel portion of thermal resistances
R_tot = Total resistance from floor to outside air


dTF/dt = Qin/CF - (TF-Tout)/(CF*Rtot)
dAin/dt = (Rparallel / Rtot) * (dTf/dt)
