.. About Traits



.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .orange   {color:orange}   </style>

.. |assign_tag_btn|  image:: images/ic_action_new_label_black.png
   :scale: 70 %

.. |add_tag_btn|  image:: images/buttons/ic_action_new.png
  :scale: 40 %

.. |edit_btn|  image:: images/buttons/ic_action_edit.png
  :scale: 40 %

.. |menu_btn|  image:: images/buttons/ic_action_overflow_black.png
  :scale: 40 %

.. |delete_btn|  image:: images/buttons/ic_action_discard.png
  :scale: 40 %

.. |tag_btn|  image:: images/kds_tags.png
  :scale: 25 %

.. role:: orange

.. |scoring| raw:: html

   <a href="http://www.kddart.org/help/kdsmart/html/kdsmarthelp.html" target="_blank">Scoring</a>

.. |importexport| raw:: html

  <a href="http://www.kddart.org/help/kdsmart/html/data-import-export-backup.html" target="_blank">Data Import, Export & Backup</a>

.. _Tags: 

=======
Tags
=======


KDSmart scoring includes the use of tags for plots and sub-plots. This section provides more information on tags including how to create and use them.

|br|

What is a Tag?
==============
Tags are short, text descriptions that are used to represent information about a plot or sub-plot (a cell) in a trial e.g. 'BD' which can mean 'bird damage'. They provide a quick method of applying predefined classifications or annotations to plots or sub-plots. They essentially work like reusable notes. such as.

Tags have the following characteristics:

- User definable;
- Consist of a short name and optional long description;
- New tags can be created in the field;
- Can be imported from a CSV file; and
- Are exportable to CSV file.

The main benefits of tags are that they:

- Are simple to use - selectable from a list makes them quick and easy to assign;
- User or project definable;
- Provide consistent annotation, avoiding problems with spelling or language; and
- Deployable across multiple users, devices and locations.

This means that the:

- Users spend less time writing and repeating notes in the field; and
- Data curators have more consistent, uniform recordings from multiple locations by different field workers.


When tags have been assigned to a plot or sub-plot they will appear as shown in the following image, which shows part of the **Scoring Screen** with two tags assigned at |circle1| which is above the trait column.
Tags are assigned or reassigned using the |assign_tag_btn| **Assign Tag Button** at |circle2|.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/tags/tags13.png
        :show_caption: true
        :width: 60%
        :align: center
        :title: Example of Two Applied Tags on the Scoring Screen

    |center-end|


.. only:: latex

    .. figure:: images/tags/tags13.png
       :scale: 40 %
       :alt: Example of Two Applied Tags on the Scoring Screen

       Example of Two Applied Tags on the Scoring Screen

|br|

A few tag examples are shown in the following table:

|center-start|

.. tabularcolumns:: |\Y{0.3}|\Y{0.5}|

.. list-table:: Example Tags
   :class: longtable
   :widths: 25 60
   :header-rows: 1


   * - **Tag (Short Name)**
     - **Long Description**
   * - BD
     - Bird Damage
   * - LDG+
     - General Lodging in plots-mild
   * - LDG++
     - General Lodging in plots-moderate
   * - WET
     - Waterlogging

|center-end|

|br|

Tag Management
==============

Tags are managed from the **Tags Screen** which can be accessed by selecting the |tag_btn| **Tags Button** on the **Home Screen** or through the **Menu**. The following actions can be performed at the **Tags Screen**:

- Add a new tag;
- Edit a tag description;
- Delete selected tag(s) (Note: Assigned/in use Tags cannot be deleted);
- Import tags from a CSV file; and
- Export selected tags to a CSV file.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/tags/tags1.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Tags Screen

    |center-end|


.. only:: latex

    .. figure:: images/tags/tags1.png
       :scale: 20%
       :alt: Tags Screen

       Tags Screen

|br|

|br|

Adding Tags
------------

Tags can either be created in KDSmart or imported. Follow the instructions below to create a new tag.

.. tabularcolumns:: |\Y{0.1}|\Y{0.6}|


.. list-table:: Adding Tags
   :class: longtable
   :widths: 1 70
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Open the **Tags Screen** and select the |add_tag_btn| **Add Tag Button**.
   * - **2.**
     - Enter a *Label* (tag name) such as 'HD' in the image below. Select the *Use* option to check if the name for the tag is free and confirm it.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags2.png
               :show_caption: true
               :width: 15%
               :align: center
               :title: Choosing a Tag Name

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags2.png
              :scale: 20 %
              :alt: Choosing a Tag Name

              Choosing a Tag Name

   * - **3.**
     - A description can be added once the tag name has been confirmed. Enter the description into the text field and then select the **Confirm Button** (the tick) to confirm the name and description of the tag.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags3.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Tag Description

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags3.png
              :scale: 25 %
              :alt: Tag Description

              Tag Description

   * - **4.**
     - A dialogue box will open and you will need to choose to cancel, edit, or confirm your new tag details.

        .. only:: html

            |center-start|

            .. thumbnail:: images/tags/tags4.png
                :show_caption: true
                :width: 40%
                :align: center
                :title: Saving a Tag

            |center-end|


        .. only:: latex

            .. figure:: images/tags/tags4.png
               :scale: 25 %
               :alt: Saving a Tag

               Saving a Tag

|br|

Editing Tags
-------------

Tags can be edited once they have been created. The instructions below outline how to edit a tag.

