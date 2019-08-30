Deployment guide for production
===============================

* Install **stable** version of the IQRF Gateway Daemon [1]
* Disable auto updates of IQRF repository in the daemon configuration [2] (optional)

[1] https://docs.iqrf.org/iqrf-gateway/daemon-install.html
[2] /etc/iqrf-gateway-daemon/iqrf__JsCache.json "checkPeriodInMinutes": 0
