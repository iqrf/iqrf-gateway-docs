Webapp CLI
==========

The IQRF Gateway Webapp Manager is a command-line interface that can be used to manage the Webapp database and features from a command shell.

Synopsis
--------

The basic syntax for using the CLI tool is as follows::

	iqrf-gateway-webapp-manager <command> [options] [arguments]

Use *iqrf-gateway-webapp-manager help <command>* to display help message for specified command. Commands, their parameters and usage can be found below.
Commands can either be used in interactive mode by not specifying options, or non-interactive mode if all options are specified or the *--no-interaction* option is used.
Commands are split into several sections, options for each command group are at the end of the respective section.

General options
---------------

General options applicable to any command.

.. csv-table::
	:header: "Short", "Long", "Description"
	:widths: 8, 12, 50
	
	"``-h``", "``--help``", "Displays the CLI tool help message"
	"``-q``", "``--quiet``", "Do not output any message"
	"``-v``", "``--version``", "Display version of this application"
	"", "``--ansi``", "Force ANSI output"
	"", "``--no-ansi``", "Disable ANSI output"
	"``-n``", "``--no-interaction``", "Do not ask any interactive questions"
	"``-v|vv|vvv``", "``--verbose``", "Increases verbosity of messages: v for normal output, vv for more verbose output and vvv for debug output"

General commands
----------------

General commands for usage of the CLI tool.

help
^^^^

Displays help message for a specific command with description, arguments and usage.

Synopsis:

.. code-block:: bash

	iqrf-gateway-webapp-manager help <command>


list
^^^^

Lists all available commands.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager list

nette:cache:purge
^^^^^^^^^^^^^^^^^

Clears webapp cache.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager nette:cache:purge

API key commands
----------------

Commands used to manage API keys stored in the webapp database.

api-key:list
^^^^^^^^^^^^

Lists all existing API keys and their meta data.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager api-key:list

api-key:add
^^^^^^^^^^^

Creates a new API key and stores it in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager api-key:add [-d|--description DESCRIPTION] [-e|--expiration EXPIRATION]

api-key:edit
^^^^^^^^^^^^

Edits an existing API key and stores changes in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager api-key:edit [-i|--id ID] [-d|--description DESCRIPTION] [-e|--expiration EXPIRATION]

api-key:delete
^^^^^^^^^^^^^^

Remvoes an existing API key from the databasae.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager api-key:delete [-i|--id ID]

Options
^^^^^^^

Options for API key commands.

.. csv-table::
	:header: "Short", "Long", "Description"
	:widths: auto

	"``-i``", "``--id``", "API key ID"
	"``-d``", "``--description``", "API key description"
	"``-e``", "``--expiration``", "API key expiration"

Database commands
-----------------

Commands used to manage the webapp database.

database:create
^^^^^^^^^^^^^^^

Creates a new database for webapp.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager database:create

migrations:migrate
^^^^^^^^^^^^^^^^^^

Executes database migration to the latest version.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager migrations:migrate


Feature commands
----------------

Commands used to manage webapp features.

feature:list
^^^^^^^^^^^^

Lists all available webapp features.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager feature:list

feature:enable
^^^^^^^^^^^^^^

Enables a feature. Multiple features can be specified to be enabled at once.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager feature:enable <feature_name>

.. code-block:: bash

	iqrf-gateway-webapp-manager feature:enable <feature1_name> <feature2_name> ...

feature:disable
^^^^^^^^^^^^^^^

Disables a feature. Multiple features can be specified to be disabled at once.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager feature:disable <feature_name>

.. code-block:: bash

	iqrf-gateway-webapp-manager feature:disable <feature1_name> <feature2_name> ...

Mapping commands
----------------

Commands used to manage board pin mappings stored in webapp database.

mapping:list
^^^^^^^^^^^^

Lists all existing mappings in database and their properties.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager mapping:list


mapping:add
^^^^^^^^^^^

Creates a new board mapping and stores it in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager mapping:add [-t|--type TYPE] [-N|--name NAME] [-I|--interface INTERFACE] [-b|--bus-pin BUS_PIN] [-p|--pgm-pin PGM_PIN] [-P|--power-pin POWER_PIN] [-r|--baud-rate BAUD_RATE]

*Note: Baud rate is an optional argument unless the mapping type is set to UART.*

mapping:edit
^^^^^^^^^^^^

Edits an existing board mapping and stores changes in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager mapping:add [-i|--id ID] [-t|--type TYPE] [-N|--name NAME] [-I|--interface INTERFACE] [-b|--bus-pin BUS_PIN] [-p|--pgm-pin PGM_PIN] [-P|--power-pin POWER_PIN] [-r|--baud-rate BAUD_RATE]

mapping:remove
^^^^^^^^^^^^^^

Removes an existing board mapping from the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager mapping:remove [-i|--id ID]

Options
^^^^^^^

Options for board mapping commands.

.. csv-table::
	:header: "Short", "Long", "Description"
	:widths: auto

	"``-i``", "``--id``", "Mapping ID"
	"``-t``", "``--type``", "Mapping type, available options: spi, uart"
	"``-N``", "``--name``", "Mapping name"
	"``-I``", "``--interface``", "Mapping device name, example: /dev/ttyS0"
	"``-b``", "``--bus-pin``", "Mapping bus enable GPIO pin number"
	"``-p``", "``--pgm-pin``", "Mapping programming mode switch GPIO pin number"
	"``-P``", "``--power-pin``", "Mapping power enable GPIO pin number"
	"``-r``", "``--baud-rate``", "(optional) Baud rate for mapping type UART, available options: 1200, 2400, 4800, 9600, 19200, 38400, 57600, 115200, 230400"

User commands
-------------

Commands used to manage user profiles stored in the webapp database.

user:list
^^^^^^^^^

Lists all existing user profiles.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager user:list

user:add
^^^^^^^^

Creates a new user profile and stores it in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager user:add [-u|--username USERNAME] [-p|--password PASSWORD] [-r|--role ROLE] [-l|--language LANGUAGE]

user:edit
^^^^^^^^^

Edits an existing user profile and stores changes in the database.

Usage:

.. code-block:: bash

	iqrf-gateway-webapp-manager user:edit [-u|--username USERNAME] [-r|--role ROLE] [-l|--language LANGUAGE]

user:password
^^^^^^^^^^^^^

Changes password of an existing user profile and stores changes in the database.

.. code-block:: bash

	iqrf-gateway-webapp-manager user:password [-u|--username USERNAME] [-p|--password PASSWORD]

user:remove
^^^^^^^^^^^

Removes an existing user profile from the database.

.. code-block:: bash

	iqrf-gateway-webapp-manager user:remove [-u|--username USERNAME]

Options
^^^^^^^

Options for user commands.

.. csv-table::
	:header: "Short", "Long", "Description"
	:widths: auto

	"``-u``", "``--user``", "Username"
	"``-p``", "``--password``", "User's password"
	"``-r``", "``--role``", "User's role, available options: normal, power"
	"``-l``", "``--language``", "User's interface language, available options: en"
