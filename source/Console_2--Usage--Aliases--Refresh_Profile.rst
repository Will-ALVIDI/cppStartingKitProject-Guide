Alias to refresh the .profile file
==================================

Why do you have to do it
------------------------

Refresh your ``.profile`` file is something you have to do everytime you make changes inside your ``.profile`` file and you want to apply the changes.

To accelerate this repetitive task it is recommended to create an alias to do it.

How to do it
------------

    * Edit your ``.profile`` file
    * Type 
    ::
    
        alias <YourAliasName>="source ~/.profile"

.. note:: ``alias`` is the internal command you call to create an alias.
 
 ``<YourAliasName>`` is the name of the alias you wan to create. 

 ``source`` is the command to refresh and apply the changes. 

 ``~/.profile`` is the path of your ``.profile`` file. 
 
 ``~`` which stands for your Home directory.

.. warning:: The first time you edit the ``.profile`` file and you add this refresh fonctionality you need to refresh it manually before to be able to use the alias you created.

 To do it just type
 ::
 
    source ~/.profile