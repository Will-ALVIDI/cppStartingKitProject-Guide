Edit
====

Define User Settings
--------------------

Introduction
````````````

**To modify a setting** you have to edit the related **User Settings** file and ``Copy`` ``Paste`` to it the necessary chunks of code from the related **Default Settings** file.

For Example
````````````

Modify a setting of the text editor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    * Open the `Default Settings for the text editor`_
    * Open the `User Settings for the text editor`_
    
.. tip:: If your **User Settings** file is blank add those lines
 ::
 
    {
    
    }

-------------------------------------------------------------------------------

.. note:: Between those brackets your will add your **User Settings**.

-------------------------------------------------------------------------------

    * Locate inside the **Default Settings** file something you want to change and ``Copy`` it
    * For the example we want to change the font size specified as follow
    
    ::

        "font_size": 10,
    
    * ``Paste`` it to your **User Settings** file
    * Change the setting to something else
    * For the example we will use ``12`` as setting for the ``"font_size"`` parameter
    * Your **User Settings** file must look like this
    
    ::
    
        {
            "font_size": 12,
        } 
    
    * To apply the changes **Save** the file

.. warning:: In some cases you may need to restart Sublime Text to see the changes.
 
    
.. _Default Settings for the text editor : Sublime_Text--Usage--Preferences--Usage--Access--Default_Settings_for_the_Text_Editor.html
.. _User Settings for the text editor : Sublime_Text--Usage--Preferences--Usage--Access--User_Settings_for_the_Text_Editor.html