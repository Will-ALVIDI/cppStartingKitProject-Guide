Enable Make
===========

Why do you have to do it
------------------------

**Make** is known and used by Linux users as the ``make`` command. 

To use it you as such in **Windows 7** you need a ``make.exe`` file available to your environment variables.

**MinGW -w64** included this tool but by default its name is ``mingw32-make.exe``. 

How to do it
------------

.. note:: This step assumes that you have `MinGW -w64 installed`_.

Use mingw32-make from MinGW -w64 as make
````````````````````````````````````````

    * Go to your **MinGW -w64 bin folder**
    
      ::
  
      <YourDrive>:\Path\To\MinGW\bin
      
    * Locate ``mingw32-make.exe`` file
    * Rename it to ``make.exe``
    
.. _MinGW -w64 installed: C++_Starting_Kit_Plugin--Installation--Prerequisite--Install_MinGW.html