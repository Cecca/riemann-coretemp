riemann-coretemp
================

Simple [Riemann](http://riemann.io) client to poll the temperature of each core. Parses the output of `sensors` to measure the temperature.

Requirements
------------

 - [`riemann-tools`](https://github.com/aphyr/riemann-tools)
     
        gem install riemann-tools

 - [`lm-sensors`](http://www.lm-sensors.org/)
        
        # Debian, Ubuntu etc..
        apt-get install lm-sensors
        # Fedora
        yum install lm_sensors

        # configuration
        sensors-detect
