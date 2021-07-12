*************************
How to install the daemon
*************************

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

**Follow** the web guide at `https://repos.iqrf.org`_.

Stable
------

- iqrf-gateway-daemon_2.3.*_amd64.deb
- iqrf-gateway-daemon_2.3.*_i386.deb
- iqrf-gateway-daemon_2.3.*_arm64.deb
- iqrf-gateway-daemon_2.3.*_armhf.deb
- iqrf-gateway-daemon_2.3.*_armel.deb

Testing (release candidates)
----------------------------

- iqrf-gateway-daemon_2.3.0~rc*_amd64.deb
- iqrf-gateway-daemon_2.3.0~rc*_i386.deb
- iqrf-gateway-daemon_2.3.0~rc*_arm64.deb
- iqrf-gateway-daemon_2.3.0~rc*_armhf.deb
- iqrf-gateway-daemon_2.3.0~rc*_armel.deb

Devel (alpha, beta)
-------------------

- iqrf-gateway-daemon_2.4.0-*_amd64.deb
- iqrf-gateway-daemon_2.4.0-*_i386.deb
- iqrf-gateway-daemon_2.4.0-*_arm64.deb
- iqrf-gateway-daemon_2.4.0-*_armhf.deb
- iqrf-gateway-daemon_2.4.0-*_armel.deb

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
- https://dl.iqrf.org/iqrf-gateway-daemon/bionic

.. _`https://repos.iqrf.org`: https://repos.iqrf.org
