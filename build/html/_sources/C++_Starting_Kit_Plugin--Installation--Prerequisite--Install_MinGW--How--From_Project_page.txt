Install MinGW with the installer from the Project Page
======================================================

Installation
------------

Download
````````

From the project page
^^^^^^^^^^^^^^^^^^^^^

    * From the `MinGW w64 project page`_
    * Go to **Download** on the right side
    * ``Scroll-down`` until you see **Mingw-builds project - native toolchains using trunk**
    * There is a column called **Installation**
    * Click on the **SourceForge** link and wait for your download

.. note:: This last step should give you an installer : ``mingw-w64-install.exe``.

Install
```````

    * Launch the installer 
    * When the **Settings** window appears follow this setup

.. list-table::
   :widths: 20 60
   :header-rows: 0

   * - Version
     - Choose the latest
   * - Architecture
     - x64
   * - Threads
     - posix
   * - Exception
     - seh
   * - Build revision
     - choose the latest
     
Post Installation
-----------------

Add MinGW bin folder to the environment variables
`````````````````````````````````````````````````

  * Add **MinGW bin folder** to the `environment variables`_
  * The path you will have to add is
  
  ::
  
      <YourDrive>:\Path\To\MinGW\bin

.. note:: You can install multiple version of MinGW and specify explicitly later to Sublime Text the path of the compiler you want to use.

.. tip:: If you encouter issues with the installer `install MinGW manually`_
    
.. _MinGW w64 project page: mingw-w64.sourceforge.net
.. _environment variables: Windows_7--Prerequisite--Required--Customization--Manage_the_Environment_Variables.html
.. _install MinGW manually: C++_Starting_Kit_Plugin--Installation--Prerequisite--Install_MinGW--How--From_Sourceforge.html