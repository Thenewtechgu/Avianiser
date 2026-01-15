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
