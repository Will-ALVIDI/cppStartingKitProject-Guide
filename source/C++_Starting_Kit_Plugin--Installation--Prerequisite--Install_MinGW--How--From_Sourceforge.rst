Install manually MinGW From SourceForge
=======================================

Installation
------------

Download
````````

From Sourceforge
^^^^^^^^^^^^^^^^

    * Go to `MinGW w64 project on SourceForge`_

    * From Here browse to :
   
        * **Toolchains targetting Win64**
        * **Personal Builds**
        * **mingw-builds**
        * **<Select latest version>**
        * **threads-posix**
        * **seh**
        * **<Select the latest version>** 
        
.. note:: Wait for your download and save it.     
 
Install
-------

.. note:: After the download you will have to extract the archive, rename it if you want, and place it to your desired path.

Post Installation
-----------------

Add MinGW bin folder to the environment variables
`````````````````````````````````````````````````

  * Add MinGW bin folder to the `environment variables`_.
  * The path you will have to add is
  
  ::
  
      <YourDrive>:\Path\To\MinGW\bin

.. note:: You can install multiple version of MinGW and specify explicitly later to Sublime Text the path of the compiler you want to use.

.. warning:: **To finish the installation** you must add **MinGW bin folder** path to your `environment variables`_. It should looks like follow :
 ::
    <YourDrive>:\Path\To\MinGW\bin

.. _environment variables: Windows_7--Prerequisite--Required--Customization--Manage_the_Environment_Variables.html    
.. _MinGW w64 project on SourceForge: http://sourceforge.net/projects/mingw-w64/files/