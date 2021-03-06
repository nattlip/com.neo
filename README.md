# SZ Neo Coolcam device support App for Homey @ Athom.com
Makes Homey work with these nice and cheap chinese z-wave products

## Supported devices with most common parameters:
* NAS-PD01ZE, Motion Sensor
* NAS-WR01ZE, Power Switching Plug
* NAS-SW01ZE, Touch Wall Switch
* NAS-AB01ZE, Siren / Doorbell speaker
* NAS-DS01ZE, Door Sensor


## Supported devices with some parameters:
* NAS-WS01ZE, Flood Sensor

## Supported Languages:
* English
* Dutch (Nederlands)

## Todo
* Add more settings to devices

## Change Log:

### v 1.1.9   
**add support:**   
NAS-SW01ZE - Touch Wall Switch Support Added
note: Untested because no hardware available yet
Please contact me on slack or mail to debug further if something is not working correct with this switch
NAS-AB01ZE - More settings so the siren can also be used as doorbell speaker

**fixed**
* NAS-AB01ZE - Fixed a flow card error in the driver


### v 1.1.8   
**add support:**   
NAS-SW01ZE - Touch Wall Switch Support Added
note: Untested because no hardware available yet
Please contact me on slack or mail to debug further if something is not working correct with this switch
**fixed**
* NAS-AB01ZE - Fixed a flow card error in the driver

### v 1.1.7   
**update:**   
NAS-PD01ZE - Fixed LUX reporting based on threshold setting     
NAS-PD01ZE - Added battery alarm trigger card    
NAS-PD01ZE - Regrouping settings based on function + textual updates settings / labels / hints   
NAS-WR01ZE - Regrouping settings based on function + textual updates settings / labels / hints   
**notes**   
NAS-PD01ZE - LUX reporting based on interval setting is not working; under clarification with manufacturer   

### v 1.1.6 
**update:**   
NAS-WR01ZE - Updated mobile card & insights logging to include current and voltage   
Z-Wave Driver (v1.1.2)   
**notes**   
re-pair of Power Plug required to make use of current and voltage reporting capabilities   

### v 1.1.5
**add support:**   
NAS-WR01ZE - Additional settings implemented (e.g. over-load current, alarm current, time switch function)   
**update:**     
NAS-WR01ZE - Bug fixes defaultConfiguration and parameters, implementation of power consumption (kWh)   
NAS-WR01ZE - textual fixes (setting-labels, -hints and association group-hints)   
