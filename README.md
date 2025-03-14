# CONES
CONES: Matlab code for convex optimization in electromobility studies
=====================================================================
This repository includes examples for powertrain design and energy management of electrified vehicles. 
A tutorial describing the convex modeling steps is not (yet) included. Instead, readers are referred to the following article which gives basic overview on the convex modeling and the optimization framework.
[1] B. Egardt, N. Murgovski, M. Pourabdollah, and L. Johannesson. Electromobility studies based on convex optimization: Design and control issues regarding vehicle electrification. IEEE Control Systems Magazine, 34(2):32-49, 2014.

Instructions for further reading is provided in the folders where examples are saved. 
In order to be able to run examples in Matlab, please follow the following steps:
1. Instal CVX, Matlab software for disciplined convex programming. The examples have been tested with CVX provided within this package, CVX redistributable, v2.1, and solver SeDuMi. We strongly recommend using this version of CVX for getting accustomed to the examples. Further information about CVX, e.g. licensing, manual, latest version, can be found at http://cvxr.com/cvx.
2. Go to one of the folders where examples are saved, and execute in Matlab the file starting with "start...".
The following examples are currently available:
a) CONVveh: Energy management of a conventional vehicle. Gear is decided by heuristics. This example does not require optimization and its purpose is only to be used as a benchmark solution. 
b) FCHV: Combined design and energy management of a fuel cell hybrid vehicle (FCHV), with a supercapacitor as an energy buffer. This example provides the optimal energy management of the vehicle and the optimal sizes of supercapacitor and fuel cell system of a hybrid city bus.
c) FCHVbatterySOH: Combined optimization of fuel cell and battery sizing, and power-split control of a fuel cell hybrid bus, subject to a battery state of health (SOH) model. The battery health is a c-rate-weighted Ah-throughput model.
d) HEVparallel: Combined optimization of battery sizing and power-split control of a hybrid electric vehicle in a parallel powertrain configuration. The engine on/off and gear decisions are decided by heuristics.
e) HEVseries: Combined optimization of engine generator unit (EGU) and battery sizing, and power-split control of a hybrid electric vehicle in a series powertrain configuration. The engine on/off state is decided by heuristics, where the engine is turned on when demanded power of the baseline vehicle exceeds a certain threshold.

=====================================================================
Created by Nikolce Murgovski, 2014-02-09. 
Modified by Nikolce Murgovski, 2015-11-06.