.. tabularcolumns:: |\Y{0.1}|\Y{0.6}|


.. list-table:: Editing Tags
   :class: longtable
   :widths: 1 70
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Open the **Tags Screen** and select a tag that you would like to edit.
   * - **2.**
     - Select the |edit_btn| **Edit Button** as in the image below. This will present a screen like the **Add Tag Screen**

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags5.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Editing a Tag

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags5.png
              :scale: 25 %
              :alt:  Editing a Tag

              Editing a Tag
   * - **3.**
     - Edit the tag name and/or tag description and select the **Confirm Button**.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags6.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Confirming an Edited Tag

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags6.png
              :scale: 25 %
              :alt:  Confirming an Edited Tag

              Confirming an Edited Tag
   * - **4.**
     - A dialogue box will open and you will need to choose to cancel, edit, or confirm the edited tag details.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags4.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Saving a Tag

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags4.png
              :scale: 25 %
              :alt: Saving a Tag

              Saving a Tag

|br|

Deleting Tags
--------------

Tags can be deleted by either multi-selecting tags and deleting them or just deleting a single tag. Once a tag is deleted it is not possible to undo the action so it is best to keep tags in a CSV file.

.. tabularcolumns:: |\Y{0.1}|\Y{0.6}|


.. list-table:: Deleting Tags
   :class: longtable
   :widths: 1 70
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Select the tags that you want to delete by *long-pressing* it. *Short-pressing* any additional tags will allow you to multi-select multiple tags for deletion.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags9.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Multi-selecting Tags

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags9.png
              :scale: 15 %
              :alt: Multi-selecting Tags

              Multi-selecting Tags
   * - **2.**
     - Select the |menu_btn| **Menu Button** to view additional options.
   * - **3.**
     - Select the *Delete Tags* option from the menu items.
   * - **4.**
     - A message will be displayed that will list any tags that cannot be deleted because they are currently being used in a trial. Select the |delete_btn| **Delete Button** to delete any tags that are not being used in a trial.



|br|

Tag Bundles
===========

Tags can be grouped into bundles to assist with management. Tag bundles can be created in KDSmart and imported/exported from other devices as well. There will always be a bundle that is automatically created called *All Tags* See the instructions below for how to create a new tag bundle in KDSmart.

.. tabularcolumns:: |\Y{0.1}|\Y{0.6}|


.. list-table:: Creating a Tag Bundle and Adding to Tag Bundles
   :class: longtable
   :widths: 1 70
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Select the tags that you want to create a bundle with by *long-pressing* a tag and then *short-pressing* any additional tags. This will allows you to multi-select multiple tags.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags9.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Selecting Tags for a Bundle

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags9.png
              :scale: 15 %
              :alt: Selecting Tags for a Bundle

              Selecting Tags for a Bundle
   * - **2.**
     - Select the |menu_btn| **Menu Button** to view additional options.
   * - **3.**
     - Select the *Add Bundle* option from the menu items. This will take you to the **Add Tag Bundle Screen** which lists the selected tags and bundles that have already been created.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags10.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Add Tag Bundle Screen

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags10.png
              :scale: 25 %
              :alt: Add Tag Bundle Screen

              Add Tag Bundle Screen
   * - **4.**
     - Enter a bundle name and then select the **Create/Add Button** to create a new bundle.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags11.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Creating a New Bundle

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags11.png
              :scale: 25 %
              :alt: Creating a New Bundle

              Creating a New Bundle
   * - **5.**
     - You can also select a current bundle which will display a new **Add Button**. Select that button to add the selected tags to an existing bundle.

        .. only:: html

            |center-start|

            .. thumbnail:: images/tags/tags12.png
                :show_caption: true
                :width: 40%
                :align: center
                :title: Adding Tags to an Existing Bundle

            |center-end|


        .. only:: latex

            .. figure:: images/tags/tags12.png
               :scale: 25 %
               :alt: Adding Tags to an Existing Bundle

               Adding Tags to an Existing Bundle

|br|

Assigning Tags
===============

Along with scoring traits, assigning tags is a part of the scoring process. One or more tags may be assigned to a plot (or sub-plot) or reassigned if required. To assign a tag, follow these steps:

.. tabularcolumns:: |\Y{0.1}|\Y{0.6}|


.. list-table:: Assigning Tags
   :class: longtable
   :widths: 1 70
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Locate a plot or sub-plot to tag in the **Scoring Screen**.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags14.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Tags on the Scoring Screen

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags14.png
              :scale: 20 %
              :alt: Tags on the Scoring Screen

              Tags on the Scoring Screen
   * - **2.**
     - Select the |assign_tag_btn| **Assign Tag Button**.
   * - **3.**
     - Select one or more tags to assign them to a plot.

       .. only:: html

           |center-start|

           .. thumbnail:: images/tags/tags15.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Assigning Tags

           |center-end|


       .. only:: latex

           .. figure:: images/tags/tags15.png
              :scale: 20 %
              :alt: Assigning Tags

              Assigning Tags
   * - **4.**
     - Select the **Confirm Button** (tick) to save changes and return to the **Scoring Screen**. This displays the tag short name above the traits for the selected plot.

Assigning tags is often an integral part of scoring. For more information about scoring see the |scoring| page.

|br|

.. note:: Information on importing and exporting data such as tags can be found in the |importexport| page.
