Grid Control systems
============

se.de_gridcontrol 

## Description

A collection of controlsystems to define shipclasses by using controlblocks on grids 
(SpeedControl, WeaponControl, EngineControl)

This concept provides the possibility to create a very hughe variation of ships and the creation
of many different types of shipclasses.
___
### Controlsystems
#### SpeedControl
In the worldsettings the speedlimit for both gridsizes is set >10000 m/s.
The script itself reduces the max speed of a grid without a controlblock to 25 m/s (configurable)
If the ship have to fly faster, the user has to place a controlblock with a higher speedlimit on the grid.
The script detects only the highest controlblock and the different speedlimits will not add. 

#### WeaponControl
Without a WeaponControlblock a grid can support a limited amount of weapons (configurable).
If the user want to build more or different weapons on the grid, he has to build a WeaponControlblock wich supports
the wanted weapon configuration.
If the user place more than supported by the WeaponControlblock, all weapons will be disabled until he dismount the weapon wich is to much.

#### EngineControl
Every grid without this block can support a (configurable) amount of thrusters. If the user want to build more, he has to
place a EngineControlblock in the grid. If he build more that the supported engines, all thruster will be diabled.
Its a EngineControl

### Content

| System |
| ------- |
| SpeedControl -> Script to control the gridspeed| 
| WeaponControl -> Script to control the max weapons per grid|
| EngineControl -> Script to control the max thrusters per grid|
