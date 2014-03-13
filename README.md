Lab3
====

Nexys2_top_shell:
https://github.com/KevinJagoda/Lab3/blob/master/Nexys2_top_shell.vhd

Schematics:
https://github.com/KevinJagoda/Lab3/blob/master/Schematic.JPG

Mealy Elevator Controller from CE3 (used in the Nexys_top_shell):
https://github.com/KevinJagoda/CE3/blob/master/MealyElevatorController_Shell.vhd

-------------------------------------------------------------------------------------

Lab Demo was successfully showed to Dr. Neebel
  - demo had a single elevator being successfully controlled between 4 floors
  - was unable to complete prime number demo in time
  
-------------------------------------------------------------------------------------

Documentation:
  -C3C Hunter Her helped me with the syntax of assigning the buttons and switches. 
    Noted in my Nexys2_top_shell.vhd
    
-------------------------------------------------------------------------------------

What was added to Nexys2_top_shell:

- Component MealyElevatorController_shell
  -including signals (floor and nextfloor)
- assigning floor, "0000", nextfloor, and "0000" to nibble0, nibble1, nibble2, and nibble3.
- Assigning the LEDs to the clock, switches/buttons to up_down, stop, and reset, etc
