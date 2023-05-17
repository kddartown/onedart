.. KDSmart V3 Introduction



.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .orange   {color:orange}   </style>

.. |back-btn| image:: images/kds-android-back-1.png
    :scale: 90 %

.. role:: orange



===============================================
Version 3.0 Changes
===============================================




This topic describes the major changes in KDSmart Version 3.0 which reached production status on 28th April 2018.

|br|

What’s New In Release 3.0
==========================

KDSmart Version 3.0 introduces a number of new features aimed to further assist in making scoring in the field easier. We are grateful to all the feedback and suggestions from our users. Some of the following improvements are as a direct response to user suggestions. |br|

This topic provides an overview of some of the main new features, namely:

- A new **Home Screen** - more information at hand;
- The **Spreadsheet View** – underlying functionality is still the same as for trial scoring;
- Addition of trait instances - easy to add or remove trait instances to a trial;
- New trait and tag bundles - for easier management; and
- Progress tracking for all trials - (samples scored / total number of samples).



.. |image0| image:: images/ic_action_play_black.png
            :scale: 60 %


.. |image1| image:: images/kds-v3-main-portait.png
            :scale: 65 %


|br|

The Home Screen
===============

The Main or Home window has undergone changes to include more trial information for the selected trial without a need to first visit the trials window.

Features of the updated **Home Screen** include:

* Scroll through the trials in KDSmart by swiping left or right in the **Home Screen**. 
* Page indicator bars, above the trial name, indicate current position in the list of trials and whether scrolling left or right will reveal more trial.
* Restarting KDSmart or returning to the main window will display the name of the last *Trial* displayed (possibly the last being scored).
* The |image0| **Start Scoring Button** now has dual functions:
   
   Long Press
      * Displays the **Scoring Configuration Screen**.
   Single Tap
      * Recommence interrupted scoring for a trial; or 
      * Displays the **Scoring Configuration Screen** if the trial is yet to be scored.
      
* For the displayed trial, using the top |image0| **Start Scoring Button** button recommences scoring from the last plot or position where the scoring stopped.
* The **Trial Progress Bar** provides a quick visual guide for the displayed trial.
* The new **Trial Details Button** is a fast path to the details of the displayed trial. 
* When screen space is limited (e.g. with a phone) the **Lower Menu Bar** now has left/right scrolling to reveal any additional function buttons.

     |br|
     
     .. only:: html
     
         |center-start|
     
         .. thumbnail:: images/kds-v3-main-portait.png
             :show_caption: true
             :width: 40%
             :align: center
             :title: New Home Screen (Select to zoom)
     
         |center-end|
     
     
     .. only:: latex
     
         .. figure:: images/kds-v3-main-portait.png
                  :scale: 40%
                  :alt: New Home Screen
                  
                  New Home Screen
     
     |br|



.. raw:: latex
  
      \newpage

The Spreadsheet View
=====================

**Spreadsheet View** is a new option in Version 3.0 for scoring providing a 'spreadsheet style' view of a trial. Some scoring situations will benefit from this alternative to the original and default **Path View**. It is easy to alternate between the two as views as your needs dictate in the field.

The following illustration shows the **Spreadsheet View Scoring Screen** (no scored traits visible):


    |br|
    
    .. only:: html
    
        |center-start|
    
        .. thumbnail:: images/kds-v3-ssview-unscored-portait.png
            :show_caption: true
            :width: 40%
            :align: center
            :title: The Spreadsheet View Menu (Select to zoom)
    
        |center-end|
    
    
    .. only:: latex
    
        .. figure:: images/kds-v3-ssview-unscored-portait.png
                 :scale: 40%
                 :alt: The Spreadsheet View Menu
                 
                 The Spreadsheet View Menu
    
    |br|


