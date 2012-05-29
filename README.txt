The DS3212 is a Precise Real-Time Clock from Maxim.  It requires almost no external components and is temperature compensated.  This chip solves some of the RTC issues associated with the DS1307.

This Arduino shield will make it simple to add a RTC to any project, especially one where lost time is not acceptable.

On the Eagle design files, there are duplicated holes for all shield pins.  A prototyping area (similar to a breadboard) has been included.  I2C pins are connected to both A4, A5, and the "new" SDA/SCL pins on R3+ boards.