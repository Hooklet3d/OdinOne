##MK1 Active Cooler 

The MK1 Active Cooler mounts onto the rear of the MK8 Odin Mount.  It uses existing hardware and requires no additional modificaton.

The MK1 is designed to be fitted with a 40mm fan. 

###Fan selection and use... 

The fan you use should be a 12v fan, this fan will be attatched to the MK1 Cooler and by design must be positioned to push air vs pull.  

The fan should be wired to the existing 'Fan' connection on your Odin's control board.  This connection is found on the blue rail that 
contains the connections for the bed and extruder.  

Once the fan is attatched you will be able to access and use it via your slicer or Gcode commands.  

_Note:  Add the following to your starting script:_

```
M107; Turn fan off...
```
This will make sure the fan is off prior to starting warm-up.  Running the fan while warming up can cause issues with heating.  
