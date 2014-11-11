Alias to open a program
=======================

.. warning:: This manipulation **just open your program**, it doesn't open a file with this specific program.

Add your program to your Shortcut folder
----------------------------------------

Create a shortcut of your program 
`````````````````````````````````

    * Go to your installation folder
    * ``Right-Click`` on your program launcher

.. note:: Most a the time a ``*.exe`` file

-------------------------------------------------------------------------------

    * Choose **Send to**
    * Then **Desktop**

.. note:: It creates a shortcut to your program on your **Desktop**

-------------------------------------------------------------------------------

    * Go to your **Desktop**
    * ``Copy`` your shortcut
    * ``Paste`` it to your ``Shortcut`` folder

Create the alias to open your program
`````````````````````````````````````

    * Edit your ``.profile`` file
    * Type
    ::
    
        alias <YourAliasName>="start <YourProgramName>"
    * Refresh and apply your changes
    
.. tip:: Rename your shortcuts and avoid spaces.

.. _Refresh and apply: Console_2--Usage--Aliases--Refresh_Profile.html