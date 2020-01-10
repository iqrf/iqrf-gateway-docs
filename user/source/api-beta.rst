Beta Application Programming Interface
======================================

**v2.3.0-beta** - only new or modified JSON messages for communication via `MQ`_/`WS`_/`MQTT`_ channels.

.. _`MQ`: https://en.wikipedia.org/wiki/Message_queue
.. _`WS`: https://en.wikipedia.org/wiki/WebSocket
.. _`MQTT`: https://cs.wikipedia.org/wiki/MQTT

IQMESH Network
--------------

IQRF Bonding
++++++++++++

- `AutoNetwork request v1-0-0`_ and `example`__
- `AutoNetwork response v1-0-0`_ and `example`__

.. _`AutoNetwork request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/iqmeshNetwork_AutoNetwork-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/iqmeshNetwork_AutoNetwork-request-1-0-0-example.json
.. _`AutoNetwork response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/iqmeshNetwork_AutoNetwork-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/iqmeshNetwork_AutoNetwork-response-1-0-0-example.json

Daemon Information
------------------

The commands to access daemon lite DB.

- `StartEnumeration request v1-0-0`_ and `example`__
- `StartEnumeration response v1-0-0`_ and `example`__
- `GetNodes request v1-0-0`_ and `example`__
- `GetNodes response v1-0-0`_ and `example`__
- `GetSensors request v1-0-0`_ and `example`__
- `GetSensors response v1-0-0`_ and `example`__
- `GetBinaryOutputs request v1-0-0`_ and `example`__
- `GetBinaryOutputs response v1-0-0`_ and `example`__
- `GetLights request v1-0-0`_ and `example`__
- `GetLights response v1-0-0`_ and `example`__
- `GetDalis request v1-0-0`_ and `example`__
- `GetDalis response v1-0-0`_ and `example`__

.. _`StartEnumeration request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_StartEnumeration-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_StartEnumeration-request-1-0-0-example.json
.. _`StartEnumeration response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_StartEnumeration-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_StartEnumeration-response-1-0-0-example.json
.. _`GetNodes request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetNodes-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetNodes-request-1-0-0-example.json
.. _`GetNodes response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetNodes-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetNodes-response-1-0-0-example.json
.. _`GetSensors request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetSensors-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetSensors-request-1-0-0-example.json
.. _`GetSensors response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetSensors-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetSensors-response-1-0-0-example.json
.. _`GetBinaryOutputs request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetBinaryOutputs-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetBinaryOutputs-request-1-0-0-example.json
.. _`GetBinaryOutputs response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetBinaryOutputs-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetBinaryOutputs-response-1-0-0-example.json
.. _`GetLights request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetLights-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetLights-request-1-0-0-example.json
.. _`GetLights response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetLights-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetLights-response-1-0-0-example.json
.. _`GetDalis request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetDalis-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetDalis-request-1-0-0-example.json
.. _`GetDalis response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/#iqrf/infoDaemon_GetDalis-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/latest/json/iqrf/examples/infoDaemon_GetDalis-response-1-0-0-example.json
