.. rst-class:: chapter-with-expand

.. About Traits



.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .brown  {color:brown}  </style>
    <style> .green  {color:green}  </style>
    <style> .orange {color:orange} </style>


.. role:: brown
.. role:: green
.. role:: orange






===============================================
Tips & Troubleshooting
===============================================



.. |back-btn| image:: images/kds-android-back-1.png
            :scale: 90 %

.. |blue-bars| image:: images/ic_action_drawer_bright_blue.png
            :scale: 20 %

.. |back-btn2| image:: images/android-Back-50.png
            :scale: 17 %

.. |back-btn3| image:: images/kds-android-return-48.png
            :scale: 17 %

.. |back-area| image:: images/kds-back-area.png
            :scale: 70 %

.. |rotate-btn| image:: images/kds-rotate-btn.png
            :scale: 80 %

.. |accept-btn2| image:: images/ic_action_accept_black.png
            :scale: 90 %


.. |cancel-btn2| image:: images/ic_action_cancel_black.png
            :scale: 90 %



.. |expand| image:: _static/jean_victor_balin_add_blue.png
            :scale: 90 %


.. |contract| image:: _static/jean_victor_balin_remove_blue.png
            :scale: 90 %





This page contains a few general usage tips for KDSmart.

Select any heading to expand/display  |expand| or  contract |contract| the section.

|br|


Tips
=====

.. _Determining The Android Version:
.. rst-class:: activity

Determining The Android Version
"""""""""""""""""""""""""""""""

For support purposes, you may be asked to provide the version number of Android you are using.
This is a simple check to perform on your phone or tablet by performing the following:

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table::  Determining Android Version
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - From the phone's **Home Screen** (not in KDSmart) select |settings| **Settings**.
   * - **2.** 
     - Scroll down to the bottom and select either **About Phone** or **About Device**.
   * - **3.** 
     - Earlier versions the **Android Version** will appear in this list.
                  
                  .. only:: html
                  
                      |center-start|
                  
                      .. thumbnail:: images/AndroidVersion_2.png
                           :width: 40%
                           :show_caption: True
                           :alt: About Phone (Select to zoom)
                           :title: About Phone (Select to zoom)
                  
                      |center-end|
                  
                  .. only:: latex
                  
                      .. figure:: images/AndroidVersion_2.png
                         :scale: 60 %
                         :alt: About Phone (Select to zoom)
                         
                         About Phone (Select to zoom)                  

   * - **4.** 
     - Later versions select the **Software Info** item and **Android Version** should appear at the top.
                 
                 .. only:: html
                 
                     |center-start|
                 
                     .. thumbnail:: images/AndroidVersion_1.png
                          :width: 40%
                          :show_caption: True
                          :alt: Android Version (Select to zoom)
                          :title: Android Version (Select to zoom)
                 
                     |center-end|
                 
                 .. only:: latex
                 
                     .. figure:: images/AndroidVersion_1.png
                        :scale: 60 %
                        :alt: Android Version (Select to zoom)
                        
                        Android Version (Select to zoom)
     

|br|

.. rst-class:: activity

Continue Scoring The Previous Trial
"""""""""""""""""""""""""""""""""""

.. |image0| image:: images/ic_action_play_black.png
            :scale: 100 %


The name of the trial being scored is displayed on the KDSmart **Home Screen**. Just touch the |image0| **Start Scoring Button** or the trial name to continue from where you were previously scoring. 
KDSmart remembers the position or plot when you last exited the scoring activity for the trial (see the next section) and will present that plot to you.

|br|

.. rst-class:: activity

Quick Stop for a Break
""""""""""""""""""""""

.. |image1| image:: images/exit-where-autoscoring_framed.png
            :scale: 50 %

.. |image2| image:: images/exit-where-scoring-auto_on_framed.png
            :scale: 50 %

.. |image3| image:: images/exit-confirm-stop-scoring_framed.png
            :scale: 50 %


.. tabularcolumns:: |\Y{0.3}|\Y{0.3}|\Y{0.3}|

.. list-table:: 
   :widths: 20 20 20
   :class: longtable
   :header-rows: 0

   * - **1.** If in **Auto-advance Mode**, exit using the **Home Button** in the top left corner: |br| |image1| 
     - **2.** In the **Scoring Screen**, exit using the **Home Button** in the top left corner: |br| |image2| 
     - **3.** Confirm the exit by selecting the **Confirm Button** in the popup: |br| |br| |image3| 
   
|br|



