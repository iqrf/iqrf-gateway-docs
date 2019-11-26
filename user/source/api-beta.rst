Beta Application Programming Interface
======================================

**v2.2.0-beta** - only new or modified JSON messages for communication via `MQ`_/`WS`_/`MQTT`_ channels.

.. _`MQ`: https://en.wikipedia.org/wiki/Message_queue
.. _`WS`: https://en.wikipedia.org/wiki/WebSocket
.. _`MQTT`: https://cs.wikipedia.org/wiki/MQTT

Timestamps
----------

Timestamps are in ISO8601 Date (Extend) format.

- YYYY-MM-DDThh:mm:ss.sss±hh:mm (2019-08-22T22:05:16.583+02:00)

IQRF Standard
-------------

Standard messages has been design according to `IQRF Standard`_ and `DPA protocol`_.

.. _`IQRF Standard`: https://www.iqrfalliance.org/techDocs
.. _`DPA protocol`: https://www.iqrf.org/DpaTechGuide

Sensor
++++++

Extending FRC for NADR and metadata information.

- `Sensor Frc request v1-0-0`_ and `example`__
- `Sensor Frc response v1-0-0`_ and `example`__

.. _`Sensor Frc request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfSensor_Frc-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfSensor_Frc-request-1-0-0-example.json
.. _`Sensor Frc response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfSensor_Frc-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfSensor_Frc-response-1-0-0-example.json

Dali
++++

Support for new IQRF standard.

- `SendCommands request v1-0-0`_ and `example`__
- `SendCommands response v1-0-0`_ and `example`__
- `SendCommandsAsync request v1-0-0`_ and `example`__
- `SendCommandsAsync response v1-0-0`_ and `example`__
- `Dali Frc request v1-0-0`_ and `example`__
- `Dali Frc response v1-0-0`_ and `example`__

.. _`SendCommands request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_SendCommands-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_SendCommands-request-1-0-0-example.json
.. _`SendCommands response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_SendCommands-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_SendCommands-response-1-0-0-example.json
.. _`SendCommandsAsync request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_SendCommandsAsync-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_SendCommandsAsync-request-1-0-0-example.json
.. _`SendCommandsAsync response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_SendCommandsAsync-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_SendCommandsAsync-response-1-0-0-example.json
.. _`Dali Frc request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_Frc-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_Frc-request-1-0-0-example.json
.. _`Dali Frc response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfDali_Frc-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfDali_Frc-response-1-0-0-example.json

Embed OS
--------

Fixes and changes related to DPA 4.10.

- `Read OS request v1-0-0`_ and `example`__
- `Read OS response v1-0-0`_ and `example`__
- `TestRfSignal request v1-0-0`_ and `example`__
- `TestRfSignal response v1-0-0`_ and `example`__
- `FactorySettings request v1-0-0`_ and `example`__
- `FactorySettings response v1-0-0`_ and `example`__

.. _`Read OS request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_Read-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_Read-request-1-0-0-example.json
.. _`Read OS response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_Read-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_Read-response-1-0-0-example.json
.. _`TestRfSignal request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_TestRfSignal-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_TestRfSignal-request-1-0-0-example.json
.. _`TestRfSignal response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_TestRfSignal-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_TestRfSignal-response-1-0-0-example.json
.. _`FactorySettings request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_FactorySettings-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_FactorySettings-request-1-0-0-example.json
.. _`FactorySettings response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqrfEmbedOs_FactorySettings-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqrfEmbedOs_FactorySettings-response-1-0-0-example.json

IQMESH Network
--------------

Services that ease the task of working with IQMESH network. They are composed of more then single DPA transaction 
(req-cnf-rsp) in most of the cases. They are also integrating information from `IQRF Repository`_. They are 
inspired by the services available in `IQRF IDE`_ - IQMESH Network Manager.

.. _`IQRF Repository`: https://repository.iqrfalliance.org/doc/
.. _`IQRF IDE`: https://iqrf.org/technology/iqrf-ide

IQRF Bonding
++++++++++++

Fixes and improvements.

