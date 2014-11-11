How to add a message inside the terminal
========================================

Why do you have to do it
------------------------

If you added the `refresh .profile file`_ to your aliases you may need to insert a message at the end of the process to mention you that eveything goes right.

How to do it
------------

Create the message
``````````````````

    * Go to your **Shortcut folder**
    * Create a folder called ``Message``
    * Open the ``Message`` folder
    * Create a file called ``Refresh Profile.txt``
    * Enter your message, the following for example
    ::
    
        You successfully updated your profile !

Create the alias 
````````````````

    * Edit your .profile file
    * To add a message to the `refresh .profile file`_
    ::
    
        alias <YourAliasName>="source ~/.profile && cat <YourDrive>:/Path/to/the/Message/folder/Refresh\ Profile.txt"
    * `Refresh and apply`_ your changes
    
    
.. _refresh .profile file: Console_2--Usage--Aliases--Refresh_Profile.html
.. _Refresh and apply: Console_2--Usage--Aliases--Refresh_Profile.html