.. raw:: latex
  
      \newpage

.. _Android Permissions:
.. rst-class:: activity

Android Permissions
"""""""""""""""""""

Android has introduced more stringent application security which affects KDSmart and any other Android application. Permission is required at the initial application installation, and may be requested again following installing any application updates. 

Without allowing permissions an application will not work, or be unable to use all its functionality.

Upon initial KDSmart installation, a message similar to the following example will be displayed. Selecting **Allow** will enable KDSmart to work.


  |br|

  .. only:: html

      |center-start|

      .. thumbnail:: images/kds-permission-msg2.png
           :width: 50%
           :show_caption: True
           :alt: Android Permission Request (Select to zoom)
           :title: Android Permission Request (Select to zoom)

      |center-end|

  .. only:: latex

      .. figure:: images/kds-permission-msg2.png
         :scale: 60 %
         :alt: Android Permission Request (Select to zoom)
         
         Android Permission Request (Select to zoom)

  |br|

If *Deny* is selected, KDSmart will display an advisory message (appearing in background of above image) with a |cancel-btn2| **Cancel Button** and an|accept-btn2| **Accept Button**. Selecting:

* **Cancel** will stop KDSmart; and
* **Accept** will cause Android to redisplay the approval request message again.

Selecting *Don't ask again*, if it is displayed, and *Deny* will require a visit to Android settings to restart the request process. See `Restoring/Changing Permissions`_ below for instructions.

The next example shows the permission request following an update to KDSmart, which must be accepted before the application will open.


  |br|

  .. only:: html

      |center-start|

      .. thumbnail:: images/kdsmart_accessto_msg.png
           :width: 40%
           :show_caption: True
           :alt: Android Access Permissions Request (Select to zoom)
           :title: Android Access Permissions Request (Select to zoom)

      |center-end|

  .. only:: latex

      .. figure:: images/kdsmart_accessto_msg.png
         :scale: 60 %
         :alt: Android Access Permissions Request (Select to zoom)
         
         Android Access Permissions Request (Select to zoom)

  |br|
  

.. rst-class:: activity

Why Must I Grant Access?
""""""""""""""""""""""""

Applications, including KDSmart, need to access the storage/memory on the device be able to:

* Load your trial/nursery data;
* To add to or make changes to that data; and 
* To save your data.

Quite simply, without allowing any permission, KDSmart **Will Not Work**.

Other features KDSmart can use on the device, such as the camera, microphone, etc. are also affected. The following table shows KDSmart permission requirements for the application or specific features to work:


.. tabularcolumns:: |\Y{0.25}|\Y{0.7}|

.. list-table::  KDSmart Permission Requirements
   :widths: 5 70
   :class: longtable
   :header-rows: 1
   :stub-columns: 0

   * - **Permission** |br| **Required**
     - **Description**
   * - **Camera**
     - Required if the camera is to be used by KDSmart.
   * - **Location**
     - Required if the location option has been enabled.
   * - **Microphone**
     - Required to record any audio notes using the microphone in KDSmart.
   * - **Storage**
     - **KDSmart will not work** without being given storage permission.
       This is required to store *any data* on the device e.g. sample data, trial import or export, traits, tags, etc.
   * - **Bluetooth**
     - Required if Bluetooth barcode scanners or scales are to be used.    



.. raw:: latex
  
      \newpage

.. rst-class:: activity

Restoring/Changing Permissions
"""""""""""""""""""""""""""""""

At some stage you may have denied KDSmart access, e.g. to the camera, or *Never ask again* has been selected. These settings can be changed by using the following procedure.


.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table::  Procedure to change KDSmart Permissions
   :widths: 5 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - 1
     - On the Android device, select the system **Settings Button** |settings|
   * - 2
     - Select **Applications**
   * - 3
     - Select **KDSmart**
   * - 4
     - Select **Permissions**
   * - 5
     - Enable the required permission. |br| **Remember Storage is mandatory** to use KDSmart and the other settings are needed if that functionality is required. |br|
     
       |br|
     
       .. only:: html
     
           |center-start|
     
           .. thumbnail:: images/kds-permission1.png
                :width: 40%
                :show_caption: True
                :alt: Permission Settings (Select to zoom)
                :title: Permission Settings (Select to zoom)
     
           |center-end|
     
       .. only:: latex
     
           .. figure:: images/kds-permission1.png
              :scale: 60 %
              :alt: Permission Settings (Select to zoom)
              
              Permission Settings (Select to zoom)
     
       |br|
            
       **Note:** Selecting **More** or the highlighted menu button illustrated at (1) displays **All permissions**. These additional settings will also affect KDSmart behaviours for certain features.