- `SmartConnect request v1-0-0`_ and `example`__
- `SmartConnect response v1-0-0`_ and `example`__
- `AutoNetwork request v1-0-0`_ and `example`__
- `AutoNetwork response v1-0-0`_ and `example`__

.. _`SmartConnect request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_SmartConnect-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_SmartConnect-request-1-0-0-example.json
.. _`SmartConnect response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_SmartConnect-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_SmartConnect-response-1-0-0-example.json
.. _`AutoNetwork request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_AutoNetwork-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_AutoNetwork-request-1-0-0-example.json
.. _`AutoNetwork response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_AutoNetwork-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_AutoNetwork-response-1-0-0-example.json

IQRF Enumeration
++++++++++++++++

Fixes and changes related to DPA 4.10.

- `EnumerateDevice request v1-0-0`_ and `example`__
- `EnumerateDevice response v1-0-0`_ and `example`__

.. _`EnumerateDevice request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_EnumerateDevice-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_EnumerateDevice-request-1-0-0-example.json
.. _`EnumerateDevice response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_EnumerateDevice-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_EnumerateDevice-response-1-0-0-example.json

IQRF Configuration
++++++++++++++++++

Changes related to DPA 4.10.

- `ReadTrConf request v1-0-0`_ and `example`__
- `ReadTrConf response v1-0-0`_ and `example`__
- `WriteTrConf request v1-0-0`_ and `example`__
- `WriteTrConf response v1-0-0`_ and `example`__

.. _`ReadTrConf request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_ReadTrConf-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_ReadTrConf-request-1-0-0-example.json
.. _`ReadTrConf response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_ReadTrConf-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_ReadTrConf-response-1-0-0-example.json
.. _`WriteTrConf request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_WriteTrConf-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_WriteTrConf-request-1-0-0-example.json
.. _`WriteTrConf response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/iqmeshNetwork_WriteTrConf-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/iqmeshNetwork_WriteTrConf-response-1-0-0-example.json

Daemon Management
-----------------

IQRF SPI upload for IQD-GW-01 or KON-RASP-02 devices.

- `Upload request v1-0-0`_ and `example`__
- `Upload response v1-0-0`_ and `example`__

.. _`Upload request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/mngDaemon_Upload-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/mngDaemon_Upload-request-1-0-0-example.json
.. _`Upload response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/mngDaemon_Upload-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/mngDaemon_Upload-response-1-0-0-example.json

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

.. _`StartEnumeration request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_StartEnumeration-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_StartEnumeration-request-1-0-0-example.json
.. _`StartEnumeration response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_StartEnumeration-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_StartEnumeration-response-1-0-0-example.json
.. _`GetNodes request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetNodes-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetNodes-request-1-0-0-example.json
.. _`GetNodes response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetNodes-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetNodes-response-1-0-0-example.json
.. _`GetSensors request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetSensors-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetSensors-request-1-0-0-example.json
.. _`GetSensors response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetSensors-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetSensors-response-1-0-0-example.json
.. _`GetBinaryOutputs request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetBinaryOutputs-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetBinaryOutputs-request-1-0-0-example.json
.. _`GetBinaryOutputs response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetBinaryOutputs-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetBinaryOutputs-response-1-0-0-example.json
.. _`GetLights request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetLights-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetLights-request-1-0-0-example.json
.. _`GetLights response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetLights-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetLights-response-1-0-0-example.json
.. _`GetDalis request v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetDalis-request-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetDalis-request-1-0-0-example.json
.. _`GetDalis response v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/infoDaemon_GetDalis-response-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/infoDaemon_GetDalis-response-1-0-0-example.json

Daemon Notification
-------------------

Daemon state notifications related to interfaces, modes via websocket channel on port 1438.

- `Monitor message v1-0-0`_ and `example`__

.. _`Monitor message v1-0-0`: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/#iqrf/ntfDaemon_Monitor-message-1-0-0.json
.. __: https://apidocs.iqrf.org/iqrf-gateway-daemon/json/iqrf/examples/ntfDaemon_Monitor-message-1-0-0-example.json
