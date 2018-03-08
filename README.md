# isthmus
Easy and modular OpenSimulator management and deployment for Linux. I made this system for my own 25 regions in OsGrid. Designed for OpenSim 0.9 and higher.

It's probably not good enough for commercial-grade grids but makes life a lot easier for hobbyists running multiple sims in an open grid.

This branch only works with opensim compiled from https://github.com/lickx/opensim (lickx branch or its descendants inventorybase or nani)

## Features
  * Easily upgrade all sims at once
  * Shared config and caches
  * Logical folder hierarchy
  * Issue mass commands (simauto) or per-sim (simctl)
  * Flexible OAR backups
  * Crash detection (and restart if needed)
  * Dynamic TCP port assignment (range 9000-9100)
  
## Preconfigured
Works out of the box for:

  * OsGrid (https://www.osgrid.org)
  * Metropolis (https://www.hypergrid.org)
  * Grids using phpgridserver (https://github.com/ft-/phpGridServer)

Other grids can add themselves, set your grid specific files up in  
share/grids/YourGrid (see other grids), then do a pull request.

For more info see the contents of the doc folder
