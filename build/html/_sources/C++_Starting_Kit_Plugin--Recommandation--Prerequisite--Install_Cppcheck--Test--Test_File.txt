Test Sublime Linter - cppcheck
==============================

.. warning:: The following steps assume that you strictly followed the `set up Cppcheck for Sublime Text`_ and the `minimal set up for Sublime Linter - cppcheck`_ sections.

Create a testing file
---------------------

    * **Open Sublime Text**
    * **Create a new file** called ``test.cpp``
    * ``Copy`` ``Paste`` the following lines inside the ``test.cpp`` file
    
    ::
    
        #include <iostream>
        
        using namespace std;
        
        int main()
        {
            cout << "it works" << endl;
            
            return 0;

.. warning:: This chunk of code **contains voluntarily an error**.

 A ``}`` must be added after ``return 0;`` if you want your program to work correctly. 
 
 But **this is not what you need to test Sublime Linter - ccpcheck**.
 

.. _set up Cppcheck for Sublime Text: C++_Starting_Kit_Plugin--Recommandation--Prerequisite--Install_Cppcheck--How.html

If the set up of Sublime Linter - cppcheck is correct
`````````````````````````````````````````````````````

    * You must see
        
        * before the line numbers
        * **at line 6**
        * A ``huge white dot``

.. note:: This ``huge white dot`` notice you that **Sublime Linter - cppcheck** detects an error to this specific line.

 **If your set up is correct and you correct the error** by adding a ``}`` after the ``return 0;``, this ``huge white dot`` **must disappear**. 
 


.. _set up Cppcheck for Sublime Text: C++_Starting_Kit_Plugin--Recommandation--Prerequisite--Install_Cppcheck--How.html

.. _minimal set up for Sublime Linter - cppcheck: C++_Starting_Kit_Plugin--Recommandation--Prerequisite--Install_Cppcheck--Test--Minimal_Set_Up.html 