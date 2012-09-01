0.9 (in development)
====================

- #43: Added Russian translation (thanks to Andrey Cherepanov)
- Added French translation (thanks to Pierre Buard)
- Removed fast_taps, circular_touchpad, and edge_motion features, which will
  be removed in a future version of the synaptics driver

0.8.1 (Feb 11, 2012)
====================

- Website now hosted on http://synaptiks.readthedocs.org (thanks to the
  readthedocs.org team for this service)
- Mailing list now hosted at synaptiks@librelist.com
- Added Czech translation (thanks to Pavel Fric)
- Fixed syntax error in ``synaptiks_init_config.desktop``


0.8 (Oct 7, 2011)
=================

- Removed build-time dependency against kdesdk-scripts
- Fixed "Defaults" button in configuration dialog of tray application
- Fixed KeyError on unknown event types in keyboard monitor
- #21: Fixed crash after resume from suspend
- #17: Fixed support for non-usb devices
- Added Danish translation (thanks to Martin Schlander)


0.7 (Jun 27, 2011)
==================

- Require pyudev 0.8 or newer now
- #10: Increased maximum for minimum and maximum speed to 10.0


0.6.2 (Jun 9, 2011)
===================

- #11: Fixed punctuation


0.6.1 (Apr 23, 2011)
====================

- #9: Fixed installation of autostart files


0.6 (Apr 19, 2011)
==================

- #1: Use XRecord for keyboard management, if available
- #6: Reinitialize mouse monitoring and mouse display if the system is resuming
  from suspend
- #4: Fixed touchpad search on 64-bit systems


0.5.3 (Mar 8, 2011)
===================

- Fixed segfault on failed connection to X11 display in ``synaptikscfg``
- #7: Show a clean error message instead of a traceback, when no touchpad is
  found by ``synaptikscfg``


0.5.2 (Feb 8, 2011)
===================

- Fixed corner coasting configuration to actually reflect the corner coasting
  setting from the touchpad driver
- #3: Fixed property data extraction on 64 bit architectures


0.5.1 (Jan 31, 2011)
====================

- Fixed source distribution to include the handbook


0.5 (Jan 29, 2011)
==================

- Complete rewrite in Python instead of C++
- Removed daemon
- Removed touchpad management from System Settings module
- Added a separate system tray application for touchpad management, which is
  *not* started automatically

Miscellaneous changes
---------------------

- Detect two-finger emulation support and enable two-finger configuration, if
  emulation is supported
- The acceleration factor setting now supports four decimals after point for
  increased precision
- Use UDev instead of HAL for mouse device monitoring


0.4 (Apr 11, 2010) and older releases
=====================================

These releases were written in C++ and developed on other places, please refer
to the changelog_ of these legacy releases for information about changes.

.. _changelog: http://gitorious.org/synaptiks/synaptiks-website/blobs/master/changes.rst
