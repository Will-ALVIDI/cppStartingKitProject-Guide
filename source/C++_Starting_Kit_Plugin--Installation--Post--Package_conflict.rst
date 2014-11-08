Avoid package conflicts
=======================

.. warning:: This step avoid Sublime Text native C and C++ syntaxes to conflict with the C++ Starting kit plugin syntaxes.

-------------------------------------------------------------------------------

    * Open the `User Settings for the text editor`_
    * Locate the following line
    
    ::

        "ignored_packages": ["Vintage"]
    
    * Add ``C`` and ``C++`` syntaxes to the ``"ignored_packages"`` parameter
    * You must have something like this
    
    ::
    
        "ignored_packages": ["Vintage", "C", "C++"]    

    
.. _User Settings for the text editor: Sublime_Text--Usage--Preferences--Usage--Access--User_Settings_for_the_Text_Editor.html