**********
Mender OTA 
**********

Update your **IQRF Gateway(s) fleet** using `Mender`_ platform in a few minutes. 

Mender server
#############

| Our testing server is running here: https://mender.iqrf.org

| When you build your image adjust it for your server in yml configuration or ask us
| for the demo at support@iqrf.org. 

Repository
##########

Build your custom Linux Yocto image for RPI with Mender support.

.. code-block:: bash

  git clone https://gitlab.iqrf.org/open-source/iqrf-gateway-os
  cd iqrf-gateway-os
  ./build_yocto_docker.sh

Download image
##############

Download, extract and burn image to your SD card or compute module using `Etcher`_ SW.

.. code-block:: bash

  https://dl.iqrf.org/iqrf-gateway-os/*.sdimage.bz2

Download artefact
#################

Once your devices are registered in Mender server update is done using *.mender artifacts from WebUI. 

.. code-block:: bash

  https://dl.iqrf.org/iqrf-gateway-os/*.mender

.. _`Mender`: https://mender.io/
.. _`Etcher`: https://www.balena.io/etcher/
