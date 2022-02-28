# node-red-contrib-sds011-dust-sensor
This is a Node Red node to manage connection to the SDS011 sensor on a Raspberry Pi. It is based on https://github.com/ikhayainkomishi/node-red-contrib-sds011 and documentation resp. Nodes help text was updated to make it easier to use. 

All sensors supported modes like constant measurement mode and measuring in certain intervals. 

This node works on all devices with a serial port.

## Wiring

Make sure you specify correct serial port. The default is `/dev/serial0` which is used on Raspberry Pi. Remember to wire Tx <--> Rx correctly.

## License
GPLv3