.. Note:: When first selecting **Spreadsheet View**, the first column is partially collapsed, designed to accommodate small phone screens. It can easily be adjusted by:

          #. Selecting the |image2| **Menu Button** at top right.
          #. Select **Adjust First Column Width Checkbox** to display a sizing slider at the bottom of the screen.
          #. Adjust the width as required then switch off the resizer by deselecting the **Adjust First Column Width Checkbox**.


|br|

How to Select Spreadsheet View
-------------------------------

**Spreadsheet View** can be selected in the **Scoring Configuration Screen** for a trial as illustrated next. 

     |br|
     
     .. only:: html
     
         |center-start|
     
         .. thumbnail:: images/kds-config-optn-2.png
             :show_caption: true
             :width: 40%
             :align: center
             :title: Scoring View Selection (Select to zoom)
     
         |center-end|
     
     
     .. only:: latex
     
         .. figure:: images/kds-config-optn-2.png
                  :scale: 50%
                  :alt: Scoring View Selection
                  
                  Scoring View Selection
     
     |br|

The default view can also be chosen in the **Settings Menu**.

|br|

Spreadsheet View Window Elements
---------------------------------


.. |goto-btn| image:: images/goto_location_black.png
            :scale: 55 %

.. |a-pc-btn| image:: images/ic_object_alive_plot_collapsed.png
            :scale: 35 %


.. |a-npc-btn| image:: images/ic_object_alive_plot_not_collapsed.png
            :scale: 35 %




The following image shows a cropped and annotated version of the previous example **Spreadsheet View**. |br| A description of the window elements is provided in the following table.


       |br|
       
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/kds-v3-ssview-unscored-portait-annot.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Annotated Spreadsheet View (Select to zoom)
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/kds-v3-ssview-unscored-portait-annot.png
                    :scale: 40%
                    :alt: Annotated Spreadsheet View
                    
                    Annotated Spreadsheet View
       
       |br|

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table:: Annotations for the illustration above
   :widths: 1 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 1

   * - **Item**
     - **Description**
   * - 1.
     - Select the |goto-btn| **Location Button** to return to the last scored sample.
   * - 2.
     - **Active Trait Columns**, scrollable left to right. |br| **Note:** Traits that are inactive for the scoring session are not displayed.
   * - 3.
     - The **Plot Column** i.e. plot ID/ column, row. |br| Also shows indicators for tags, notes, photos and menu selector.
   * - 4.
     - Symbolises the plot. Downward pointing |a-npc-btn| indicates the plot is expanded displaying the contained sub-plots. Sideways pointing |a-pc-btn| indicates the sub-plots for the plot are hidden from view.
   * - 5.
     - A sub-plot belonging to the plot above.
   * - 6.
     - The dash **'-'** symbolises an un-scored trait. Touch the cell to score the trait for this plot.
   * - 7.
     - The dot **'.'** symbolises a value cannot be entered e.g. this is a plot level trait. In this example, it is a plot level trait and it is at the sub-plot row, hence not scorable.
   * - 8.
     - The green arrow indicates plots are vertically scrollable.
   * - 9.
     - The yellow arrow indicates the traits are horizontally scrollable.
   * - 10.
     - Blue arrow indicates this area can be expanded or contracted by selecting  **Adjust First Column Width Checkbox**  from the **Settings Menu** (at circle 11) then using the resizing bar.
   * - 11.
     - The **Settings Menu**. There are significantly different menu items in **Spreadsheet View** compared to **Path View**. See the  `Settings Menu`_ topic below.




