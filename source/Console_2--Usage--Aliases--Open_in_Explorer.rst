Alias to open a specific directory inside the Windows Explorer
==============================================================

How to do it
------------

    * Edit your ``.profile`` file
    * Type
    ::
    
        alias <YourAliasName> = "start <YourDrive>:/Specific/Path"
    * `Refresh and apply`_ your changes

.. tip:: For example to open your ``Program Files`` folder create an alias like this
 ::
 
    alias <YourAliasName>="start c:/Program\ Files"

 The space between ``Program`` and ``Files`` is specified by ``\`` (an antislash) followed by a space.


.. warning:: Don't use ``\`` to separate your folders inside your paths but ``/``.

.. _Refresh and apply: Console_2--Usage--Aliases--Refresh_Profile.html