.. |settings| image:: images/settings-icn.png
            :scale: 50 %

|br|

.. rst-class:: activity

Database Integrity Check
""""""""""""""""""""""""


This database check and repair is mainly relevant in a situation where the following error occurs:

  |br|

  .. only:: html

      |center-start|

      .. thumbnail:: images/kds_error_plotvisitlist_construct_failed.png
          :show_caption: true
          :width: 50%
          :align: center
          :title: Example Error Requiring DB Integrity Check/Repair (select to zoom)

      |center-end|

  .. only:: latex

      .. figure:: images/kds_error_plotvisitlist_construct_failed.png
               :scale: 40%
               :alt: Example Error Requiring DB Integrity Check/Repair
               
               Example Error Requiring DB Integrity Check/Repair

  |br|

This function checks the KDSmart database for the existence of duplicate samples for a trait instance, plot, sub-plot in each trial and removes the sample *if the Trait Value is null*.

If any duplicate samples are found containing a value, the following error message will appear: |br| *"Duplicate Samples with a value  Please contact Diversity Arrays and send them your Database"* |br| will be displayed and the check/repair processing will stop.



Should repair display this message and is unable to proceed, please export the database and report the issue separately attaching the database in the email, or use an alternative file transfer method if the file is too large for email. |br| The option to export the database is located just above the **Database Integrity Check Button**.



.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table:: Steps to execute the Database Integrity Check
   :widths: 5 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - 1
     - At the **Home Screen** or menu by selecting the |kds_devices| **Manage Devices Button**. 
   * - 2
     - Within the **Database Tab**, select **Database Integrity Check**
        
        .. only:: html
        
            |center-start|

       
            .. thumbnail:: images/kds-database-integrity-check.png
                        :show_caption: true
                        :width: 30%
                        :align: center
                        :title: Database Integrity Check (select to zoom)

            |center-end|

        .. only:: latex

            .. figure:: images/kds-database-integrity-check.png
                        :scale: 60%
                        :alt: Database Integrity Check/Repair
                        
                        Database Integrity Check/Repair
        


.. note:: Depending upon the size of trials within the KDSmart database, this check could take more than 10-15 minutes. The check can be cancelled, however, any errors present may not be repaired.


.. raw:: latex
  
      \newpage

.. rst-class:: activity

Navigation Within KDSmart
"""""""""""""""""""""""""

Standard Android application navigation is used in KDSmart. The table below outlines some of the UI elements related to navigation.


.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table::  
   :widths: 20 70
   :class: longtable
   :header-rows: 1

   * - **Button**
     - **Description**
   * - |back-btn| or |back-btn3| or |back-btn2| 
     - **Back Buttons** to return to the previous screen.
   * - |back-area|
     - Selecting the **Back** area (highlighted) surrounds the top left corner containing the logo and trial name or similar region on one of the edit screens (e.g. edit trait, tag etc.).
   * -  |blue-bars|
     - **Side Menu** |br| Screens with three blue menu bars have a slide out a menu at the top left as illustrated. Select the menu bars to display or hide the menu.
        
         .. only:: html
         
             |center-start|

        
             .. thumbnail:: images/kds-side-menu.png
                         :show_caption: true
                         :width: 20%
                         :align: center
                         :title: Slide Out Menu (select to zoom)

             |center-end|

         .. only:: latex

             .. figure:: images/kds-side-menu.png
                         :scale: 60%
                         :alt: Slide Out Menu (select to zoom)
                         
                         Slide Out Menu (select to zoom)
       


.. raw:: latex
  
      \newpage


.. rst-class:: activity

Screen Orientation/Rotation
""""""""""""""""""""""""""""

Android is able to lock or prevent the screen from rotating |rotate-btn| for all apps on the device.
KDSmart behaves in accordance with this Android device setting.


.. tabularcolumns:: |\Y{0.4}|\Y{0.6}|

.. list-table::  
   :widths: 40 60
   :class: longtable
   :header-rows: 1

   * - **If Android Screen Rotation Is ...**
     - **Then KDSmart will ...**
   * - **Enabled**
     - Respond to changes in the screen orientation.
   * - **Disabled**
     - Not detect or respond to changes in the screen orientation.


.. Note:: Automatic rotation is intentionally disabled within the **Scoring Screen** to prevent undesirable screen changes. Various movements of the user and device in the field, such as bending down to inspect a sub-plot would cause frequent and unnecessary screen changes.

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table::  Steps to rotate the scoring screen (Landscape to Portrait, Portrait to Landscape)
   :widths: 5 80
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - 1
     - Ensure *Android Screen Rotation* is enabled. 
   * - 2
     - In KDSmart, exit from the scoring screen to another screen.
   * - 3
     - Turn the device to the required position (portrait or landscape).
   * - 4
     - Return to the **Scoring Screen** which should now display with the desired orientation.

|br|

.. rst-class:: activity

Lists and Select Mode for Multiple Selection
"""""""""""""""""""""""""""""""""""""""""""""

