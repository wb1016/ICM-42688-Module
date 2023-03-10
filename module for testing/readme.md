## summary
testing module for P variant, but you can edit files to use V variant.
this module is mainly designed to test behavior with and without 32.768kHz oscilator.
## clocking
connecting INT2 to OSC will enable oscilator output. otherwise, you should connect INT2 to GND.
## I2C
default I2C address is 1101000(0x68). you can solder the onboard jumper to use alternative address 1101001(0x69)
## editing
you can import schmatic and PCB in easyeda.