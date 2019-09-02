Deployment guide for production
===============================

* Install **stable** version of the `IQRF Gateway Daemon`_
* (optional) Disable **auto updates** of IQRF Repository in the daemon configuration: /etc/iqrf-gateway-daemon/iqrf__JsCache.json "checkPeriodInMinutes": 0
* Export **daemon's configuration and scheduler setting** using `IQRF Gateway Webapp`_, menu Configuration/Migration
* (optional) Disable logging in the daemon configuration for SD card based gateways: /etc/iqrf-gateway-daemon/shape__TraceFileService.json "level": "ERR"

.. _`IQRF Gateway Daemon`: daemon-install.html
.. _`IQRF Gateway Daemon`: webapp-install.html
