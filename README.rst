ESP-IDF template app
====================

This is a template application to be used with `Espressif IoT Development Framework`_ (ESP-IDF). 

Please check ESP-IDF docs for getting started instructions.

Code in this repository is Copyright (C) 2016 Espressif Systems, licensed under the Apache License 2.0 as described in the file LICENSE.

.. _Espressif IoT Development Framework: https://github.com/espressif/esp-idf

With bschwind/esp-32-build
==========================

* Install the dependencies for [this repo](https://github.com/bschwind/esp-32-build)
* Clone this repo with `git clone --recursive https://github.com/bschwind/esp-idf-template.git`
* Do the typical docker-machine startup with `docker-machine start <MACHINE_NAME>` and `docker-machine env <MACHINE_NAME>`
* Run `./run.sh`
* Once in a shell inside the container, you can run `make` to build your code, `make flash` to flash it, and `./monitor.sh` to attach to run a serial monitor and see output from the ESP32
