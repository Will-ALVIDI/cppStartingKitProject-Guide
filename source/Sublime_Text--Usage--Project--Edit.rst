Edit
====

Minimal settings for a Project
------------------------------

    * `Open the Side Bar`_
    * `Create a Project`_
    * Open the ``*.sublime-project`` file located to your `Project`_ location
    * ``Copy`` the following 


    ::
    
        {
            "folders":
            [
                {
                    "path": ".",
                    "file_exclude_patterns":
                    [
                        "*.sublime-project",
                    ]
                }
            ]
        }
    
    * ``Paste`` it inside the ``*.sublime-project`` file
        
.. note:: The ``"folders"`` parameter defines the folders included to your `Project`_.
 
 The ``"path"`` parameter specifies a folder you want to include.

 Specify ``.`` as setting for ``"path"`` parameter will include the folder where your `Project`_ was created.
 
 The ``"file_exclude_patterns"`` parameter hides from the **Side Bar** the display of specified extensions.
 
 The ``"*.sublime-project"`` as setting for ``"file_exclude_patterns"`` parameter will hide all the ``*.sublime-project`` file inside the `Project`_.

.. note:: For specific purposes your `Project`_, the internal tools or a plugin may require different settings.

 But **for beginners** or to quickly start a `Project`_ those settings are enough to make it work properly.
        
.. note:: 
        
Hide Project files with specific file extension
-----------------------------------------------

.. note:: This example will hide ``*.exe`` files from your `Project`_ 

-------------------------------------------------------------------------------
  
    * `Open the Side Bar`_  
    * `Open a Project`_ including at least one ``*.exe`` file
    * Open the ``*.sublime-project`` file located to your `Project`_ location
    * Locate the ``"file_exclude_patterns"`` parameter
    * If you use a `minimal settings for a Project`_ you must have 
    
    ::
    
        "file_exclude_patterns":
        [
            "*.sublime-project",
        ]
        
    * Modify the Settings by adding ``"*.exe,"``
    * You must have something like this
    
    ::
    
        "file_exclude_patterns":
        [
            "*.sublime-project",
            "*.exe",
        ]
        
.. note:: This will hide the ``*.exe`` files from the **Side Bar**.

.. _Create a Project: Sublime_Text--Usage--Project--Access.html#create-a-project
.. _Project: Sublime_Text--Usage--Project--Presentation.html  
.. _minimal settings for a Project: Sublime_Text--Usage--Project--Edit.html#minimal-settings-for-a-project
.. _Open a Project: Sublime_Text--Usage--Project--Access.html#open-a-project
.. _Open the Side Bar: Sublime_Text--Usage--Project--Access.html#create-a-project