.. |action-menu| image:: images/ic_action_overflow_black.png
            :scale: 90 %
            
This is a generic tip for KDSmart trials, traits and tag selection lists. The example shown is the trial list.

  |br|
  
  .. only:: html
  
      |center-start|

 
      .. thumbnail:: images/kds-sel-list-example.png
                  :show_caption: true
                  :width: 60%
                  :align: center
                  :title: Multiple Selection Example (Select to zoom)

      |center-end|

  .. only:: latex

      .. figure:: images/kds-sel-list-example.png
                  :scale: 60%
                  :alt: Multiple Selection Example (Select to zoom)
                  
                  Multiple Selection Example (Select to zoom)
                  
  |br|


When a list of items is displayed, as the trial list in the left-hand image |circle1| above, a *long press* on any Trial item will invoke **Select Mode**. 

Once in **Select Mode**, multiple items may be selected, by touching them as illustrated in the right hand |circle2| image above where three trials have been selected. The number of items selected is indicated at the top right, in this example **Selected:3** appears.

Selecting the |action-menu| **Action Button** in the **Action Bar** (not shown), will perform the chosen action for the selected item(s).


.. caution:: Please be take care when using the delete function which will remove the selected trials. Backup your data regularly to prevent any loss as delete is final.

.. raw:: latex
  
      \newpage


.. rst-class:: activity


.. raw:: latex
  
      \newpage

.. rst-class:: activity

