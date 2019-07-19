**********************************
How to install the webapp
**********************************

Add PHP 7.3 repository
######################

If you are using Debian 9, Raspbian 9, UbiLinux 4 or Ubuntu 16.04 you have to add PHP 7.3 repository.

For Debian
----------
.. code-block:: bash

	sudo apt-get -y install apt-transport-https lsb-release ca-certificates
	sudo wget -O /etc/apt/trusted.gpg.d/php.gpg https://packages.sury.org/php/apt.gpg
	sudo sh -c 'echo "deb https://packages.sury.org/php/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/php.list'
	sudo apt-get update

For Raspbian
------------
.. code-block:: bash

	sudo apt-get -y install apt-transport-https lsb-release ca-certificates dirmngr
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys D93B0C12C8D04D7AAFBCFA27CCD91D6111A06851
	sudo sh -c 'echo "deb https://repozytorium.mati75.eu/raspbian stretch-backports main contrib non-free" > /etc/apt/sources.list.d/php.list'
	sudo apt-get update

For UbiLinux
------------
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

Add IQRF Gateway repository
###########################

For Debian and UbiLinux
-----------------------

Buster 10
+++++++++
.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian buster stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Stretch 9
+++++++++
.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/debian stretch stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

For Ubuntu
----------

Bionic 18.04
++++++++++++
.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu bionic stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Xenial 16.04
++++++++++++
.. code-block:: bash

	sudo apt-get install dirmngr apt-transport-https
	sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9C076FCC7AB8F2E43C2AB0E73241B9B7B4BD8F8E
	echo "deb https://repos.iqrf.org/ubuntu xenial stable testing" | sudo tee -a /etc/apt/sources.list.d/iqrf.list
	sudo apt-get update

Install IQRF Gateway webapp
###########################
.. code-block:: bash

	sudo apt-get install iqrf-gateway-webapp
