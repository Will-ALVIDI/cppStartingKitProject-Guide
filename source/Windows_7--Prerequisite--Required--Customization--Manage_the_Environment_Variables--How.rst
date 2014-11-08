How to do it
============

Access
------

Environment Variables
`````````````````````

    * Open the **Start Menu**
    * ``Right-Click`` on **Computer**
    * Choose **Properties**
    * Click on **Advanced system settings**
    * Click on **Environment Variables**

Edit
----

Manage the Environment Variables
````````````````````````````````
    
Add path for all users
^^^^^^^^^^^^^^^^^^^^^^
    
    * Inside the **System variable** section
    * Find the **Path** variable
    * Click to **Edit**
    * Inside **Variable value** add a ``;``
    * Then add your path
    * Click **OK** to validate your changes

    
Add path for the current user
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    
    * Inside the **User variable for <YourUserName>** section
    * Click **New...**
    * Inside **Variable name** type **Path**
    * Then add your path
    * Click **OK** to validate your changes

Apply the changes
^^^^^^^^^^^^^^^^^

    * **Log off** or **Restart** your computer.

.. warning:: Be very careful if you use the **Add path to all users** method.
 Paths inside this field are critical for your system to work.

.. warning::  Notice the ``;`` between each paths.

.. tip:: **Safest way to manipulate those fields**
 
 * ``Copy`` ``Paste`` the content of those fields in a blank file inside your text editor 
 * Make the changes inside this file then ``Copy`` them
 * ``Paste`` your changes inside you environment variables 
 
.. tip:: It is recommended to use the **Add path for the current user** method.