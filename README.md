Description
-----------

This driver is a Python wrapper of the  peak-linux-driver (in C) for Linux.


List of External dependencies
---------------------

- swig
  - sudo apt-get install swig

- peak-linux-driver-7.X
  - Please visit http://peak-system.com and download peak-linux-7.X

- gcc
- python-2.7


First Step : Library compilation
--------------------------------
> sudo make clean 
> sudo make


Second Step : Library installation
----------------------------------

> sudo make install

By default the module will be installed in /usr/lib


PATH settings
-------------

Add /usr/lib to the PYTHONPATH in order to find the module.

Example: export PYTHONPATH=/usr/lib:$PYTHONPATH


