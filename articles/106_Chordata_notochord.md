# Chordata: Notochord

A python module that contains the core of the [Chordata Motion's software framework](http://chordata.cc). It is designed to run inside a microcomputer such as the Raspberry Pi allowing to control mocap hardware peripherals such as Chordata's Hub and KCeptors.

[https://gitlab.com/chordata/notochord-module](https://gitlab.com/chordata/notochord-module)

It also handle many signal processing operations required to obtain a moving human skeleton from the raw sensor data.

Most internal routines are implemented in C/C++ and wrapped using Cython, so the module combines the flexibility of python and the performance of a compiled language.

![chordata integrations](images/105_Chordata_integrations.jpg)

<script type="application/json">
{
  "technologies": [
    "Python",
    "Cython",
    "C++",
    "Sensors",
    "Raspberry-pi",
    "Websockets"
  ],
  "description": "A python module that contains the core of the Chordata Motion's software framework. It is designed to run inside a microcomputer such as the Raspberry Pi allowing to control mocap hardware peripherals such as Chordata's Hub and KCeptors.",
  "tags": [
    "Open-Source",
    "Mocap",
    "CI/CD",
    "py-module",
    "Signal-processing",
    "Electronics"
  ],
  "thumbnail": "images/106_thumb_notochord_module.png"
}
</script>
