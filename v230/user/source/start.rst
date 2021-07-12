Getting started
===============

* Install the `IQRF Gateway Daemon`_
* Install the `IQRF Gateway Webapp`_
* `Configure`_ your IQRF interface for coordinator TR module

  * Select **one of** from SPI, UART or CDC based on your HW

* Learn about the `Daemon API`_ and `Webapp API`_
* `Scheduler`_ helps with regular tasks 
* Choose `MQ`_/`WS`_/`MQTT`_ channel for communication with the daemon

  * Check/Set configuration for your channel using `IQRF Gateway Webapp`_

.. _`IQRF Gateway Daemon`: daemon-install.html
.. _`IQRF Gateway Webapp`: webapp-install.html
.. _`Configure`: configure.html
.. _`MQ`: https://en.wikipedia.org/wiki/Message_queue
.. _`WS`: https://en.wikipedia.org/wiki/WebSocket
.. _`MQTT`: https://en.wikipedia.org/wiki/MQTT
.. _`Daemon API`: daemon-api.html
.. _`Webapp API`: webapp-api.html
.. _`Scheduler`: scheduler.html

Next steps
----------

* Use http://webapp-ip/iqrfnet/send-raw/ to confirm communication with TR module in the gateway
* Use http://webapp-ip/iqrfnet/network/ to **Bond via button**/**Smart Connect via QR code**/**AutoNetwork** new devices into the IQRF network
* Use http://webapp-ip/cloud/{aws/azure/bluemix/inteli-glue/} manager to connect the gateway to the **favourite cloud** 
* Check gateway `Webapp API`_

* Configure any JSON API task in the `Scheduler`_ or send `JSON API`_ requests from your application directly
* If you use IQRF standard devices such as Sensor, Binary output, Light or Dali in your network, check `JSON API for Standard`_    
* Parse `JSON API`_ responses coming from the network

.. _`JSON API`: daemon-api.html
.. _`JSON API for Standard`: daemon-api.html#iqrf-standard
.. _`Webapp API`: webapp-api.html

Reference applications
----------------------

- `FRC&Sleep`_
- `Multiple GWs`_

.. _`FRC&Sleep`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/apps/frc&sleep
.. _`Multiple GWs`: https://docs.iqrf.org/iqd-gw-01/apps.html

Examples
--------

Give a go with the API examples in your favourite programming language

- `Bash`_
- `Python`_
- `JavaScript`_
- `NodeRed`_

.. _`Bash`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/examples/bash
.. _`Python`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/examples/Python
.. _`JavaScript`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/examples/nodejs
.. _`NodeRed`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/examples/node-red
