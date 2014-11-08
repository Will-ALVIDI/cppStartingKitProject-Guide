Minimal set up for Sublime Linter - Cppcheck
============================================

.. warning:: The following steps assume that you strictly followed the `set up Cppcheck for Sublime Text`_ section.

-------------------------------------------------------------------------------

Open Sublime Linter preferences
-------------------------------

    * Go the **Preferences** menu
    
        * Then **Package Settings**
        * Then **Sublime Linter**
        * Choose **Settings - User**
        * **Locate the following lines**
        ::
        
            "linters": {
                "cppcheck": {
                    "@disable": true,
                    "args": [],
                    "enable": "style",
                    "excludes": [],
                    "std": []
            }

Enable Sublime Linter - cppcheck
--------------------------------

    * Replace ``true`` by ``false`` for the ``"@disable"`` parameter
    * You must have something like this
    
    ::
    
        "@disable": false,
        
Specify a standard syntax to Sublime Linter - cppcheck
------------------------------------------------------

    * Add ``"c++11"`` for the ``"std"`` parameter
    * You must have something like this
    
    ::
    
        "std": ["c++11"]

.. tip:: Now **Sublime Linter - cppcheck** has its minimal setup.

 It must work at this point but if you want to be sure follow the `testing process`_ section
        
.. _set up Cppcheck for Sublime Text: C++_Starting_Kit_Plugin--Recommandation--Prerequisite--Install_Cppcheck--How.html
.. _testing process: C++_Starting_Kit_Plugin--Recommandation--Prerequisite--Install_Cppcheck--Test--Test_File.html