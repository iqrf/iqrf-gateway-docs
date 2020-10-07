How to install the webapp
=========================

Install first `IQRF Gateway Daemon`_ package since IQRF repository is added during the daemon installation.
IQRF repository is also needed in order to install webapp interface.

Add PHP 7.3 repository
######################

If you are using Debian 9, Raspbian 9, UbiLinux 4, Ubuntu 16.04 or Ubuntu 18.04 you have to add PHP 7.3 repository.

For Debian 9, Raspbian 9 and UbiLinux 4
----------
.. code-block:: bash

	sudo apt-get -y install apt-transport-https lsb-release ca-certificates
	sudo wget -O /etc/apt/trusted.gpg.d/php.gpg https://packages.sury.org/php/apt.gpg
	sudo sh -c 'echo "deb https://packages.sury.org/php/ stretch main" > /etc/apt/sources.list.d/php.list'
	sudo apt-get update

For Ubuntu
----------
.. code-block:: bash

	sudo add-apt-repository ppa:ondrej/php
	sudo apt-get update

Install IQRF Gateway webapp
###########################
.. code-block:: bash

	sudo apt-get install iqrf-gateway-webapp

.. _`IQRF Gateway Daemon`: daemon-install.html
