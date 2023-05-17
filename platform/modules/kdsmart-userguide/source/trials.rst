.. About Traits



.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .orange   {color:orange}   </style>

.. role:: orange

.. raw:: html

    <style> .brown {color:brown} </style>

.. role:: brown





=======
Trials
=======

KDSmart is designed for collecting data for *trials*. Trials can either be `imported <https://www.kddart.org/help/kdsmart/html/data-import-export-backup.html>`_ from external sources, `transferred <https://www.kddart.org/help/kdsmart/html/exchangedata.html>`_ from KDXplore, or `created <https://www.kddart.org/help/kdsmart/html/trials.html#creating-a-trial>`_ within KDSmart.

Trials in KDSmart can be viewed and managed from the **Trials screen**:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Trials/trials2.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Trials Screen

    |center-end|


.. only:: latex

    .. figure:: images/Trials/trials2.png
       :scale: 25 %
       :alt: Trials Screen

       Trials Screen

|br|


This page provides more information on trials, including creating and managing them in KDSmart.

|br|

What is a Trial?
================

*Trial*  is the general term used in KDDart to refer to studies, experiments, nurseries, projects, etc. Trials contain data on the physical layout of a field and trial details and the plots and sub-plots within that field.

Trials also contain `traits <https://www.kddart.org/help/kdsmart/html/traits.html>`_ which are the qualities or characteristics being scored, and possibly `tags <https://www.kddart.org/help/kdsmart/html/tags.html>`_ that are reusable notes.

Generally, a trial is created in KDXplore or KDManage, transferred to KDSmart for scoring in the field, transferred back to KDXplore for data curation, and finally uploaded into KDDart.

|br|

.. tip:: Trials contain multiple *plots* - areas, spaces or even pots, uniquely identified by a plot ID, coordinate pairs (column/row ID), or both. *Subplots* are individual specimens within a plot.


|br|

Trial Types
-----------

There are three types of trials in KDXplore:

* Column and Row (X/Y) - the combination of column and row numbers is a unique identifier for every plot in the trial;
* Plot ID - the plot ID is a unique identifier for every plot; and
* Block - the combination of block, column, and row numbers is a unique identifier for each plot.


|br|

Trial Details
----------------

Each trial contains a set of attributes that define its characteristics. You can find the details for each trial in the **Trial Details screen**:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Trials/trials1.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Trial Details Screen

    |center-end|


.. only:: latex

    .. figure:: images/Trials/trials1.png
       :scale: 25 %
       :alt: Trial Details Screen

       Trial Details Screen

|br|


Trial Management
=================

Trials in KDSmart are managed from the **Trials screen**, shown in the sections above. This screen has options for many trial management activities such as importing, exporting, creating, and editing trials.

|br|

Creating a New Trial
---------------------

New X/Y and Plot ID trials can be created within KDSmart.

|br|

.. only:: html

  |center-start|

  .. thumbnail:: images/Trials/trials3.png
       :width: 40%
       :show_caption: True
       :alt: Creating a New X/Y Trial
       :title: Creating a New X/Y Tria (select to zoom)

  |center-end|

.. only:: latex

    .. figure:: images/Trials/trials3.png
       :scale: 25%
       :alt: Creating a New X/Y Tria

       Creating a New X/Y Tria



|br|

.. only:: html

  |center-start|

  .. thumbnail:: images/Trials/trials4.png
       :width: 40%
       :show_caption: True
       :alt: Creating a New Plot ID Trial
       :title: Creating a New Plot ID Trial (select to zoom)

  |center-end|

.. only:: latex

    .. figure:: images/Trials/trials4.png
       :scale: 25%
       :alt: Creating a New Plot ID Trial

       Creating a New Plot ID Trial

|br|

.. list-table:: Creating a New Trial
   :widths: 1 70
   :header-rows: 1

   * - Step
     - Action
   * - **1.**
     - Navigate to the **Trials screen** and select the **Menu button** to open the **Menu**.
   * - **2.**
     - Select the **Create Trial button** to display the **Create Trial screen**.
   * - **3.**
     - Enter the details for the new trial. Depending on whether you are creating an X/Y or Plot ID trial, there will be different options. See the table below for a complete list of all details.
   * - **4.**
     - Select the **Confirm button** to finalise the creation of the trial.

|br|


.. insert video here

.. note:: Currently, you cannot create new block trials in KDSmart. Instead, you will need to import or transfer them into the app.

|br|


Adding & Removing Traits in a Trial
-----------------------------------

Trials need to have traits added to them for scoring. You can also remove traits from an existing trial.

.. list-table:: Adding Traits to a Trial
   :widths: 1 70
   :header-rows: 1

   * - Step
     - Action
   * - **1.**
     - Select the **Trial Details button** to view the details of a trial.
   * - **2.**
     - Select the **Edit Traits button** to display the **Trait Instances screen**. If there are existing traits, it will list them here. See the `Preparing for Scoring <https://www.kddart.org/help/kdsmart/html/preparation.html#trait-instance>`_ page for information on this screen.
   * - **3.**
     - Select the **Menu button**, and choose traits to add from under the title *Trait Bundles*. They are organised in bundles (if you have any bundles). This allows you to add sets of related traits at once.
   * - **4.**
     - Select the **Confirm button** to add the traits. You will now see the newly added traits in the **Trait Instances screen**.

To remove traits, go to the **Trait Instances screen** and select the **Manage Traits button** to open a menu where you will find the *Remove option*.

.. note:: If you don’t want to score a trait, it is not always necessary to completely remove it from the trial. See the `Preparing for Scoring <https://www.kddart.org/help/kdsmart/html/preparation.html#trait-instance>`_ page for information on how to deselect traits when scoring.

|br|

Editing Trial Details
---------------------

Trial details are displayed in the **Trial Details screen**. You can edit some *details*; however, trial *attributes* that are imported data are not editable. Each editable detail will have an **Edit button** next to it.

|br|

.. only:: html

  |center-start|

  .. thumbnail:: images/Trials/trials5.png
       :width: 40%
       :show_caption: True
       :alt: Trial Details Screen
       :title: Trial Details Screen (select to zoom)

  |center-end|

.. only:: latex

    .. figure:: images/Trials/trials5.png
       :scale: 25%
       :alt: Trial Details Screen

       Trial Details Screen


|br|

Deleting Trials
---------------

*Long-press* on a trial in the **Trials screen** to select it and then select the *Delete option*.


.. still need to create trial bundles section
