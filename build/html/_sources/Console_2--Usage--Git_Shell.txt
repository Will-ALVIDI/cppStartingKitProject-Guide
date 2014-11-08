Set up Console 2 to automatically login to the Git for Windows Shell
====================================================================

    * **Open Console 2**
    * Go to the **Edit** menu

        * Then **Settings...**
        * From the hierarchy on the left select **Console**
        * Inside the **Shell** field type
        ::

            sh --login -i
    

.. note:: This command will automatically log you to the **Git for Windows Shell** when **Console 2** starts.

.. tip:: If for any reason you mess up with this field and **Console 2** doesn't want to reopen you can edit the configuration ``console.xml`` file inside the installation folder.

.. warning:: Don't put anything inside the **Startup Dir** field or you will encounter undesirable behaviors with the other specific functionalities you will have to set up in this guide.