What Data Transfer Method is Best?
""""""""""""""""""""""""""""""""""

This is dependent upon several factors influenced by your organisation's implementation of  KDDart platform components either fully, partially or not at all. For example, if KDSmart is being used 'standalone' without any other KDDart software, CSV files are required to load your data.

The following table outlines 

.. tabularcolumns:: |\Y{0.3}|\Y{0.7}|

.. list-table:: 
   :widths: 25 50
   :class: longtable
   :header-rows: 1
   :stub-columns: 0

   * - **Best When ...**
     - **Description**
   * - **KDSmart is to be used on its own**
     - Using KDSmart *standalone*, without any other KDDart software, means CSV files must be used to import and export all your trial, traits and tag data.
       
       Also useful if you want to try KDSmart with some of your trial data just to see how it works in the field.
   * - **Several KDSmart devices used to score the same trial and KDXplore is being used**
     - Using KDXplore with KDSmart when a direct connection can be established for data transfer, or if a connection is not possible either CSV or KDX files can be used.
   * - **Your Trials are stored in KDDart's data layer and a direct connection is available** 
     - This functionality is returning to KDSmart to directly connect with the KDDart database layer for trial selection and download or upload.



.. raw:: latex
  
      \newpage

.. rst-class:: activity

Symbols and Buttons
"""""""""""""""""""

The button symbols used in KDSmart are shown in the following table:


.. tabularcolumns:: |\Y{0.2}|\Y{0.2}|\Y{0.6}|

.. list-table::  
   :widths: 20 20 60
   :class: longtable
   :header-rows: 1

   * - **Button**
     - **Term**
     - **Description**
   * - |kds_trials|
     - **Trials**
     - Trials or nurseries refer to the experiments or research being conducted. |br| Select *Trials* on the **Home Screen** to display the list of trials that have been loaded into KDSmart. |br| *Demonstration Trials* are preloaded for familiarisation of KDSmart and training.
   * - |kds_tags|
     - **Tags**
     - Manage the tags used in the trials.
   * - |kds_traits|
     - **Traits**
     - Manage the traits used in the trials.
   * - |kds_devices|
     - **Devices**
     - Manage devices (scanners, scales, etc.), Bluetooth, and database.
   * - |kds_settings|
     - **Settings**
     - Manage the device settings and those that apply to all trials.
   * - |kds_info|
     - **Information**
     - Contextual help for KDSmart, information about KDSmart, and licensing.
   * - |run-btn|
     - **Start**
     - Start or Run button.
   * - |kds-DemoRun|
     - **Run (Demo DB)**
     - Start the active trial. A white border indicates the current setting is for a *Demonstration* database trial (*Demo DB*).
   * - |kds-ProdRun|
     - **Run (Production DB)**
     - Start the active trial. A yellow border indicates the current setting is for a *Production* database trial (sometimes referred to as *Prod DB*).
   * - |btn_advance|
     - **Advance**
     - Step forward and advance to the next plot.
   * - |btn_retreat|
     - **Retreat**
     - Step backward and retreat to the previous plot.
   * - |kds_plots|
     - **Plot**
     - Either a plot ID or a column and row pair that uniquely identifies an area (i.e. plot) within a trial. Within a trial, each combination or column/row must be unique.
   * - |organism-types|
     - **Organism Types**
     - Within settings, the type of organism being measured can be specified. This appears in the **Scoring Screen**. |br| Each setting has a different image representation for the organism type.


.. |organism-types| image:: images/kds-organism-types.png
            :scale: 70 %

.. |run-btn| image:: images/ic_action_playback_play.png
            :scale: 70 %

.. |kds-DemoRun| image:: images/kds-DemoRunButton.png
            :scale: 70 %

.. |kds-ProdRun| image:: images/kds-ProdRunButton.png
            :scale: 70 %

.. |kds_tags| image:: images/kds_tags.png
            :scale: 70 %

.. |kds_devices| image:: images/kds-devices.png
            :scale: 70 %

.. |kds_traits| image:: images/kds-traits.png
            :scale: 17 %

.. |kds_settings| image:: images/kds_settings.png
            :scale: 70 %

.. |kds_info| image:: images/kds_info.png
            :scale: 30 %

.. |kds_trials| image:: images/kds_trials.png
            :scale: 30 %

.. |kds_plots| image:: images/kds-plot-512.png
            :scale: 30 %

.. |btn_advance| image:: images/btn_advance_black.png
            :scale: 100 %

.. |btn_retreat| image:: images/btn_retreat_black.png
            :scale: 100 %

.. |KDSnew010| image:: images/KDSbasics/KDSnew010.png
            :scale: 30 %            

.. raw:: latex
  
      \newpage

Troubleshooting
================

.. rst-class:: activity

Block Trial Issues
""""""""""""""""""

The 3.0.28 update has resolved some database issues with block trials. However, some users may find that after updating KDSmart, their block trials do not work anymore. This is due to the trials not being compatible with the new database version. The following instructions outline a quick fix for this issue: 

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Fixing Block Trials
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Navigate to the **Devices Screen**. The image below shows how to get there from the **Home Screen**. Select the **Devices Button** at |circle1|.
     
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/KDSbasics/KDSnew010.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Devices Screen
       
           |center-end|

       .. only:: latex
       
           .. figure:: images/KDSbasics/KDSnew010.png
              :scale: 17 %
              :alt: Devices Screen
              
              Devices Screen  
          
   * - **2.**
     - A **Fix Block Trials Button** has been added and can be seen in the below image at |circle1|.
     
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/KDSbasics/KDSnew011.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Fixing Block Trials
       
           |center-end|

       .. only:: latex
       
           .. figure:: images/KDSbasics/KDSnew011.png
              :scale: 17 %
              :alt: Fixing Block Trials
              
              Fixing Block Trials
              
   * - **3.**
     - A list of block trials will be displayed. Select the trial that you want to fix and it should be converted to be compatible with the newest version of KDSmart.   


.. raw:: latex
  
      \newpage

.. rst-class:: activity

Plot Attribute Alias Issues 
"""""""""""""""""""""""""""

The 3.0.28 update to KDSmart has involved a change in the way that block trials are handled. Some users may experience issues with the plot attribute alias of a block trial if they try to import a block trial to KDSmart 3.0.28 if it was exported from an earlier version of KDSmart.

|br|

If you have this issue, KDSmart will present options for setting the correct plot attribute alias which can be seen in the below image. Choose the field that should match up with the plot attribute alias and the file will be converted for you.  

.. only:: html

    |center-start|

    .. thumbnail:: images/KDSbasics/KDSnew012.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Fixing Plot Attribute Alias

    |center-end|

.. only:: latex

    .. figure:: images/KDSbasics/KDSnew012.png
       :scale: 17 %
       :alt: Fixing Plot Attribute Alias
       
       Fixing Plot Attribute Alias
      
