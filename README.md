# i2c ips for vivado ip subsystem

All these simple ips aimed at making bd design easier.

## i2c_slave

make i2c_slave as a ip for vivado

![i2c_slave](./doc/i2c_slave.jpg)


## i2c_extender

i2c_extender makes a single master in fpga can access i2c device on diffierent fpga io

![i2c_extender](./doc/i2c_extender.jpg)

## i2c_hub

i2c_hub paly as one slave / tow (and more) master bridge, even multi-master if Time Division Multiplexing Access

![i2c_hub](./doc/i2c_hub.jpg)

## xgpio_to_i2c

In bd wrapper, tri-state io can be interface to i2c port by this ip, hence, don't need to modify wrapper, is it better!?

