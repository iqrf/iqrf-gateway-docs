Daemon API - Beta
=================

**v2.4.0~beta** - only new or modified JSON messages for communication via `MQ`_/`WS`_/`MQTT`_ channels.

.. _`MQ`: https://en.wikipedia.org/wiki/Message_queue
.. _`WS`: https://en.wikipedia.org/wiki/WebSocket
.. _`MQTT`: https://cs.wikipedia.org/wiki/MQTT

IQMESH Network
--------------

IQRF OTA
++++++++

- `OtaUpload request v1-0-0`_ and `example`__
- `OtaUpload response v1-0-0`_ and `example`__

.. _`OtaUpload request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/iqmeshNetwork_OtaUpload-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/iqmeshNetwork_OtaUpload-request-1-0-0-example.json
.. _`OtaUpload response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/iqmeshNetwork_OtaUpload-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/iqmeshNetwork_OtaUpload-response-1-0-0-example.json

Daemon Information
------------------

The commands to access daemon lite DB.

- `Enumeration request v1-0-0`_ and `example`__
- `Enumeration response v1-0-0`_ and `example`__
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
- `GetMidMetaData request v1-0-0`_ and `example`__
- `GetMidMetaData response v1-0-0`_ and `example`__
- `GetNodeMetaData request v1-0-0`_ and `example`__
- `GetNodeMetaData response v1-0-0`_ and `example`__
- `MidMetaDataAnnotate request v1-0-0`_ and `example`__
- `MidMetaDataAnnotate response v1-0-0`_ and `example`__
- `OrphanedMids request v1-0-0`_ and `example`__
- `OrphanedMids response v1-0-0`_ and `example`__
- `SetMidMetaData request v1-0-0`_ and `example`__
- `SetMidMetaData response v1-0-0`_ and `example`__
- `SetNodeMetaData request v1-0-0`_ and `example`__
- `SetNodeMetaData response v1-0-0`_ and `example`__

.. _`Enumeration request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_Enumeration-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_Enumeration-request-1-0-0-example.json
.. _`Enumeration response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_Enumeration-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_Enumeration-response-1-0-0-example.json
.. _`GetNodes request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetNodes-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetNodes-request-1-0-0-example.json
.. _`GetNodes response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetNodes-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetNodes-response-1-0-0-example.json
.. _`GetSensors request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetSensors-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetSensors-request-1-0-0-example.json
.. _`GetSensors response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetSensors-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetSensors-response-1-0-0-example.json
.. _`GetBinaryOutputs request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetBinaryOutputs-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetBinaryOutputs-request-1-0-0-example.json
.. _`GetBinaryOutputs response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetBinaryOutputs-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetBinaryOutputs-response-1-0-0-example.json
.. _`GetLights request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetLights-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetLights-request-1-0-0-example.json
.. _`GetLights response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetLights-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetLights-response-1-0-0-example.json
.. _`GetDalis request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetDalis-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetDalis-request-1-0-0-example.json
.. _`GetDalis response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetDalis-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetDalis-response-1-0-0-example.json
.. _`GetMidMetaData request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetMidMetaData-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetMidMetaData-request-1-0-0-example.json
.. _`GetMidMetaData response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetMidMetaData-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetMidMetaData-response-1-0-0-example.json
.. _`GetNodeMetaData request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetNodeMetaData-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetNodeMetaData-request-1-0-0-example.json
.. _`GetNodeMetaData response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_GetNodeMetaData-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_GetNodeMetaData-response-1-0-0-example.json
.. _`MidMetaDataAnnotate request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_MidMetaDataAnnotate-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_MidMetaDataAnnotate-request-1-0-0-example.json
.. _`MidMetaDataAnnotate response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_MidMetaDataAnnotate-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_MidMetaDataAnnotate-response-1-0-0-example.json
.. _`OrphanedMids request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_OrphanedMids-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_OrphanedMids-request-1-0-0-example.json
.. _`OrphanedMids response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_OrphanedMids-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_OrphanedMids-response-1-0-0-example.json
.. _`SetMidMetaData request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_SetMidMetaData-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_SetMidMetaData-request-1-0-0-example.json
.. _`SetMidMetaData response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_SetMidMetaData-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_SetMidMetaData-response-1-0-0-example.json
.. _`SetNodeMetaData request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_SetNodeMetaData-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_SetNodeMetaData-request-1-0-0-example.json
.. _`SetNodeMetaData response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/#iqrf/infoDaemon_SetNodeMetaData-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/v230/json/iqrf/examples/infoDaemon_SetNodeMetaData-response-1-0-0-example.json
