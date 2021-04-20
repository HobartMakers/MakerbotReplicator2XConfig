# MakerbotReplicator2XConfig

## Setup Procedure

* Set up OctoPrint server (eg. on Raspberry Pi)  
* Connect via web interface, set up user, etc  
* Install GPX plugin  
* Install Ultimaker Cura on host machine  
* Connect Cura to Octoprint with plugin (Go to Marketplace -> Octoprint)  
* Set up new printer in Cura  

## Cura Printer Settings
**Printer Settings**
Width: 220mm  
Depth: 145mm  
Height: 150mm  
Build plate shape: Rectangular  
GCode flavour: Makerbot
See file in this repo for start and end G-Code

## GPX Settings
Machine Type: Replicator 2X  
GCode flavour: Makerbot
Others default

## Octoprint Printer Profile Settings
### Print bed & build volume
Form factor: rectangule  
Origin: Center  
heated bed: [x]  
Heated chamber: [ ]  
Width: 200mm  
Depth: 120mm  
Height: 110mm  
### Hotend & extruder
Nozzle Diameter: 0.4mm  
Number of extruders: Can leave at just *1* for now..
