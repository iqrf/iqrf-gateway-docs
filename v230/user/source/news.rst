News
====

Known issues
------------

| IQRF GW webapp before version 2.0.1 is vulnerable to an code injection attack by passing 
  specially formed parameters to URL that is leading to RCE (CVE-2020-15227 
  (https://blog.nette.org/en/cve-2020-15227-potential-remote-code-execution-vulnerability, 
   https://nvd.nist.gov/vuln/detail/CVE-2020-15227)).

Documentation
-------------

 * Adding Webapp CLI description
 * Updating news and roadmap

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Mon, 16 Nov 2020 19:10:00 +0100

 * Updating news and roadmap

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Mon, 02 Nov 2020 12:00:00 +0100

 * Adding Webapp API page
 * Overall documentation update

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 07 Oct 2020 12:00:00 +0200

 * Adding Mender OTA update
 * Updating news

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Tue, 23 Jun 2020 12:00:00 +0200

Latest daemon
-------------

iqrf-gateway-daemon (2.3.5) stable; urgency=medium

 * `Changelog daemon 2.3.5`_

 -- Karel Hanák <karel.hanak@iqrf.org>  Fri, 08 Jan 2021 09:48:46 +0100

.. _`Changelog daemon 2.3.5`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.5/debian/changelog#L1

Latest webapp
-------------

iqrf-gateway-webapp (2.2.3) stable; urgency=medium

 * `Changelog webapp 2.2.3`_

 -- Karel Hanák <karel.hanak@iqrf.org>  Thu, 17 Dec 2020 17:13:05 +0100

.. _`Changelog webapp 2.2.3`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.3/debian/changelog#L1

Former daemon versions
----------------------

iqrf-gateway-daemon (2.3.4) stable; urgency=medium

 * `Changelog daemon 2.3.4`_

 -- Karel Hanák <karel.hanak@iqrf.org>  Thu, 17 Dec 2020 16:17:02 +0100

.. _`Changelog daemon 2.3.4`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.4/debian/changelog#L1

iqrf-gateway-daemon (2.3.3) stable; urgency=medium

 * `Changelog daemon 2.3.3`_

 -- Karel Hanák <karel.hanak@microrisc.com>  Mon, 23 Nov 2020 18:12:00 +0100

.. _`Changelog daemon 2.3.3`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.3/debian/changelog#L1

iqrf-gateway-daemon (2.3.2) stable; urgency=medium

 * `Changelog daemon 2.3.2`_

 -- Karel Hanak <karel.hanak@iqrf.com>  Mon, 02 Nov 2020 13:30:00 +0100

.. _`Changelog daemon 2.3.2`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.2/debian/changelog#L1

iqrf-gateway-daemon (2.3.1) stable; urgency=medium

 * `Changelog daemon 2.3.1`_

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Thu, 29 Oct 2020 12:15:00 +0100

.. _`Changelog daemon 2.3.1`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.1/debian/changelog#L1

iqrf-gateway-daemon (2.3.0) stable; urgency=medium

 * `Changelog daemon 2.3.0`_

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Sun, 25 Oct 2020 23:15:00 +0100

.. _`Changelog daemon 2.3.0`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.0/debian/changelog#L1

iqrf-gateway-daemon (2.3.0~rc2) testing; urgency=medium

 * `Changelog daemon 2.3.0~rc2`_

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Fri, 16 Oct 2020 22:00:00 +0200

.. _`Changelog daemon 2.3.0~rc2`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.0-rc2/debian/changelog#L1

iqrf-gateway-daemon (2.3.0~rc1) testing; urgency=medium

 * `Changelog daemon 2.3.0~rc1`_

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Mon, 05 Oct 2020 13:30:00 +0200

.. _`Changelog daemon 2.3.0~rc1`: https://gitlab.iqrf.org/open-source/iqrf-gateway-daemon/-/blob/v2.3.0-rc1/debian/changelog#L1

iqrf-gateway-daemon (2.2.2) stable; urgency=medium
 
 * Configuration change
  * Added parameter for websocket to accept connection from localhost only 
 
 * Fixed
  * Selection of updated IQRF OS in JS drivers

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Mon, 20 Jul 2020 12:00:00 +0200

iqrf-gateway-daemon (2.2.1) stable; urgency=medium

 * Fixed:
  * Websocket messaging parameter acceptOnlyLocalhost
  * Custom hwpId for coordinator commands
  * Selection of updated IQRF OS in JS drivers

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Wed, 15 Jul 2020 12:30:00 +0200

iqrf-gateway-daemon (2.2.0) stable; urgency=medium

 * Info:
  * Release version 2.2.0

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Sun, 21 Jun 2020 20:00:00 +0200

iqrf-gateway-daemon (2.2.0-rc6) testing; urgency=medium

 * Changed:
  * Periodic downloads from IQRF repository disabled

 * Fixed:
  * iqrfEmbedOs_WriteCfg
  * iqrfEmbedCoordinator_SetMID 

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Tue, 26 May 2020 13:30:00 +0200

iqrf-gateway-daemon (2.2.0-rc5) testing; urgency=medium

 * Improved:
  * WriteTrConf service
  * DPA 4.13 support

 * Fixed:
  * GetMidMetaData metadata API 

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 3 May 2020 18:00:00 +0200

iqrf-gateway-daemon (2.2.0-rc4) testing; urgency=medium

 * Improved:
  * IQRF SPI status handling
  * DPAVer formating in IQMESH services
  * Enhanced JsCache tracing 

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 6 Feb 2020 14:30:00 +0100

iqrf-gateway-daemon (2.2.0-rc3) testing; urgency=medium

 * Fixed:
  * Period setting in mngScheduler_AddTask API

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Fri, 20 Dec 2019 15:00:00 +0100

iqrf-gateway-daemon (2.2.0-rc2) testing; urgency=medium

 * Fixed:
  * LP timing for STD+LP networks

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Mon, 16 Dec 2019 14:30:00 +0100

iqrf-gateway-daemon (2.2.0-rc) testing; urgency=medium

 [ Frantisek Mikulu ]
 [ Roman Ondracek ]
 [ Vasek Hanak ]
 [ Rostislav Spinar ]

 * Added:
  * DPA 4.1x support
  * Timestamps in ISO8601 Date (Extend) format
  * IQRF Dali standard support
  * Sensor and Dali FRC extended format
  * IQMESH AutoNetwork core functionality
  * Daemon state monitoring service
  * Native TR upload for KON-RASP-02 compatible boards
  * Build for RPI1 and RPI zero boards

 * Improved: 
  * IQMESH WriteTrConf to enable broadcast
  * IQMESH SmartConnect service
  
 * Fixed: 
  * Missing TestRfSignal API
  * Minor repairs

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Fri, 6 Dec 2019 13:30:00 +0100

iqrf-gateway-daemon (2.1.7) RELEASED; urgency=medium

 * API: fix IQRF Sensor FRC schema
 * GitLab CI: change in configuration deploy folder

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Fri, 30 Aug 2019 07:00:00 +0200

iqrf-gateway-daemon (2.1.6) RELEASED; urgency=medium

 * GitLab CI: fix daemon version, fix debug package
 * GitLab CI: fix dependencies of the package for Debian Buster i386

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Fri, 19 Jul 2019 20:11:34 +0200

iqrf-gateway-daemon (2.1.5) RELEASED; urgency=medium

 [ Roman Ondracek ]

 * IQRF Repository: rewrite updater to Python3, update cache
 * GitLab CI: update package creation
 * Debian packaging: update name of paho.mqtt.c package
 * GitLab CI: fix build of temporary debug packages
 * GitLab CI: fix build of package for Debian Buster
 * GitLab CI: do not clean DAEMON_VERSION variable from the environment for Debian packaging

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Thu, 18 Jul 2019 23:51:47 +0200

iqrf-gateway-daemon (2.1.4) RELEASED; urgency=medium

 * Improved: Auto update of IQRF repository cache during package build
 * Updated: Sensor's FRC API doc
 * Fixed: IQRF BO's schemas
   
 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 6 Jun 2019 5:00:00 +0000

iqrf-gateway-daemon (2.1.3) RELEASED; urgency=medium

 * Fixed Scheduler's schemas
 * Fixed Sensor's FRC service
 * Updated Sensor's schemas
 * Updated IQRF repository cache
   
 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 30 May 2019 14:00:00 +0000

iqrf-gateway-daemon (2.1.2) RELEASED; urgency=medium

 * Removing Autonetwork service from API and CFG
  
 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Sun, 12 May 2019 21:00:00 +0000

iqrf-gateway-daemon (2.1.1) RELEASED; urgency=medium

 [ Frantisek Mikulu ]
 [ Roman Ondracek ]
 [ Rostislav Spinar ]

 * IQRF UART receive handling improved
 * IQRF repository cache updated
  
 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Wed, 8 May 2019 23:30:00 +0000

iqrf-gateway-daemon (2.1.0) RELEASED; urgency=medium

 [ Frantisek Mikulu ]
 [ Michal Konopa ]
 [ Vasek Hanak ]
 [ Dusan Machut ]
 [ Roman Ondracek ]
 [ Rostislav Spinar ]

 * DPAv40x support
 * Metadata API introduced
 * IQMESH service for RemoveBond
 * Scheduler API enhanced and persistent
 * Deb packages for Armel arch
 * Docker support
 * Source code released
 * Many fixes and improvements 
  
 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Fri, 3 May 2019 13:30:00 +0000

iqrf-gateway-daemon (2.0.0) RELEASED; urgency=medium

 [ Frantisek Mikulu ]
 [ Michal Konopa ]
 [ Roman Ondracek ]
 [ Rostislav Spinar ]

 * Requesting initial async packet from the coordinator if not received during boot
 * Monitoring initial async packet from the coordinator during runtime and setting RF mode
 * WriteTrConf service improved
 * BondNodeLocal and SmartConnect services improved
 * Setting hwpId for IQRF Sensor FRC fixed

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Thu, 22 Nov 2018 12:00:00 +0000

iqrf-gateway-daemon (2.0.0-rc) testing; urgency=medium

 [ Frantisek Mikulu ]
 [ Michal Konopa ]
 [ Vasek Hanak ]
 [ Dusan Machut ]
 [ Vlastimil Kosar ]
 [ Roman Ondracek ]
 [ Jaromir Mastik ]
 [ Michal Valny ]
 [ Rostislav Spinar ]

 * IQRF JSON API v2, v1
 * IQRF Standard
 * IQRF Repository - offline/online
 * IQMESH Network services
 * MQ, MQTT, Websocket messaging
 * SPI, UART, CDC interfaces
 * DPA timing - unicast, broadcast, FRC
 * DPA 3.03, 3.02

 -- Rostislav Spinar <rostislav.spinar@iqrf.com>  Tue, 31 Oct 2018 11:20:00 +0000

Former webapp versions
----------------------

iqrf-gateway-webapp (2.2.2) stable; urgency=medium

 * `Changelog webapp 2.2.2`_

 -- Karel Hanák <karel.hanak@iqrf.org>  Mon, 30 Nov 2020 07:13:59 +0100

.. _`Changelog webapp 2.2.2`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.2/debian/changelog#L1

iqrf-gateway-webapp (2.2.1) stable; urgency=medium

 * `Changelog webapp 2.2.1`_

 -- Karel Hanák <karel.hanak@microrisc.com>  Mon, 23 Nov 2020 13:55:07 +0100

.. _`Changelog webapp 2.2.1`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.1/debian/changelog#L1

iqrf-gateway-webapp (2.2.0) stable; urgency=medium

 * `Changelog webapp 2.2.0`_

 -- Karel Hanak <karel.hanak@iqrf.com>  Mon, 16 Nov 2020 09:34:40 +0100

.. _`Changelog webapp 2.2.0`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.0/debian/changelog#L1

iqrf-gateway-webapp (2.2.0-rc2) stable; urgency=medium

 * `Changelog webapp 2.2.0~rc2`_

 -- Karel Hanak <karel.hanak@iqrf.com>  Sat, 14 Nov 2020 16:36:26 +0100

.. _`Changelog webapp 2.2.0~rc2`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.0-rc2/debian/changelog#L1

iqrf-gateway-webapp (2.2.0-rc1) stable; urgency=medium

 * `Changelog webapp 2.2.0~rc1`_

 -- Karel Hanak <karel.hanak@iqrf.com>  Fri, 13 Nov 2020 18:50:54 +0100

.. _`Changelog webapp 2.2.0~rc1`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.2.0-rc1/debian/changelog#L1

iqrf-gateway-webapp (2.1.0) stable; urgency=medium

 * `Changelog webapp 2.1.0`_

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Sun, 25 Oct 2020 11:25:00 +0100

.. _`Changelog webapp 2.1.0`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.1.0/debian/changelog#L1

iqrf-gateway-webapp (2.1.0~rc3) testing; urgency=medium

 * `Changelog webapp 2.1.0~rc3`_

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 14 Oct 2020 01:55:00 +0200

.. _`Changelog webapp 2.1.0~rc3`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.1.0-rc3/debian/changelog#L1

iqrf-gateway-webapp (2.1.0~rc2) testing; urgency=medium

 * `Changelog webapp 2.1.0~rc2`_

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Fri, 09 Oct 2020 00:15:00 +0200

.. _`Changelog webapp 2.1.0~rc2`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.1.0-rc2/debian/changelog#L1

iqrf-gateway-webapp (2.1.0~rc1) testing; urgency=medium

 * `Changelog webapp 2.1.0~rc1`_

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Tue, 06 Oct 2020 06:10:00 +0200

.. _`Changelog webapp 2.1.0~rc1`: https://gitlab.iqrf.org/open-source/iqrf-gateway-webapp/-/blob/v2.1.0-rc1/debian/changelog#L1

iqrf-gateway-webapp (2.0.0) stable; urgency=medium

 * Info:
  * Release version 2.0.0

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Mon, 22 Jun 2020 20:00:00 +0200

iqrf-gateway-webapp (2.0.0-rc17) testing; urgency=medium

  * Prepare for version 2.0.0-rc17
  * API: check user language and role while user creation and editing
  * Makefile: fix patch for Doctrine ORM

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 10 Jun 2020 21:15:00 +0200

iqrf-gateway-webapp (2.0.0-rc16) testing; urgency=medium

  * Prepare for version v2.0.0-rc16
  * Makefile: apply patches for installation
  * GitLab CI: fix Debian package creation for IQD-GW-01
  * Makefile: do not install documentations for dependencies
  * API: add JSON schema for WiFi network list
  * Feature: add link to Grafana dashboard
  * Tests: add skeleton for API automated testing
  * API: fix user edit Tests: add features
  * GitLab CI: add API testing
  * GitLab CI: fix configuration
  * GitLab CI: fix syntax
  * API: fix API endpoint for user creation
  * API: fix JWT authenticator
  * Behat: refactor features
  * Behat: fix coding style
  * Gateway: fix disk, memory and swap sizes on 32-bit systems
  * Install: add error messages for SQL driver is missing (fix IQRF-GATEWAY-WEBAPP-3B) and database table is missing (fix IQRF-GATEWAY-WEBAPP-28)
  * Docker: fix images for latest tags
  * GitLab CI: fix IQD-GW-01 stable package build

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Sat, 06 Jun 2020 10:30:51 +0200

iqrf-gateway-webapp (2.0.0-rc15) testing; urgency=medium

  * Prepare for version 2.0.0-rc15
  * Config: fix Tracer file configuration forms
  * Core: replace form renderer
  * Config: fix TRacer file confuguration tool
  * Gateway: add list of installed packages into diagnostics archive
  * IQRF net: add workaround for DNS servers with scoped IPv6 address
  * Add tests, fix coding style
  * NPM: update dependencies
  * Fix Server Error page
  * Kernel: handle invalid or nonexistent version file
  * Guzzle: set timeout to 10 seconds
  * Core: refactor optional feature management, disable version checker
  * Gateway: check certificate and private key existence (fixes IQRF-GATEWAY-WEBAPP-1Q)
  * Console: fix coding style
  * Service: handle service manager process timeout (fixes IQRF-GATEWAY-WEBAPP-32)
  * Gateway: handle nonexistent IQRF Gateway Daemon log file (fixes IQRF-GATEWAY-WEBAPP-18)

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Sun, 24 May 2020 23:30:00 +0200

iqrf-gateway-webapp (2.0.0-rc14) testing; urgency=medium

  * Prepare for version 2.0.0-rc14
  * Makefile: install also files for API
  * IQRF net: hide empty footers in Standard manager
  * IQRF net: add previous light level indication (fix #234)
  * Update messages
  * Core: skip unreadable directories and files in ZIP archive
  * Config: trace verbosity level input make case insensitive
  * Core: fix permission fixing
  * Config: catch exceptions in scheduler task manager
  * Core: fix permission fixing while writing into file

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Thu, 14 May 2020 23:45:00 +0200

iqrf-gateway-webapp (2.0.0-rc13) testing; urgency=medium

  * Prepare for version v2.0.0-rc13
  * Service: fix flash messages in different modules
  * IQRF net: update P2P input labels in the TR configuration form
  * Config: fix scheduler form validation
  * IQRF net: partially disable TR configuration cache, fix FRC checkbox
  * Console: refactor commands
  * IQRF network: fix WebSocket client debug panel
  * IQRF network: refactor form factories
  * Config: hide disabled IQRF interfaces

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Fri, 08 May 2020 00:30:00 +0200

iqrf-gateway-webapp (2.0.0-rc12) testing; urgency=medium

  * Api: add REST API skeleton
  * API: add gateway endpoints
  * API: update annotations
  * API: add enpoint for IQRF IDE Macros
  * API: add diagnostics endpoint
  * API: add enponts to get and list component instances's configuration
  * API: add API endpoints for IQRF Gateway Daemon service manipulation
  * API: add endpoints for PIXLA client service manipulation
  * API: add API endpoints for Unattended upgrades service manipulation
  * API: add CORS policy
  * API: expose headers, fix annotations
  * API: add Basic authorization
  * Gateway: fix TR info displaying
  * API: add some clouds manager endpoints, fix coding style
  * API: fix authenticator
  * API: fix indentation in annotations
  * API: add endpoint for configuration component instance editing
  * API: add endpoints for component instance creating and deleting
  * API: add endpoints for editing and returning main configuration
  * API: add endpoint to create new component
  * API: use JWT authorization
  * API: fix JWT authorization
  * API: add endpoints to list network connections and interfaces
  * API: fix CORS headers
  * API: add API endpoints for connecting and disconnecting network interfaces
  * API: add endpoints for component configuration deleting and editing
  * API: edits the endpoint to get information about the configuration component
  * API: add endpoint to get network connection detail
  * API: add middleware for OPTION HTTP method handeling
  * API: Add respose entities
  * API: fix annotations, add entities
  * API: add endpoint to edit network connection
  * API: add endpoint to delete the network connection
  * API: fix bug in JWT authorization
  * API: fix coding style in JWT authorization
  * API: add SSH daemon service manager endpoints
  * Tests: add missing tests
  * Tests: add missing tests
  * API: add endpoint for network connectivity check
  * Network: add method to list available WiFi networks
  * Core: fix redirect after sign in
  * Gateway: add simple TLS certificate manager API: fix JWT signer
  * API: fix OpenAPI schema endpoint
  * API: add Amazon AWS IoT connection endpoint
  * Fix coding style
  * API: add JWT signature validation
  * Gateway: fix SSH daemon service manager (fix #231)
  * API: refactor OpenAPI specification endpoint
  * Config: fix creating a new component instance
  * Debian packaging: use IQRF Gateway Daemon's certificate for HTTPS, warmup templates during installation
  * API: catch invalid JSON exception
  * API: handle more error states in the configuration manager
  * API: add IQRF Gateway Daemon configuration schemas
  * API: add schemas for User manager and IQRF Gateway Webapp version endpoint
  * API: add more JSON schemas
  * API: add more JSON schemas
  * API: refactor service manager
  * GitLab CI: allow coverage stage to fail
  * Core: add privileged file manager
  * API: add endpoint to get IQRF interfaces
  * API: add JSON schema for Amazon AWS IoT connection creation
  * API: fix specification
  * API: fix User manager endpoints
  * Prepare for version 2.0.0-rc12
  * Composer: fix dependencies on older PHP versions
  * Fix typos
  * Fix coding style
  * API: fix typo in exception
  * Gateway: refactor system service controlling
  * IQRF net: remove DPA response parsers
  * Debian packaging: fix template warmup
  * Service: redesign status page

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Mon, 04 May 2020 22:00:00 +0200

iqrf-gateway-webapp (2.0.0-rc11) testing; urgency=medium

  * Prepare for version 2.0.0-rc11
  * Debian packaging: disable debug info in postinst
  * Config: skip corrupted files in listings
  * Tests: fix coding style
  * Composer: update UUID library
  * Debian packaging: fix tempates warmup
  * Debian packaging: fix postint script
  * Use Doctrine instead of Nette Database

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Fri, 24 Apr 2020 15:00:00 +0200

iqrf-gateway-webapp (2.0.0-rc10) testing; urgency=medium

  * Prepare for version 2.0.0-rc10
  * Debian packaging: fix iqrf-gateway-webapp-manager installation
  * Disable secure flag in session cookies

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Fri, 17 Apr 2020 00:22:05 +0200

iqrf-gateway-webapp (2.0.0-rc9) testing; urgency=medium

  * Prepare for version 2.0.0-rc9
  * Debian packaging: fix Apache2 configuration installation
  * Debian packaging: use PHP-FPM in Apache2 site configuration
  * Makefile: add skeleton of install target
  * Debian packaging: fix SQLite database owner
  * Debian packaging: update mainteiner scripts

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 15 Apr 2020 23:30:00 +0200

iqrf-gateway-webapp (2.0.0-rc8) testing; urgency=medium

  * Prepare for version 2.0.0-rc8
  * IQRF net: update flash messages on Coordinator upload page

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Tue, 14 Apr 2020 01:32:00 +0200

iqrf-gateway-webapp (2.0.0-rc7) testing; urgency=medium

  * Core: fix redirect after sign in
  * Core: hide User ID column for normal users
  * IQRF net: add TR configuration success read flash message for BFUs
  * Prepare for version 2.0.0-rc7
  * Config: skip invalid scheduler task files
  * Tests: fix scheduler tests
  * Config: enable IQRF Info component configuration tool for all users
  * IQRF net: add error message for device info table if daemon is not correctly responding
  * Core: add another redirect if the user is signed in (fix #226)
  * IQRF net: fix TR configuration form (fix #220)
  * Core: use own directory for sessions (fix #230)
  * IQRF net: add error messages for incorrect DPA sections (fix #221)
  * IQRF net: add missing Alternative DSM channel input field in TR configuration (fix #220)
  * Config: restart IQRF Gateway Daemon after scheduler task import
  * Config: fix texts on Scheduler task import page
  * IQRF net: fix typos in error messages for incorrect HWPID in DPA packet/JSON request
  * Gateway: fix SSH daemon service manager (fix #231)
  * Monolog: disable Git processor
  * Core: fix datagrid overflow (fix #233), fix sidabar toggle icon, update dependencies
  * Debian packaging: use IQRF Gateway Daemon's certificate for HTTPS, warmup templates during installation
  * Debian packaging: disable command printing
  * Config: fix scheduler ZIP archive import

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Mon, 13 Apr 2020 00:25:00 +0200

iqrf-gateway-webapp (2.0.0-rc6) testing; urgency=medium

  * Core: hide unnecessary inputs in user add form
  * Gateway: rename IQRF Gateway Daemon and SSH daemon service managers
  * Gateway: redesign power control

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Thu, 19 Mar 2020 13:20:00 +0100

iqrf-gateway-webapp (2.0.0-rc5) testing; urgency=medium

  * Update dependencies
  * IQRF net: rename error message "No response from IQRF Gateway Daemon." (fix #221)
  * Core: rename user edit form save button (fix #222)
  * IQRF net: fix coding style in IQRF Standard Sensor form template
  * Config: add scheduler's task validation
  * Config: fix scheduler's task validation
  * Config: rename labels in the scheduler's task configuration form
  * IQRF net: disable FRC embedded peripheral configuration for DPA 4.xx, rename TR configuration write button (fix #220)
  * IQRF net: fix coding style
  * Core: add link to docs (fix #223)
  * IQRF net: add information about the daemon restarting  at Coordinator upload page (fix #224)
  * Core: fix bug at sign in page (fix #226)
  * Config: fix uncatched exception in scheduler task editor
  * Config: add cache directory permissions workaround
  * Network: check exit code when reading network connection, add network connection deletion
  * Gateway: add SSH daemon service manager (fix #227)
  * IQRF net: skip devices with invalid address in device map

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 18 Mar 2020 19:40:00 +0100

iqrf-gateway-webapp (2.0.0-rc4) testing; urgency=medium

  * Sentry: update DSN keys
  * IQRF Net: fix JSON API request validation
  * GitLab CI: remove Debian 9 Stretch image generation for testing
  * GitLab CI: update phpDocumentator
  * Makefile: fix test target
  * Config: refactor scheduler manager
  * Debian packaging: skip tests
  * Config: add JSON schema validations for imported scheduler's tasks

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 12 Feb 2020 10:50:00 +0100

iqrf-gateway-webapp (2.0.0-rc3) testing; urgency=medium

  * IQRF Net: remove DALI support message
  * IQRF Net: fix ping nodes
  * Debian packaging: support also Apache2 web server and support multiple PHP versions
  * IQRF net: add confirmation messages for removing a node and clearing all bonds
  * Core: fix version
  * Fix coding style
  * Core: update router
  * IQRF net: add missing flash messages at Send DPA package and Send JSON request pages (fix #204)
  * Gateway: show the latest modified log file (fix #209)
  * Gateway: fix version and coding style
  * IQRF Net: merge TR configuration forms Core: refactor menu, user edit form and sign in
  * Core: update sign in logo, refactor sign out
  * Core: fix error pages
  * Config: enable JSON Metadata API configuration tool also for normal users
  * IQRF Net: rename TR upload to Coordinator upload, add info message (fix #202)
  * IQRF Net: show HWPID on Device enumeration page
  * Gateway: fix log viewer
  * IQRF Net: remove Autonetwork emdedded from DPA Macros (fix #216)
  * IQRF Net: edit texts on Coordinator upload page (fix #202)
  * Core: remove password hash from user list method
  * Core: try to fix permissions after file manipulation failure (fix #214)
  * Core: move CSS and JS source directories to the root directory
  * IQRF Net: remove old IQRF IDE Macros files
  * Gateway: refactor service control
  * Gateway: refactor unattended upgrade control panel
  * Gateway: refactor gateway mode control panel (fix #210)
  * IQRF Net: refactor TR configuration
  * IQRF Net: fix RF channel inputs in TR configuration
  * Core: fix password change for normal users
  * Gateway: remove one extra button for log downloading
  * Core: hide role and language columns in user datagrid for normal users
  * Core: fix coding style, refactor user datagrid
  * IQRF Net: fix TR configuration writing for nodes
  * Config: refactor scheduler configuration form, add support for multiple messages in one task (fix #219)
  * Config: fix scheduler configuration migration
  * IQRF Net: remove JSON API messages conversion to array (fix #194)
  * Config: fix save and restart button in scheduler task configuration form
  * Config: add redirect to datagrid if scheduler task does not exist
  * IQRF Net: add JSON API request validation on Send JSON request page
  * Config: add IQRF Info configuration tool (fix #200)
  * Config: fix datagrids - fix CSS overflow, fix AJAX snippet
  * Cloud: improve Hexio IoT Platform MQTT connection wizard
  * Install: add GW information download button (fix #218)
  * PHPStan: fix rule

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Sun, 09 Feb 2020 20:45:00 +0100

iqrf-gateway-webapp (2.0.0-rc2) testing; urgency=medium

  * Tests: fix tests for the webapp's version
  * GitLab CI: fix stable package deployment
  * Add PHP 7.4 support, update Monolog and Sentry (fix #179)
  * Debian packaging: fix patches
  * Add Rector, fix coding style

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Mon, 06 Jan 2020 13:37:07 +0100

iqrf-gateway-webapp (2.0.0-rc1) testing; urgency=medium

  [ Roman Ondracek ] 
  [ Rostislav Špinar ]

  * Fix test for the version manager
  * Add locks for tests which is manipulating with files
  * Catch exceptions in the scheduler configuration manager
  * Create a snapshot build of Debian package
  * Add sudo as Debian package dependency
  * Update IQRF Gateway Daemon's SPI configuration tool
  * Fix SPI pins mapping tool for SBCs
  * Update the installation guide
  * Add more translations for the datagrid
  * Add a skeleton of user documentation
  * Fix permissions in the Debian package
  * Hide OTA upload configuration tool
  * Fix typo in IQMESH configuration tool's presenter
  * Fix lintian tag `embedded-javascript-library`
  * Add packages `python3-sphinx` and `rsync` to the testing Docker image
  * Add the API documentation and User documentation deploy to GitLab CI
  * Add SSH client to the testing Docker image
  * Add `recommonmark` to the testing Docker image
  * Fix path to the user documentation to deploy
  * Fix Docker images
  * Fix a grammatical mistake in the user documentation
  * Add MQTT topics to the MQTT datagrid
  * Show only necessary components for a normal user
  * Add a method to get UART interfaces available in the system
  * Refactor IQRF CDC and SPI configuration presenters
  * Fix components order in the generic configuration manager
  * Add a lock before a scheduler's task deletion in the test
  * Fix a bug in the IQRF Gateway Daemon's configuration import
  * Add the IQRF UART interface configuration tool
  * Add JSON highlighter
  * Partially refactor websocket client
  * Refactor a websocket client
  * Change coding style checker's settings
  * Fix a translation in GW info
  * Update names of IQRF Gateway Daemon's directories
  * Refactor the version manager
  * Refactor tests for getting information about the gateway
  * Refactor the service manager
  * Add debug information into Websocket client
  * Fix bug in a saving of IQRF Gateway Daemon's configuration file
  * Update SPI and UART GPIO pins names
  * Fix URL to IQRF Gateway Daemon's websocket server
  * Refactor managers for a creation connection into cloud services
  * Fix bug in tests
  * Add a guide how to install PHP 7.2 on Raspbian 9
  * Refactor test for IQRF Gateway Daemon's service manager
  * Fix configuration error messages
  * Add more tests for cloud service managers
  * Fix the path for certificates for MQTT connections
  * Create the directory for certificates for MQTT connections
  * Fix IQRF JSON requests
  * Fix IQRF JSON requests in tests
  * Add a SPI port mapping
  * Rename the configuration tool for components for normal users
  * Move the navigation to own template
  * Fix whitespaces in the navigation
  * Add a port and pins mapping for UART interface
  * Update the PGP key of PHP repository for Raspbian
  * Update the root CA certificate for Amazon AWS IoT
  * Fix bug in the generic cloud service manager
  * Fix component's status changing from datagrid
  * Fix redrawing of the component's datagrid
  * Remove support of the old websocket service - shape::WebsocketService
  * Fix websocket interface manager
  * Allow status changes from the datagrid for MQ, MQTT and Websocket interface
  * Fix bugs in JSON validation against the JSON schema
  * Allow status changes from the datagrid for WebSocket messagings
  * Fix typos, update PHPDocs, sort imports and format source code
  * Add links to PDF and video guides for cloud services
  * Add the CLI tool for managing webapp
  * Refactor CLI tool
  * Add man page
  * Update Debian package and man page
  * Update docker images for testing
  * Add PHP 7.3 support to Travis CI
  * Update composer in PHP 7.2 and PHP 7.3 builds in GitLab CI
  * Cleanup IQRF DPA configuration tool
  * Refactor DPA request and response manager
  * Change namespace for IQRF Network module
  * Fix test for the router
  * Rename the file with translations for IQRF Network manager
  * Fix send DPA raw form
  * Scheduler uses APIv2 and displays the task time in human readable format
  * Fixed names of namespaces
  * Fix bugs in the scheduler's configuration tool
  * Improve user's data grid
  * Remove scheduler from manageable components by normal user
  * Fix IQRF Gateway Daemon's log viewer
  * Fix timezone in tests
  * Fix URL for checking updates
  * Update the installation guide
  * Decrease default WS client timeout to 26 seconds
  * Add scheduler's configuration migration
  * Redesign
  * Fix coding style
  * Add favicon
  * Fix bug in GW diagnostics
  * Use only stable composer's packages (fix problem with DI)
  * Add disk, memory and swap usages
  * Add IQMESH Network bonding manager
  * Use new API for setting an access password and an user key
  * Add IQMESH enumeration manager, add DPA version and RF mode to GW info
  * Fix name of IBM Cloud
  * Change the order of cloud services
  * Fix disk usage unit conversion
  * Add information about IQRF Gateway to GW info
  * Update phpDocumentator
  * Fix coding style
  * Follow redirects in phpDocumentator's download links
  * Fix bug in a swap usage
  * Update notification about a new version and about an offline mode
  * Fix changing of the IQRF Gateway Daemon mode
  * Fix badges in Read me, fix packagist's package name
  * Fix GitLab CI badge's URL
  * Fix the coding style in Read me
  * Workaround for broken dependencies of Kdyby/Translation
  * Update dependency on IQRF Gateway Daemon's Debian package
  * Update IQRF IDE Macros
  * Add code coverage generation into GitLab CI
  * Fix settings of coding style checker
  * Reload nginx service only if nginx service is started in Debian package installation and uninstallation
  * Add Docker testing images building and deploying into GitLab CI
  * Update Docker images for testing
  * Fix Docker testing images building and deploying in GitLab CI
  * Fix upload of testing Docker images to Docker Hub
  * Update Sentry's DSN
  * Revert "Remove a configuration tool for Tracer"
  * Fix a configuration tool for trace files
  * Add a basic datagrid for trace file service configuration tool
  * Update Docker images
  * Refactor GitLab CI configuration
  * Fix GitLab CI configuration
  * Fix GitLab CI configuration
  * Allow build failure of Docker image for Raspberry Pi
  * Add SPI restart option into IQRF SPI configuration tool
  * Set IQRF Gateway Daemon's WS server URL via ENV variable
  * Build new Docker images for each commit
  * Remove PHP 7.2 from the testing Debian Buster image
  * Remove build of Docker images for RPi (segfault) and update testing Docker images
  * Update changelog
  * Workaround for a failing creation of a new MQTT connection due unset values (fix #113)
  * Add form for sending a raw JSON DPA requests
  * Update the installation wizard, add button to show some GW info in the installation wizard
  * Fix coding style
  * Build and upload Docker images after tests
  * Fix a typo in GitLab CI's configuration
  * Fix coding style
  * Fix indents in composer file
  * Fix coding style
  * Fix templates for Tracer configuration tool
  * Fix Debian package dependencies
  * Make from a custom shell manager (`App\CoreModule\Models\CommandManager`) an adapter for `symfony/process` (fix #132)
  * Update PHP dependencies
  * Add prototype of IQRF Gateway Updater
  * Fix coding style in IQRF Gateway Updater
  * Fix coding style in lang files
  * Add gwmon customer ID to GW info, remove TR info from installation GW info
  * Remove unused imports form installation GW info presenter
  * Fix path to the gwmon customer ID
  * Add link to IQRF Gateway updater into webapp's navigation
  * Fix the Send JSON request form, add JSON schema validation for JSON requests to send
  * Fix coding style in IQRF network module
  * Add a new rfMode detection
  * Fix creation of JSON api request
  * Fix getting information about the Coordinator
  * Fix coding style in JSON API request
  * Fix RF mode parser
  * Refactor board managers
  * Use NPM and webpack for CSS and JS dependencies, add Sentry and textarea autosize
  * Refactor JS, add ESLint
  * Fix a default directory with scheduler's tasks
  * Rename Send JSON DPA request to Send IQRF JSON request
  * Fix an error message when a file with scheduler's tasks is not found
  * Optimize CSS and JS files for JSON highlighter
  * Add CSS minimizer, split JS files into modules, fix UART ports and pins selector
  * Add new JS files into the main template
  * Add EditorConfig
  * Fix PHPDoc for WS client's exceptions
  * Add a skeleton for a new IQMESH Network manager
  * Refactor IQMESH Network manager - mainly sections bonding and discovery, fix small bugs in IQMESH Network manager
  * Fix unexpected tabulars in IQMESH Network manager
  * Fix name for PIXLA Token and IQMESH Network type
  * Fix whitespaces in GW Info manager
  * Add Debian package deployment into GitLab CI
  * Fix Debian package deployment in GitLab CI
  * Fix development Debian package deployment environment name in GitLab CI
  * Fix IQMESH Security title
  * Fix missing title for IQRF IDE Macros
  * Hide Power user role in the first user creation
  * Split off TR configuration from IQMESH Network Manager
  * Simplify TR configuration tab names
  * Add an missing empty param object to Clean all bonds request
  * Swap positions of IQMESH Network manager and TR configuration
  * Fix title of IQMESH Network manager's form
  * Fix network type change
  * Remove an unnecessary message Id control in WebSocket client
  * Refactor WebSocket client
  * Fix a visibility of stopSync method of WebSocket client
  * Use a package contributte/monolog instead of an unmaintained package Kdyby/Monolog for the error logging into Sentry
  * Update PHPStan to version 0.11
  * Fix WebSocket client
  * Add Devices info into IQMESH Network manager
  * IQMESH Network manager: use decimal addresses instead of hexadecimals
  * TR configuration: do not fill embedded peripherals if the response is not successful
  * Core: Redirect to previous page after log in when user is logged out due inactivity
  * Core: update translations
  * Console: add some extra commands
  * TR configuration: move the RF configuration to the OS section
  * TR configuration: add flash messages informing about the TR configuration saving status
  * TR configuration: add flash messages informing about the TR security saving status
  * IQMESH Network manager: add flash messages informing about a bonding a discovery status
  * IQMESH Network manager: add device enumeration
  * JSON API request: fix the message ID addition
  * WebSocket client: make checking a response status as optional
  * IQRF Network: add missing flash messages translations
  * Send IQRF JSON request: add link to the documentation
  * IQMESH Network manager: use `iqmeshNetwork_RemoveBond` service for removing a bond and clearing all bonds
  * Clouds, Send IQRF JSON request: open the documentation in a new tab/window
  * Configuration: update a configuration tool for Scheduler to work with the new format
  * Configuration: update scheduler's configuration migration manager
  * Configuration: add test for scheduler's configuration migration
  * Configuration: fix coding style in a test for scheduler's configuration migration
  * Configuration: fix scheduler's configuration tool (period in ms, startTime is required only with exactTime)
  * Gateway: add IQRF Gateway Daemon's metadata and scheduler to the diagnostics data
  * Debian package: generate and apply self-signed certificate during the package installation process
  * GitLab CI: deploy docs only from branch `master`
  * GitLab CI: ignore branch name during Debian package's changelog generation
  * Debian package: remove diacritics from a self-signed certificate info
  * Debian package: remove old unnecessary directory
  * Debian package: fix sudoers for webapp
  * Gateway: add actions for powering off and rebooting IQRF Gateway
  * All: update date in copyright notices
  * Translations: fix typos
  * Configuration: fix the addition of a new task in scheduler
  * Configuration: fix a timeout in IQRF Raw message in tasks in the scheduler
  * Configuration: fix tests for scheduler's configuration tool
  * IQRF Net: Add a warning if the interoperability will be violated due a change in TR configuration
  * Configuration: Fix cron time parsing in scheduler's configuration tool
  * Configuration: add a button for saving scheduler's configuration and IQRF Gateway Daemon restart
  * Configuration: add IQRF Gateway Daemon's restart after successful scheduler's configuration import
  * Configuration: add IQRF Gateway Daemon's restart after successful configuration import
  * IQRF Net: add the coordinator to the Device Info
  * IQRF Net: update translations
  * IQRF Net: Use decimal addresses in bonded and discovered nodes parsers
  * IQRF Net: add NADR to the access password and the user key managers
  * IQRF Net: add a form for network address changing in TR configuration
  * IQRF Net: add basic IQRF Standard sensor manager
  * IQRF Net: fix name of IQMESH Network manager
  * IQRF Net: Add IQRF Standard binary output and IQRF Standard light device enumeration
  * IQRF Net: add IQRF Standard binary output state setting
  * IQRF Net: add a button `Back to IQMESH Network manager` into device enumeration
  * IQRF Net: add getting states of IQRF Standard binary outputs
  * IQRF Net: add changing and getting power of IQRF Standard light and redesign IQRF Standard manager
  * All: update PHPDocs, fix typos
  * IQRF Net: add some missing tests
  * Gateway: add missing tests for IQRF Gateway's power control manager
  * IQRF Net: add some missing tests
  * Tests: remove expected and actual output, add unit tests for Service module
  * Tests: add the database test case
  * Core: update the command manager
  * Core: move the router under CoreModule
  * Tests: refactor tests
  * Gateway: add list of upgradable packages
  * Test: fix coding style
  * Tests: fix namespaces
  * Include deb package also for Ubuntu
  * Config: add JSON Metadata API configuration tool
  * Gateway: add list of upgradable packages
  * Gateway: add an unsupported package manager error flash message
  * Debian package: fix corrupted sudo configuration
  * Debian package: fix corrupted sudo configuration
  * Tests: fix the path to the JSON schemas
  * App: refactor application's bootstrap
  * Configuration: specify a file extension of the configuration archive
  * Composer: add commands for running coverage and tests
  * Configuration: update the format of scheduler's configuration
  * Configuration: fix cron format in scheduler configuration tool
  * All: refactor form factories
  * Configuration: fix typo in scheduler's configuration migration
  * Configuration: rename `DPA Handler timeout` to DPA `Confirmation/Response timeout` in DPA configuration tool
  * Gateway: move board managers and package managers into own namespaces
  * Cloud: fix URL to IBM Cloud CA certificate
  * Gateway: Show error messages if the webapp cannot read log files
  * Gateway: fix imports in IQRF Gateway Daemon's log viewer presenter
  * IQRF Net: add a vertical scrolling to IQRF Standard tables, round IQRF Standard sensor values to two decimal places
  * IQRF Net: remove '?' from IQRF Standard sensor's units
  * Core: handle empty directories in the ZIP archive manager
  * Downgrade Latte template engine
  * Tests: fix path to version manager tests
  * Config: add scheduler's task time specification manager
  * IQRF Net: fix IQMESH security manager
  * Service: fix descriptions
  * All: fix size of headings
  * All: fix typos
  * IQRF Net: remove unnecessary rebond node action, fix bonding action's names
  * All: update JS bundles
  * Config: add option to accept WebSocket connections only from localhost
  * All: split NEON configuration files
  * Config: fix JS for the scheduler configuration tool
  * Core: normal users cannot create a new power user
  * All: use trait for flash messages in presenters
  * Debian package: add workaround for outdated composer in Debian stable
  * Tests: update Nette\Tester and PHPStan
  * IQRF Net: disable form validation for Clearing all bonds
  * IQRF Net: Add Smart Connect bonding test retries
  * Tests: update URL of echo WS server
  * IQRF Net: fix typo in bonding form
  * IQRF Net: refactor IQMESH Bonding form
  * IQRF Net: Hide unchangeable peripherals for normal users in TR configuration (DPA section)
  * Configuration: add workaround for scheduler's task deletion
  * QA: update code sniffer and fix coding style
  * All: use a trait for flash messages in presenters
  * PHPStan: add deprecation and strict rules
  * IQRF Net: update macros from IQRF IDE
  * All: Update menu
  * Cloud: Add TC Písek IoT Platform
  * Cloud: remove diacritics from TC Písek IoT Platform's name
  * Cloud: set default MQTT broker for TC Písek IoT Platform
  * IQRF net: add bonding test retries also for local bonding
  * IQRF net: rename OS configuration to RF configuration
  * Config: fix multiple instances error message in UDP configuration tool
  * Config: add flash messages in a configuration deletion
  * Config: fix bug in scheduler configuration tool
  * IQRF Network: fix names in IQRF Standard Manager (fix #160)
  * Gateway: rename titles, move Configuration migration into Configuration module
  * Service: mode under Gateway module
  * IQRF net: change IQRF Standard manager's name in the navigation menu
  * IQRF Network: fix link to IQRF Gateway Daemon's API documentation
  * Docker for ARMHF
  * Docker: refactor Dockerfiles
  * GitLab CI: fix paths to Dockerfiles
  * Docker: add support for armel, armhf, arm64, i386 and ppc64le
  * Debian: fix links to source repository
  * Docs: remove the user documentation
  * GitLab CI: fix used Docker images, update URLs
  * IQRF Network: add sensor's breakdown support
  * IQRF network: add error flash message for missing JSON schemas on Send JSON request page
  * Composer: update dependencies
  * Gateway: catch an exception on GW info page when the daemon's main configuration file doesn't exists
  * Composer: update version name of broken dependency
  * Debian: download PHP dependencies while package creation (fix #137)
  * Gateway: show GW mode on GW info page (fix #158)
  * Docker: update images for testing
  * Gateway: move the network manager into own class
  * Cloud: catch an exception if a directory for certificates cannot be created (fix #154)
  * Gateway: display short versions of the daemon and the webapp (fix #161, #150)
  * Gateway: rename page "Change gateway mode" to "Change mode"
  * Configuration: fix bad redirect on page Main configuration
  * All: use flash message trait also in datagrids and forms
  * Composer: fix guzzlette's dependency
  * Core: add alt attribute for logos
  * Gateway: fix format for released versions in the version manager
  * All: update PHPDocs and refactor callbacks
  * Debian: support multiple PHP versions (from PHP 7.1)
  * Core: allow users enable/disable specific functions (e.g. System updater)
  * Gateway: fix coding style in System updater presenter
  * Gateway: hide RFC 3041 addresses on GW info page
  * Core: fix typo in the successful message for editing users and fix translator
  * Gateway: add native upload
  * Gateway: add PIXLA client service manager (fix #157)
  * Console: add CLI command for managing optional features
  * IQRF network: fix the address validation in the bonding form (fix #164)
  * Debian: command iqrf-gateway-webapp-manager can use only root (fix #112)
  * Gateway: add error message about bad permissions
  * Gateway: remove information message at native upload form
  * IQRF network: show RF mode on enumeration page
  * Core: block all robots
  * GitLab CI: allow failure test on PHP 7.2 (due some bug), set PHP 7.3 as default PHP version
  * Debian packaging: support only PHP 7.3
  * Debian packaging: move caches and logs to the correct directories, fix the category of the manpage, remove unnecessary files, update standards version
  * Debian packaging: add comments to the rules file
  * Sentry: update DSN
  * GitLab CI: allow failure of Docker images for testing
  * Debian packaging: use the correct directory for configuration
  * IQRF Network: add product homepage and picture at device enumeration page
  * Composer: use PSR-4 instead of classmap
  * Debian packaging: fix path in patch for the correct configuration directory
  * Upgrade to Nette 3 (fix #155)
  * Remove support for PHP 7.1, workaround for contributte/console-extra
  * Use contributte/translation instead of Kdyby/Translation (fix #156)
  * Rename Native upload to TR upload and move it to IQRF network module
  * Core: fix ITranslator injection
  * IQRF network: fix the parent of Device enumeration presenter
  * Configuration: fix indents of the translator's configuration
  * Core: remove unused imports, fix ITranslator injection in the form factory
  * Debian packaging: update patches, remove unnecessary git files
  * IQRF network: fix bonding manager
  * IQRF network: remove an unused import in the bonding manager
  * Config: use the form renderer also for the configuration import forms
  * IQRF net: fix Send DPA packet form
  * IQRF net: fix coding style
  * IQRF net: fix names of groups in the TR configuration
  * Core: fix logging in without backlink
  * IQRF net: add tool for importing IQRF OS diffs
  * IQRF net: move Native upload manager from the gateway module into IQRF network module
  * Core: add hardening HTTP response headers (fix #172)
  * Core: fix Content Security Policy
  * Core: use relative paths in the main configuration file
  * IQRF net: Use UUID v4 instead of timestamp as message ID (fix #171)
  * IQRF net: remove unused import
  * Config: fix the input labels in the configuration forms
  * Config: fix WebSocket service datagrid
  * Cloud: move PIXLA manager from Gateway module to Cloud module
  * Tests: fix PHPStan rules
  * Core: add Tracy bar extension for Command manager
  * Config: replace unsupported question mark (no specific value) with asterisk (all values) in scheduler's cron-like expression
  * Core: refactor Command manager
  * Cloud: fix PIXLA flash messages
  * IQRF net: add removing nodes and clearing all nodes only on the Coordinator side
  * Tests: increase PHPStan level to 5
  * Tests: fix PHPStan configuration
  * Composer: fix Nette/Finder version
  * Composer: update IQRF IDE macros parser
  * IQRF net: disable TR upload by default
  * IQRF net: fix IQRF Binary output standard manager
  * IQRF net: fix LP icon in the device enumeration
  * Configuration: fix Tracer verbosity levels
  * Network: Add Ethernet connection manager (fix #51)
  * Features: disable Network manager by default
  * Gateway: fix Log file title
  * IQRF net: add tool for IQRF OS and DPA upgrade
  * IQRF net: fix DPA file names for DPA upload
  * IQRF net: catch an exception when DPA file to upload cannot be downloaded
  * Console: fix the feature disable command
  * Network: fix function to create a new IPv4 address entity from IPv4 address and subnet mask on 32-bit systems
  * Network: trim spaces in IPv4/IPv6 address entities
  * Network: add TUN connection into the connection type enum
  * IQRF net: add IQRF Standard DALI manager (fix #170)
  * IQRF net: add a checkbox for enabling DPA peer to peer communication in TR configuration
  * Gateway: add Unattended upgrades manager
  * Tests: use Makefile instead of Composer scripts
  * Config: show error message if the corresponding JSON schema is corrupted (fix #151)
  * IQRF net: fix the address validation in the network manager
  * Network: add massing error messages
  * Tests: fix PHPStan configuration
  * Core: fix JS error logging into Sentry
  * Network: catch Invalid UUID exception in the network connection configuration form
  * Debian packaging: add reverse proxy for IQRF Gateway Daemon's WS servers
  * Gateway: split optional updater feature into updater and unattendedUpgrades
  * Core: update GitLab repository URL in the webapp's version manager
  * Gateway: rename Unattended upgrades to Automatic upgrades
  * Network: fix Ethernet connection manager
  * Network: fix network connection enum annotations
  * Config: fix labels in WebSocket messaging configuration form
  * Config: refactor WebSocket configuration manager
  * Tests: update IQRF Gateway Daemon's configuration
  * Config: Add Daemon's monitor service configuration tool (fix #177)
  * Core: fix CSP at Error 500 page (fix #176)
  * Gateway: ignore empty files in the log viewer
  * Composer: update QA, Nette Tester a Tracy
  * Core: use dynamic module configuration loading
  * Cloud: add missing test for TC Písek IoT Platform MQTT connector
  * Debian packaging: update patches
  * Core: fix datagrid overflow on devices with small resolution (fix #121)
  * Core: refactor command manager
  * Network: add basic validation
  * Debian packaging: update dependencies
  * Network: add an error message if Network Manager is not installed
  * Gateway: remove confirmation dialogs for GW reboot and GW power off
  * Config: refactor tracer file configuration tool
  * Core: refactor JSON schema manager (fix #180)
  * NPM: update dependencies
  * IQRF net: add basic test for native upload manager
  * UI: indicate longer running tasks (fix #166)
  * Config: add default SPI pin mapping for UniPi Axon
  * IQRF net: add loading spinners for forms
  * IQRF net: catch an exception if IQRF Repository is unavailable (fix #183)
  * IQRF net: modify IQRF DALI flash message, fix warnings on IQRF Standards manager page
  * Gateway: show only local storage usage on GW Info page (fix #184)
  * IQRF net: fix the response viewer on Standard manager page
  * IQRF net: refresh the device map after device manipulation
  * QA: fix PHPStan rules
  * Cloud: rename PIXLA management title (fix #191)
  * Core: redesign error pages (fix #182)
  * Fix coding style in templates for Error pages
  * Network: fix Ethernet connection configuration form validation rules (fix #187)
  * Update Sentry DSN
  * IQRF net: catch an exception if the device is not certified at Device enumeration page
  * IQRF net: add FRC ping (fix #178)
  * NPM: update dependencies
  * IQRF net: refactor device manager
  * IQRF net: add tests for device manager
  * IQRF net: refactor DPA and IQRF OS manager for Native upload
  * IQRF net: refactor upload manager
  * IQRF net: add DPA upload form for normal users
  * IQRF net: fix DPA upload form
  * Update dependencies
  * IQRF net: add Coordinator DPA Handler upload for normal users
  * NPM: update dependencies
  * Commands: fix interface
  * Cloud: rename TC Pisek IoT platform to Hexio IoT platform
  * GUI: fix Font Awesome bar icon for navbar
  * Composer: update dependencies, fix coding style
  * Cloud: open PIXLA dashboard in a new tab
  * IQRF net: restart the daemon after Native upload
  * Fix coding style
  * Extend docker image for building docs
  * IQRF net: disable DPA timeout by default on Send raw page, update NPM dependencies
  * IQRF net: fix DPA Handler file validation on TR upload page
  * Core: add live form validator
  * Core: fix sign in form
  * GitLab CI: build packages also for IQD-GW-01
  * Debian packaging: fix patch for IQD-GW-01 package
  * IQRF net: fix JSON highlighting (fix #193)
  * Debian package: fix log directory permissions after every install/upgrade (fix #199)
  * Gateway: add IQRF Gateway Controller version and logs (fix #198)
  * Config: add task import (fix #181)
 
 -- Roman Ondracek <roman.ondracek@iqrf.com>  Tue, 31 Dec 2019 23:37:48 +0100

iqrf-gateway-webapp (2.0.0-beta) testing; urgency=medium

  * Add configuration tools for IQRF Gateway Daemon v2
  * Add PHPStan - tool for static analysis
  * Add JSON schema validation
  * Add support for Debian testing and Ubuntu 18.04 in the installer
  * Add an user manager
  * Add the installation wizard
  * Hide JSON Raw API and JSON Splitter configuration to a normal user
  * Move the link for the IQRF Gateway Daemon's configuration migration under the Gateway module
  * Drop PHP 7.0 support
  * Move core functionality into own module (CoreModule)
  * Update dependencies
  * Replace `iqrfapp` with a Websocket client
  * Rename project to `iqrf-gateway-webapp`
  * Removed configuration tools for IQRF Gateway Daemon v1

 -- Roman Ondracek <roman.ondracek@iqrf.com>  Wed, 05 Sep 2018 13:50:10 +0200
