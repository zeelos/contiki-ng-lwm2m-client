## Note

This example is based on the [LWM2M sample](https://github.com/contiki-ng/contiki-ng/tree/develop/examples/lwm2m-ipso-objects) that comes with the [Contiki-ng distribution](https://github.com/contiki-ng/contiki-ng). It is mainly tested on a [T1 SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag/) with a [CC2650 wireless MCU LaunchPad](http://www.ti.com/tool/LAUNCHXL-CC2650) acting as a [border router](https://github.com/contiki-ng/contiki-ng/wiki/Tutorial:-RPL-border-router). Further, DTLS is enabled by default using the included ['project-conf.h'](https://github.com/zeelos/contiki-ng-lwm2m-client/blob/master/project-conf.h) file. For more information (including setup), please visit the official [LWM2M documentation page](https://github.com/contiki-ng/contiki-ng/wiki/Documentation:-LWM2M) on the [Contiki-ng project.](https://github.com/contiki-ng/contiki-ng/wiki)

![Contiki-ng Screenshot](https://image.ibb.co/d4pO5J/contiki_ng_t1_screenshot.png)


## LWM2M with IPSO Objects Example

This is an OMA LWM2M example implementing IPSO Objects.
It can connect to a Leshan server out-of-the-box.
Important configuration parameters:
* `LWM2M_SERVER_ADDRESS`: the address of the server to register to (or bootstrap from)
* `REGISTER_WITH_LWM2M_BOOTSTRAP_SERVER`: set to bootstrap via `LWM2M_SERVER_ADDRESS` and then obtain the registration server address

A tutorial for setting up this example is provided on the wiki.
