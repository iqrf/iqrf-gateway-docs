*************************
How to install the daemon
*************************

.. figure:: images/iqrfgd-overview.png
    :align: center
    :figclass: align-center

    Overview

Experimental Features
#####################

Major new features in the IQRF Gateway Daemon are introduced as experimental features at first. 
This allows you to play around with them and test them out in a developmental capacity without 
having it affect production targets. Once the feature is fully tested we will release it as a 
production feature.

Beta
----

The feature is still under development and should not be used on production targets as the 
underlying functionality as well as the APIs may change in future releases.

Add IQRF Gateway repository
###########################

`https://repos.iqrf.org`_

Stable
------

- iqrf-gateway-daemon_2.3.*_amd64.deb
- iqrf-gateway-daemon_2.3.*_i386.deb
- iqrf-gateway-daemon_2.3.*_arm64.deb
- iqrf-gateway-daemon_2.3.*_armhf.deb
- iqrf-gateway-daemon_2.3.*_armel.deb

Testing (Beta)
--------------

- iqrf-gateway-daemon_2.4.0-*_amd64.deb
- iqrf-gateway-daemon_2.4.0-*_i386.deb
- iqrf-gateway-daemon_2.4.0-*_arm64.deb
- iqrf-gateway-daemon_2.4.0-*_armhf.deb
- iqrf-gateway-daemon_2.4.0-*_armel.deb

For Debian, UbiLinux, Raspbian, Armbian
---------------------------------------

Buster 10
+++++++++
- Stable

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian buster stable" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

- Testing (Beta)

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian buster stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Stretch 9
+++++++++
- Stable

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian stretch stable" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

- Testing (Beta)

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian stretch stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

For Ubuntu
----------

Bionic 18.04
++++++++++++
- Stable

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu bionic stable" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

- Testing (Beta)

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu bionic stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Xenial 16.04
++++++++++++
- Stable

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu xenial stable" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

- Testing (Beta)

.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu xenial stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Stop and disable the daemon v1
##############################

If there is IQRF Gateway Daemon v1 already running in the system.

.. code-block:: bash

	sudo systemctl stop iqrf-daemon
	sudo systemctl disable iqrf-daemon

Install the daemon
##################

.. code-block:: bash

	sudo apt-get install iqrf-gateway-daemon

or **update** if the daemon is already installed.

.. code-block:: bash

	sudo apt-get update
	sudo apt-get --only-upgrade install iqrf-gateway-daemon

Update from beta release
------------------------

.. code-block:: bash

	sudo apt-get purge iqrf-gateway-daemon
	sudo apt-get install iqrf-gateway-daemon=2.3.*

Check the status of the daemon
##############################
.. code-block:: bash
	
	systemctl status iqrf-gateway-daemon.service

Direct links
############

Packages and tarballs for download.

- https://dl.iqrf.org/iqrf-gateway-daemon/buster
- https://dl.iqrf.org/iqrf-gateway-daemon/stretch
- https://dl.iqrf.org/iqrf-gateway-daemon/bionic
- https://dl.iqrf.org/iqrf-gateway-daemon/xenial

.. _`https://repos.iqrf.org`: https://repos.iqrf.org