To enter or replace a score for a sub-plot touch the required row and column position for the trait. The displayed dialogue is dependent upon the trait’s data type e.g. the following example is for a date data type.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-v3-date-trait-selection.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Date Data Type Trait Entry (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-v3-date-trait-selection.png
             :scale: 40%
             :alt: Annotated Spreadsheet View
             
             Date Data Type Trait Entry

|br|



.. note:: If the *Lock Scored Traits* option is enabled, subsequent attempts to edit the existing value will display a warning with an option to continue or stop to prevent accidental changes as illustrated next.

  |br|
  
  .. only:: html
  
      |center-start|
  
      .. thumbnail:: images/kds-trait-value-already-set.png
          :show_caption: true
          :width: 40%
          :align: center
          :title: Trait Already Set (Select to zoom)
  
      |center-end|
  
  
  .. only:: latex
  
      .. figure:: images/kds-trait-value-already-set.png
               :scale: 60%
               :alt: Trait Already Set
               
               Trait Already Set
  
  |br|


.. Note:: Entry of Trait values is the same for both Spreadsheet and Path views.

|br|


Trait Levels
============

Previously, trait levels could only be specified as either plot or sub-plot. |br|
With KSDSmart version 3.0.3, trait level can be set to:

   Plot Level
       by using *plot* or *trial unit*; or 
   Sub-Plot Level 
       by using *sub-plot*, *individual* or *plant*.


Trait Instances
================


.. |addto| image:: images/ic_action_add_to_queue_black.png
            :scale: 40 %

.. |edit| image:: images/ic_action_edit_black.png
            :scale: 40 %


Trait instances can be added to a trial when viewing the traits for a trial.
In the following example the |addto| **Add Trait Instance Button** has been selected to reveal the highlighted menu.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-trait-istance-1.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Trait Instance Menu (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-trait-istance-1.png
             :scale: 40%
             :alt: Trait Instance Menu
             
             Trait Instance Menu

|br|

The menu options for trait instances, as appearing in the above illustration, are:

.. tabularcolumns:: |\Y{0.2}|\Y{0.8}|

.. list-table:: Menu options for trait instances
   :widths: 5 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 1

   * - **Item**
     - **Description**
   * - Add Instance
     - A new instance can be added to a trait which is associated with the trial. |br| Trait instances appear with naming of #1, #2, #3, etc.
   * - Move Up/Down
     - A trait, always with its instances, can be moved up or down relative to other traits. |br| By default, the traits appear in alphabetic order.
   * - Edit Description
     - The description of the trait instance can be edited. |br| The |edit| **Edit Button** appears next to a trait instance to perform this.
   * - Remove Trait
     - A trait or a trait instance can be removed from a trial only if it is *not scored*. |br| Use the |edit| **Edit Button** adjacent to the trait instance to remove the trait.

.. Note:: In a situation of multiple trait instances, e.g. #1, #2 and #3, the removal of #1 from a trial will leave instances #2 and #3. If an instance is added it will be instance #4 (i.e. #1 is not replaced). However, in this example, if #3 is removed then an instance is added, it will be #3. An instance cannot be removed if it contains any scored values.

|br|

.. raw:: latex
  
      \newpage

Displaying Trait Attributes
============================

Selecting the trait name at the top of the trait column displays the trait's attributes.  
These include trait:

* Alias;
* Description;
* Datatype;
* Validation rule;
* Units; and
* Level.

The following illustration from **Spreadsheet View** shows the trait DFF_PLOT (at '1') was touched to display the highlighted information: 

            
  |br|
  
  .. only:: html
  
      |center-start|
  
      .. thumbnail:: images/kds-trait-detail-display.png
          :show_caption: true
          :width: 40%
          :align: center
          :title: Trait Attributes Display (Select to zoom)
  
      |center-end|
  
  
  .. only:: latex
  
      .. figure:: images/kds-trait-detail-display.png
               :scale: 40%
               :alt: Trait Attributes Display
               
               Trait Attributes Display
  
  |br|

.. raw:: latex
  
      \newpage

Additional Plot or Sub-Plot Attributes and Actions
===================================================

A *short press* on the plot or sub-plot identifier/coordinate displays the plot or sub-plot attributes.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-plot-attributes.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Plot Attributes Display (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-plot-attributes.png
             :scale: 60%
             :alt: Plot Attributes Display
             
             Plot Attributes Display

|br|

A *long press* on the plot or sub-plot identifier/coordinate displays further attributes and functions. These are: 

- Deactivate or activate the plot/sub-plot;
- View, add or remove tags;
- Add a note (typed entry) for the plot/sub-plot;
- Add photos; 
- Add an audio note; and
- Add a sub-plot to the plot.

The following example shows the sub-plot has two tags assigned, *GV+++* and *MD* and no images are attached, as the **Attachment Icon** is disabled.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-plot-attributes-long-press.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Long Press (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-plot-attributes-long-press.png
             :scale: 60%
             :alt: Long Press
             
             Long Press

|br|

With attributes displayed as in the above example, a short press of either the plot/sub-plot icon or identifier/coordinate will display the menu which is both illustrated below. 


.. tabularcolumns:: |\Y{0.5}|\Y{0.5}|

.. list-table:: 
   :widths: 50 50
   :class: longtable
   :header-rows: 0
   :stub-columns: 0

   * - **Plot Menu**
     - **Sub-Plot Menu**
   * - .. thumbnail:: images/kds-plot-menu.png
                   :width: 80%
                   :show_caption: True
                   :title: 
     - .. thumbnail:: images/kds-specimen-menu.png
                   :width: 80%
                   :show_caption: True
                   :title: 



.. raw:: latex
  
      \newpage


Settings Menu
=============

.. |image2| image:: images/ic_action_overflow_black.png
            :scale: 80 %


Selecting the top right |image2| **Settings Menu Button** in **Spreadsheet View** displays a menu as illustrated. The menu items are different from those in **Path View**  See the following table for a brief description of these menu options:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-spreadsheetview-menu.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: The Spreadsheet View (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-spreadsheetview-menu.png
             :scale: 40%
             :alt: The Spreadsheet View
             
             The Spreadsheet View

|br|

.. tabularcolumns:: |\Y{0.2}|\Y{0.6}|

.. list-table::  
   :widths: 20 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 0
   :Align: Left

   * - **Item**
     - **Description**
   * - **Text Size**
     - Adjust the text size of the sample values.
   * - **Adjust First Column Width**
     - Displays a slider at the bottom of the screen allowing adjustment of the first column width which is helpful for small phone screens with limited space.
   * - **Location**
     - Enable or disable location services.
   * - **Scanner On**
     - Displays the **Paired Devices Screen** to allow connecting or reconnecting to a scanner.
   * - **Configure**
     - Configure the information to appear in the plot attributes.
   * - **Elapsed Days Count**
     - Checkbox to change the display of elapsed days from a date to the number of days since the trial planting date.
   * - **Unlock Scored Traits**
     - Unlocks scored traits, enabling modification without warning step.
   * - **Change Screen Orientation**
     - Change the screen orientation, e.g. change from landscape to portrait.
       A three-second delay allows the tablet to be turned to the desired orientation before the rotation lock is reactivated.
   * - **Choose Plot Colours**
     - Three colours are available for plots and traits and more can be added on request.
   * - **Show/Hide Sub-Plots**
     - Hides or shows all the sub-plots, useful for scoring only plot traits.
   * - **Fixed Plot Info**
     - Enables selection for column display of inactive traits and plot attributes.
   * - **Help**
     - Displays the inbuilt KDSmart help.


.. raw:: latex
  
      \newpage

Trait and Tag Bundles
======================

Bundles are a mechanism for sorting either traits or tags into logical, usable groups. This may assist with their use and management, e.g. it may be helpful to bundle traits for a type of crop, season or a specific experiment. 
They can also assist with distribution to multiple KDSmart devices for efficiency and to ensure consistency.

Some features of bundles are:

- A trait or tag can exist in multiple bundles;
- Every trait or tag is a member of the *All Traits* or *All Tags* bundles;
- Bundles make the selection of traits or tags easier for export or import;
- Traits or tags can be added or removed from bundles (except *All Traits* or *All Tags*); 
- It is easy to select multiple traits/tags and create a new bundle; and
- Bundles can be deleted, except for the *All Trait* and *All Tag* bundles.

The example below shows a trait bundle named *Dates Bundle* expanded to show the contents. Note the circled number, at the right of the bundle name, indicating it contains ten traits. When expanded the traits in the bundle appear below the bundle name (dotted highlight).

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/kds-trait-bundle.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: The Spreadsheet View (Select to zoom)

    |center-end|


.. only:: latex

    .. figure:: images/kds-trait-bundle.png
             :scale: 40%
             :alt: Trait Bundle
             
             Trait Bundle

|br|

Remember bundles are logical groupings, so there is only ever one instance of a trait defined in KDSmart.

.. Note:: for Bundles, Tags work in the same manner as Traits.


.. raw:: latex
  
      \newpage

Creating Bundles 
-----------------

Viewing traits or tags the procedure is the same. Traits are used here to illustrate.

To create a bundle, at least one trait or tag needs to be selected to invoke the menu, however, a bundle can exist without traits/tags.


A long press on a trait will reveal a different set of actions

.. tabularcolumns:: |\Y{0.5}|\Y{0.5}|

.. list-table:: Example of Trait Menu Bar on different sized devices
   :widths: 40 40
   :class: longtable
   :header-rows: 1
   :stub-columns: 0
   :Align: Center

   * - **Tablet**
     - **Phone**
   * - .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/kds-trait-bundle-menu-tablet.png
               :show_caption: true
               :width: 80%
               :align: center
               :title: Tablet Example (select to zoom image)
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/kds-trait-bundle-menu-tablet.png
              :scale: 40 %
              :alt: Tablet Example
              
              Tablet Example
     - .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/kds-trait-bundle-menu-phone.png
               :show_caption: true
               :width: 80%
               :align: center
               :title: Phone Example (select to zoom image)
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/kds-trait-bundle-menu-phone.png
              :scale: 40 %
              :alt: Phone Example
              
              Phone Example



.. |tag_b-btn| image:: images/tag_bundle_icon.png
            :scale: 55 %


.. |trait_b-btn| image:: images/trait_bundle_icon.png
            :scale: 25 %




.. tabularcolumns:: |\Y{0.1}|\Y{0.8}|

.. list-table::  Steps to Create, Add to or Delete from a Bundle
   :widths: 1 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 0
   :Align: Left

   * - **Step**
     - **Action**
   * - 1.
     - In the **Trait/Tag Screen**, *long press* a trait/tag to be added to the bundle.
   * - 2.
     - The top bar of the display will change to be similar to the previous trait window examples for phone and tablet. This also indicates the number of traits/tags selected. |br| More traits/tags can be selected or deselected with a single press.
   * - 3.
     - Select either the |image2| **Setting Menu Button**, the |trait_b-btn| **Trait Bundle Button**, or |tag_b-btn|  **Tag Bundle Button**.
       
   * - 4.
     - Enter a unique bundle name. The display will assist in providing a unique name.
   * - 5.
     - Select the **Create/Add Button** to create the new bundle or if delete has been selected confirm by selecting the **Delete Button**. 
     

.. note:: Deleting a Bundle does *not* delete the Traits.



.. raw:: latex
  
      \newpage

Export Bundles 
---------------

Bundles can be exported as either a CSV file or to KDXplore which will require a connection.

.. |upload_btn|  image:: images/ic_action_upload_black.png
            :scale: 55 %

.. tabularcolumns:: |\Y{0.1}|\Y{0.8}|

.. list-table::  Steps to Export a Bundle
   :widths: 1 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 0
   :Align: Left

   * - **Step**
     - **Action**
   * - 1.
     - In the **Trait/Tag Screen**, *long press* the bundle to be exported.
   * - 2.
     - At the top bar of the display select the |upload_btn| **Export Button**.
   * - 3.
     - Select the *Tablet* option to export a CSV file or KDXplore if you have a current connection to the KDXplore application.
   * - 4.
     - Confirm and a message will indicate success and location of the CSV file.


