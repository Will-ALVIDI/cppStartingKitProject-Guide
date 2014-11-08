Add Open Console 2 inside the current directory from the Right-Click menu
=========================================================================

    * Create a file called ``OpenConsoleHere.reg``    

    * ``Copy`` ``Paste`` the following lines inside the ``OpenConsoleHere.reg`` file

    ::

        Windows Registry Editor Version 5.00
        [HKEY_CLASSES_ROOT\Directory\shell\Console2]
        @="Open Console Here"
        [HKEY_CLASSES_ROOT\Directory\shell\Console2\command]
        @="C:\\Path\\To\\Console\\2\\Console2.exe" 
        [HKEY_CLASSES_ROOT\Directory\Background\shell\Console2]
        @="Open Console Here"
        [HKEY_CLASSES_ROOT\Directory\Background\shell\Console2\command]
        @="C:\\Path\\To\\Console\\2\\Console2.exe"
        
.. note:: This registry tweak will add an option called ``"Open Console Here"`` to your Right-Click menu.

-------------------------------------------------------------------------------

    * Line **5** and **9** where you have 

    ::

        @="<YourDrive>:\\Path\\To\\Console\\2\\Console2.exe" 

    * Replace the paths by your own. Be sure to point to your Console 2 launcher (``*.exe`` file).
    * When it's done **Save** the file
    * ``Double-Click`` on ``OpenConsoleHere.reg`` file to add your new functionalities.
    * Accept the warning message.

.. note:: Now you should be able to open **Console2** from everywhere in your system and it will open it in the current directory. 