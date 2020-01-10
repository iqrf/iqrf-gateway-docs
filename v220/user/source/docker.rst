******
Docker
******

Run IQRF Gateway in Docker environment in a few seconds. 

Repository
##########

.. code-block:: bash

  git clone https://gitlab.iqrf.org/open-source/iqrf-gateway-docker
  cd iqrf-gateway-docker

Start the gateway
+++++++++++++++++

.. code-block:: bash

  docker-compose -f docker-compose_amd64/armhf/armel.yml pull
  docker-compose -f docker-compose_amd64/armhf/armel.yml up -d

Stop the gateway
++++++++++++++++

.. code-block:: bash

  docker-compose down

IQRF Gateway Webapp
###################

Dockerfiles
+++++++++++

* https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/tree/master/docker
* https://cloud.docker.com/u/iqrftech/repository/docker/iqrftech/iqrf-gateway-webapp

Point the browser to http://gw-ip:8080/ and explore. Daemon configuration is not yet 
solved since there is a need to restart the daemon (container) after new configuration
being made. Web tools to work with IQRF network are ready to be explored.

IQRF Gateway Daemon
###################

Dockerfiles
+++++++++++

* https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/tree/master/docker
* https://cloud.docker.com/u/iqrftech/repository/docker/iqrftech/iqrf-gateway-daemon

There is a readme file in Gitlab repository if you want to build an image for yourself.  

Tools
+++++

.. code-block:: bash

  sudo apt-get install mosquitto-clients

.. code-block:: bash

  wget https://github.com/vi/websocat/releases/download/v1.1.0/websocat_1.1.0_amd64.deb
  sudo dpkg -i websocat_1.1.0_amd64.deb
  sudo apt-get install -y jq
  rm -f websocat_1.1.0_amd64.deb

Examples
++++++++

.. code-block:: bash

  git clone https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon
  cd iqrf-gateway-daemon/examples/bash
  ./mqtt-generic-blink.sh
  ./websocket-generic-blink.sh
