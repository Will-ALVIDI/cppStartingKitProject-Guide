How to do it
============

Install Terminal plugin
-----------------------

Installation
````````````

    * Install this plugin from `Package Control`_
    
Setup Terminal to open Console 2 inside Sublime Text 3
------------------------------------------------------
    
    * Open your **Terminal Settings - User**
        * Go to the **Preferences** menu
        * Then **Package Settings**
        * Then **Terminal**
        * Then **Settings - User**
    
.. note:: This will open ``Terminal.sublime-settings``

-------------------------------------------------------------------------------

    * ``Copy`` ``Paste`` the following lines to the ``Terminal.sublime-settings`` file
    
    ::
    
        {
            "terminal": "",
            "parameters": []
        }
    
    * Add your path to Console 2 to the ``"terminal"`` parameter
    * You must have something like this
    ::

        "terminal": "<YourDrive>:/Path/To/Console2/console2.exe",

Add a Keyboard Shortcut to open Console 2 inside Sublime Text 3
---------------------------------------------------------------
    
    * Open your Terminal Key Bindings - User
        * Go to the **Preferences** menu
        * Then **Package Settings**
        * Then **Terminal**
        * Then **Key Bindings - User** 
        * Replace the keyboard shortchut(s) you want to change.

.. tip:: If you desire you can also override native commands like **Build** or/and **Run**.

.. note:: If your **Terminal Key Bindings - User** are blank, open the **Terminal Key Bindings - Default** and ``Copy`` ``Paste`` its contents inside your key bindings preferences.

.. _Package Control: Sublime_Text--Installation--Recommandation--Install_Package_Control--How.html