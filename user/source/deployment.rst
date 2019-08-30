Deployment guide for production
===============================

* Install **stable** version of the `IQRF Gateway Daemon`_
* (optional) Disable auto updates of IQRF Repository in the daemon configuration: /etc/iqrf-gateway-daemon/iqrf__JsCache.json "checkPeriodInMinutes": 0
* Export daemon's configuration and scheduler setting using `IQRF Gateway Webapp`_, menu **Configuration/Migration

.. _`IQRF Gateway Daemon`: daemon-install.html
.. _`IQRF Gateway Daemon`: webapp-install.html
