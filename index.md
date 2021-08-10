---
layout: default
---
# Clean Water Institute
> When clean water is scarce, groundwater can be an excellent source, but drilling is expensive. Geophysical equipment, which relies on various types of signal modulation to model strata for the optimal siting of wells, can easily cost tens of thousands of dollars. This project seeks to develop low cost (<$500) instrumentation with software for data interpretation in Python. The software models geophysical data (electrical resistivity, seismic refraction, etc.) to identify choice sites for drilling a well. Software should incorporate an easy-to-use GUI, trap errors, and be easily deployable on any PC. Some code will also be used for interfacing with microcomputers recording real time data and this must be robust under trying field conditions. 

## VES Inverse

> Resistivity uses electrical current injected into the ground to determine electrical properties of earth layers. Code requires calculation of physics of electrical flow in the earth and inverse modelling to find the best-fitting earth model to observations of current and voltage measurements taken at the surface

[VESgui download for Windows (XP+)](./VESgui.exe).

<!-- 
[VESgui for Windows XP](./VESgui_xp.exe).

[VESgui for Windows Vista](./VESgui_Vista.exe).

[VESgui for Windows 7+](./VESgui_W7.exe). -->

## Seismic Refraction
> Seismic Refraction uses shock waves from sledgehammer blows at the surface to give subsurface strata defined by the compressional wave velocity. Code uses an audio interface connected to a PC to capture the first seismic signal reaching distant geophones. This is interpreted through implementation of old existing FORTRAN software (SIPT) developed but the US Geological Survey with our Visual bAsic.net GUI. 
