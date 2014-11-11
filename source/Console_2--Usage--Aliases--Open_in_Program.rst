Alias to open a file with a specific program
============================================

How do do it
------------

.. note:: If you follow this guide from the beginning you added **Your Web Browser** to the `environment variables`_.

 This is what we will use as an example but you can do it with other programs.
 
.. warning:: Minimize the number of programs you add to your `environment variables`_.

.. tip:: Only add your very commomly used programs to your `environment variables`_ like your text editor and your web browser.

Create an alias to open a file with a specific program
````````````````````````````````````````````````````````

    * Edit your ``.profile`` file
    * Type
    ::
    
        alias <YourAliasName>="<YourProgram>"
    * `Refresh and apply`_ your changes
    
.. note:: Give the name of your program launcher, most of the time a ``YourProgram.exe`` file, without the extension

 For **Firefox** for example
 ::
 
    alias fx="Firefox"

.. note:: To open a web page from your terminal

.. note:: By following this example you can now launch google home page from your terminal by typing
 ::
 
    fx www.google.com

.. _environment variables: Windows_7--Prerequisite--Required--Customization--Manage_the_Environment_Variables.html
.. _refresh and apply: Console_2--Usage--Aliases--Refresh_Profile.html

