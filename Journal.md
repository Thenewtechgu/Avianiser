14th Jan 2026
Research
I gathered a list of components I wanted to use for the flight computer, then I uploaded its datasheets to Google Notebooklm so that it only anwsers using the datasheet. This is what I came up with
<img width="255" height="486" alt="image" src="https://github.com/user-attachments/assets/b3ed52c2-54db-461a-929b-06e6363f0ad5" />

The stm chip: the main flight controller running the custom sofware I'm going to make (pid, kalmal filter) while interacting with the sensors and controlling the outputs(servos, pwm, uart, i2c)

The rp2350B: Datalogger + trancver: connect to the stm chip through spi and will log every thing that goes through the chip may be get info from the sensors do that it does't overload the stm chip

The Bosch chip: sensors

AP2112-1.8,3.3 for power
MYMGK00506ERSR:power
I might add a chip to check for countinuity for pyrotechnic charges
Time spent: 1 hour

15th-16th Jan 2026
I routed everything needed for the rpi2350b including flash, crystal, buttons, sdcard, and usbc connection
<img width="1190" height="845" alt="SCH_Avian_2-RPI_2026-01-16" src="https://github.com/user-attachments/assets/c509ea79-2a4b-4115-99e7-b173518992f6" />
Time spent: 2 hours

17th-18th Jan 2026
I removed the stm32 chip after realising that it was going to be hard to program and im only going to use the rp2350 as the flight controller
also i wired up the mymg for 12V to 5V power for the rp2350b chip
<img width="644" height="264" alt="image" src="https://github.com/user-attachments/assets/b457d3cd-c389-4b53-a9d0-671f2ca383d9" />
Time spent: 1 hour

