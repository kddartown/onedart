.. Bluetooth


 
.. include:: imagerefs.txt

.. Following raw and role is required to allow use of brown text

.. raw:: html

    <style> .orange   {color:orange}   </style>


.. role:: orange


.. |bc_scan|  image:: ../../commonimages/cmn-barcode_scannersmall.png
   :scale: 100 %

.. |bc_plot|  image:: ../../commonimages/cmn-barcode_PLot.png
   :scale: 50 %

.. |bc_subplot|  image:: ../../commonimages/cmn-barcode_SubPlot.png
   :scale: 50 %

.. |bc_trait|  image:: ../../commonimages/cmn-barcode_trait.png
   :scale: 50 %

.. |bc_trait_brown|  image:: ../../commonimages/cmn-trait_brown_bc.png
   :scale: 50 %

.. |bc_trait_7|  image:: ../../commonimages/cmn-trait_vlaue7_bc.png
   :scale: 30 %

.. |tick_btn|  image:: images/ic_action_accept.png
   :scale: 30 %

.. |back-btn| image:: images/kds-android-back-1.png
           :scale: 90 %

.. |blue-bars| image:: images/ic_action_drawer_bright_blue.png
           :scale: 20 %

.. |back-btn2| image:: images/android-Back-50.png
           :scale: 40 %

.. |back-btn3| image:: images/kds-android-return-48.png
           :scale: 40 %

.. |back-area| image:: images/kds-back-area.png
           :scale: 70 %

.. |rotate-btn| image:: images/kds-rotate-btn.png
           :scale: 80 %

.. |accept-btn2| image:: images/ic_action_accept_black.png
           :scale: 90 %


.. |cancel-btn2| image:: images/ic_action_cancel_black.png
           :scale: 90 %


.. |plus_sign| image:: images/plus_sign.png
           :scale: 90 %

.. |equals_sign| image:: images/equals_sign.png
           :scale: 90 %

.. |A_settings| image:: images/settings-icn.png
           :scale: 40 %

============================
Bluetooth Scanning
============================



.. important:: It is advisable before taking KDSmart and a Bluetooth scanner or scales to the field to test:

     #. The scanner is configured correctly;  |br|
     #. The tablet/phone with KDSmart can operate successfully with it; and  |br|
     #. Your barcodes work as expected.

Barcode scanning in KDSmart can assist with quick, easy and accurate scoring. Barcode scanning can be used for plot or sub-plot location labels and for traits.

This page contains information for enabling Bluetooth scanner devices in Android, making it available for KDSmart. An introduction to scoring using barcodes with a Bluetooth barcode scanner is also provided.


KDSmart is designed to take advantage of a Bluetooth scanner when:

- Bluetooth is available on the tablet or phone; and
- The tablet/phone can successfully connect with the Bluetooth device; and
- Trial(s) or traits have been prepared for barcode use **before importing** into KDSmart.

Barcode values must be present in the trial before it is imported into KDSmart from KDXplore or CSV file. KDXplore can generate barcodes for the trial and traits. For trials with KDXplore generated barcodes, the option *Use KDXplore Barcodes* found in KDSmart settings needs to be enabled.

Non KDXplore barcodes can be used with a trial.
These need to be:

- Included with a Trial CSV file for plot/sub-plots;
- Must be unique - A *not unique* error for plot barcodes would result upon import;
- Trait import CSV file with barcodes would need to be imported first; and
- The option *Use KDXplore Barcodes* in KDSmart Settings needs to be disabled.



The following sections describe how to connect a Bluetooth device, provide information about the barcode types, examples of how to score and some tips.

|br|

Connecting the Tablet/Phone
===========================



.. |location_link| raw:: html

   <a href="https://serialio.com/scanner-data-transfer-methods" target="_blank">https://serialio.com/scanner-data-transfer-methods</a>

.. note:: Bluetooth scanners generally have two modes: HID and SPP. |br| (More details on this page: |location_link| ) |br| Your scanner **must** be set to **SPP mode before connecting** it with KDSmart. |br| Instructions should be available in your Scanner's Manual.



Before connecting to and using a Bluetooth device, the tablet/phone with KDSmart installed, must first be introduced to the device, referred to as *pairing*.
Sometimes the device may have a pin number associated to enable pairing to occur.

The first connection and subsequent connections will require the devices to be *paired*.  Pairing may need to repeated when disconnection occurs which can be:

- After a period of time has elapsed;
- After devices 'go to sleep' (they enter sleep mode to extend their battery life);
- If the device is too far apart from the tablet/phone;
- Signal is interrupted due to obstacles (e.g. walls, etc.); or
- A combination of all of the above.

The following instructions show how to enable Bluetooth on the tablet/phone and pair with a scanner.

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table::  Steps to Enabling Bluetooth on the Tablet/Phone
   :widths: 2 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - 1.
     - On the Android tablet/phone go to Android **Settings** |A_settings| then Select **Bluetooth**.

       .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart_android_settings.png
               :show_caption: true
               :width: 50%
               :align: center
               :title: Android Settings (select to zoom image)

           |center-end|

       .. only:: latex

           .. figure:: images/kdsmart_android_settings.png
              :scale: 17 %
              :alt: Android Settings

              Android Settings

       **Note:** The version in this image was Android MarshMallow v 6.0.1, which may have a different appearance to the settings in your Android version.
   * - 2.
     - If not already powered on:
          a. **Turn on Bluetooth** on the tablet/phone;
          b. Ensure the scanner/scales to be connected is also switched on and in accordance with the device instructions is *discoverable* (it may need switching off and on again if it is not detected).
          c. When the tablet/phone successfully *discovers* the Bluetooth device, it should appear in the list of **Available Devices** on the tablet/phone.
          d. Once it has appeared it is ready for pairing. If not repeat the process.
   * - 3.
     - Select the required device in the list of **Available Devices** and enter the pin number of the device if requested to complete the pairing. |br| |br| Once successfully paired, the device will appear in the list of **Paired Devices** as illustrated: |br|

       .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart_scanner_select.png
               :show_caption: true
               :width: 50%
               :align: center
               :title: Paired Devices (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kdsmart_scanner_select.png
              :scale: 30 %
              :alt: Paired Devices

              Paired Devices

   * - 4.
     - With the device paired and connected, it is ready for use by any Android applications, such as KDSmart. |br| |br| As noted previously, the distance or proximity required to successfully maintain a Bluetooth connection between the device and the KDSmart tablet can and will vary. If disconnection occurs, reconnecting could be necessary.


|br|

KDSmart - Scanner On
=====================

Once the Android tablet/phone has been connected KDSmart can be connected to the scanner as outlined in the following steps.

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table::  Steps to Set Scanner On In KDSmart
   :widths: 2 70
   :class: longtable
   :header-rows: 1
   :stub-columns: 0

   * - **Step**
     - **Action**
   * - 1.
     - Return to **Path View** for the trial in KDSmart to be scored and from the top right menu (highlighted in the example) select **Scanner On**. This will display the paired devices.

       .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart_scanneron_menu.png
               :show_caption: true
               :width: 50%
               :align: center
               :title: Scanner On (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kdsmart_scanneron_menu.png
              :scale: 20 %
              :alt: Scanner On

              Scanner On

   * - 2.
     - From the list of available Bluetooth paired devices select the scanner device to connect

       .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart_scanner_select.png
               :show_caption: true
               :width: 50%
               :align: center
               :title: Paired Device Selection (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kdsmart_scanner_select.png
              :scale: 30 %
              :alt: Paired Device Selection

              Paired Device Selection

   * - 3.
     - Select the confirmation |tick_btn| **Tick Button**.
   * - 4.
     - Scoring now may commence using the barcode scanner.


.. Tip:: To verify the scanner is working correctly use some prepared trait barcodes, if they are available. Try the following:

     #. Within Path View for your trial select **Scanner On**  from the menu
     #. Go to **Manage Traits** and select the required trait;
     #. Select the **Test Validation Button**;
     #. Try entering values using the scanner. They should appear as if manually entered.


|br|

Using Barcodes in KDSmart
==========================

.. Note:: *Current Plot* refers to the specific location (i.e. plot, sub-plot, etc.) selected and displayed in KDSmart **Path View** ready for scoring.

KDSmart can use barcode input to assist with streamlining scoring. |br| Barcodes can be used for the following:

- Location barcodes - used to position and display the current plot for the trial associated with the scanned barcode location for the:
   - Plot; or
   - Sub Plot;
- Trait barcodes - used for the current plot to set either the:
   - Trait with value; or
   - A value for the selected trait.

This different functionality/behaviour is outlined in the following table (**Note:** The barcodes displayed and human readable text are for illustration only):


.. tabularcolumns:: |\Y{0.1}|\Y{0.2}|\Y{0.3}|\Y{0.4}|


.. list-table::  Barcode Types in KDSmart/KDXplore
   :widths: 2 3 30 60
   :class: longtable
   :header-rows: 1
   :stub-columns: 2

   * - **Prefix**
     - **Barcode Type**
     - **Example**
     - **Result When Scanned...**
   * - PL/
     - Plot
     - |bc_plot|
     - KDsmart will position the scoring window to the *plot* at the barcode location.
   * - SP/
     - Sub Plot
     - |bc_subplot|
     - KDsmart will position the scoring window to the *sub plot* at the barcode location.
   * - TR/
     - Trait Name
     - |bc_trait|
     - For the current plot KDSmart:
         - Selects the trait (*SEM* in the example) ready for a value to be entered.
         - A value may be manually entered or in some cases entered using a barcoded value (see value below).
   * - TR/
     - Trait Name: Value
     - |bc_trait_brown|
     - For the current plot KDSmart:
         1. Selects the specified trait (*GC_1* in the example); and
         2. Sets the value to the barcode value (brown).

       These are possible for traits with a categorical data type or those with a specific and possibly short range. (See below `Example - Trait and Value Barcodes`_).
   * -
     - Value
     - |bc_trait_7|
     - For the current plot and selected trait *waiting for a value to be entered*, KDSmart will enter the value of the barcode(s).
       In this example the value ‘7’ would be entered as if entering the digit ‘7’ from the keyboard. |br| |br|
       **Note:** When using value barcodes an *end-input* barcode maybe required to signify the end of input (See illustration in `Example - Trait and Value Barcodes`_ ).

|br|




Example - Categorical Trait Barcodes
-------------------------------------

The following example shows a categorical trait barcode for the trait instance *GC_1*.

.. tabularcolumns:: |\Y{0.5}|\Y{0.4}|

.. list-table::
   :widths: 40 30
   :class: longtable
   :header-rows: 0
   :stub-columns: 1

   * - .. only:: html

           |center-start|

           .. thumbnail:: images/kds_barcode_ex_Categorical.png
               :show_caption: true
               :width: 60%
               :align: center
               :title: Example Trait Barcodes - Categorical (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kds_barcode_ex_Categorical.png
              :scale: 20 %
              :alt: Example Trait Barcodes - Categorical

              Example Trait Barcodes - Categorical

     - When KDXplore creates the barcodes for the categorical trait a barcode will be created for each possible value. This example shows there are 12 valid values for the *Grain Colour* trait.



|br|

Example - Trait and Value Barcodes
-----------------------------------

The following example shows a trait barcode for the trait *SEM*.


.. tabularcolumns:: |\Y{0.5}|\Y{0.4}|

.. list-table::
   :widths: 40 30
   :class: longtable
   :header-rows: 0
   :stub-columns: 1

   * - .. only:: html

           |center-start|

           .. thumbnail:: images/barcode_example_kdsmart.png
               :show_caption: true
               :width: 60%
               :align: center
               :title: Example Trait Barcodes (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/barcode_example_kdsmart.png
              :scale: 20 %
              :alt: Example Trait Barcodes

              Example Trait Barcodes

     - In this example: |br|

       #. The trait barcode is scanned first, which selects the trait *SEM* for the current plot, ready for input. |br|
       #. Values can be scanned; then |br|
       #. End-input signifies no further values should be entered.



|br|

Using a Scanner – Examples
===========================

In KDSmart trials containing barcodes can utilise scoring using a barcode scanner. To facilitate barcode scoring in KDSmart preparation is required, such as generating barcodes in KDXplore.

For a description of barcode types that can be used in KDSmart, refer to the table *Barcode Types in KDSmart/KDXplore* in the previous topic `Using Barcodes in KDSmart`_.

The following scenarios illustrate barcode assisted scoring.

|br|

Navigating To A Specific Plot Or Sub-Plot
------------------------------------------

Scanning a plot barcode (prefixed PL/), or sub-plot barcode (prefixed SP/), will directly reference or display the location in KDSmart (i.e. the current plot).

For example if a barcode was located at the plot, it could be scanned and KDSmart will position the current plot at this location for the record to be viewed, trait(s) scored, tagged, etc.

The following table outlines the steps required:

.. tabularcolumns:: |\Y{0.1}|\Y{0.5}|\Y{0.4}|

.. list-table::  Navigating by Scanning a Plot or Sub-Plot Barcode
   :widths: 1 20 30
   :class: longtable
   :header-rows: 1
   :stub-columns: 2

   * - **Step**
     - **Action**
     - **Description**
   * - 1.
     - |bc_scan|
     - A scanner, connected and ready, with the trial open in KDSmart in **Path View**.
   * - 2.
     - |plus_sign|
     - Then
   * - 3.
     - |bc_plot|  |br| or |br|  |bc_subplot|
     - Scan either the plot or sub-plot barcode for the required plot/sub-plot
   * - 4.
     - |equals_sign|
     - Which results in:
   * - 5.
     - .. only:: html

           |center-start|

           .. thumbnail:: images/kds_ex_loc1.png
               :show_caption: true
               :width: 60%
               :align: center
               :title: Example Trait Barcodes (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kds_ex_loc1.png
              :scale: 40 %
              :alt: Example Trait Barcodes

              Example Trait Barcodes

     - The current plot in KDSmart is positioned at the matching plot or sub-plot record ready for scoring or viewing.


|br|

Scanning a Trait Barcode with Value – Categorical Data Type
------------------------------------------------------------

For the currently displayed plot location, scanning a trait barcode with value (prefixed TR/) will set the value of the trait to the value represented by the barcode.

The example shown next will set the Trait *GC_1* to *Brown* at the current location (i.e. plot 1):

.. tabularcolumns:: |\Y{0.1}|\Y{0.5}|\Y{0.4}|

.. list-table::  Scanning Trait Values - Categorical
   :widths: 1 20 30
   :class: longtable
   :header-rows: 1
   :stub-columns: 2

   * - **Step**
     - **Action**
     - **Description**
   * - 1.
     - |bc_scan|
     - A scanner, connected and ready, with the trial open in KDSmart, in **Path View**, positioned with the current plot at the required plot/sub-plot. |br| Also have a trait barcode ready to scan. This maybe a printed sheet of trait barcodes (see example above `Example - Categorical Trait Barcodes`_ ).
   * - 2.
     - |plus_sign|
     - Then
   * - 3.
     - .. only:: html

           |center-start|

           .. thumbnail:: ../../commonimages/cmn-trait_brown_bc.png
               :show_caption: true
               :width: 60%
               :align: center
               :title: Example Trait Barcodes (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: ../../commonimages/cmn-trait_brown_bc.png
              :scale: 40 %
              :alt:


     - Scan the trait Name:Value Barcode for the required trait and value. |br| Trait *GC_1* value = *Brown* in the example.
   * - 4.
     - |equals_sign|
     - Which results in:
   * - 5.
     - .. only:: html

           |center-start|

           .. thumbnail:: images/kds_ex_loc1.png
               :show_caption: true
               :width: 60%
               :align: center
               :title:  (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kds_ex_loc1.png
              :scale: 40 %
              :alt:


     - Value now set for the GC_1 Trait instance to Brown..

|br|

Scanning a Trait Name Barcode – Numeric Data Type
--------------------------------------------------

The difference here is a value is not associated with the trait barcode. When the trait scoring window is presented (as if you manually touched the trait for the current plot), it can either be entered either via the numeric key pad or by scanning value barcodes. (see example above `Example - Trait and Value Barcodes`_ )

Depending upon the data type, your barcodes and what value needs to be entered, several barcodes may need to be scanned to perform the data entry.


.. tabularcolumns:: |\Y{0.1}|\Y{0.5}|\Y{0.4}|


.. list-table::  Scanning Trait Values - Numeric Data Type
   :widths: 1 20 30
   :class: longtable
   :header-rows: 1
   :stub-columns: 2

   * - **Step**
     - **Action**
     - **Description**
   * - 1.
     - |bc_scan|
     - A scanner, connected and ready, with the trial open in KDSmart, in **Path View**, positioned at the required plot or sub-plot. |br|  Have the required trait barcodes (see example above `Example - Trait and Value Barcodes`_ ) ready for scanning.
   * - 2.
     - .. only:: html

           |center-start|

           .. thumbnail:: ../../commonimages/cmn-barcode_trait.png
               :show_caption: true
               :width: 60%
               :align: center
               :title:  (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: ../../commonimages/cmn-barcode_trait.png
              :scale: 40 %
              :alt:


     - Scan the trait barcode for the required trait.
   * - 4.
     - .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart-trait_entry.png
               :show_caption: true
               :width: 60%
               :align: center
               :title:  (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kdsmart-trait_entry.png
              :scale: 40 %
              :alt:


     -  The trait numeric entry window will display. |br| Either manually enter the value using the numeric keypad or scan the appropriate value barcodes. |br|
   * - 5.
     - .. only:: html

           |center-start|

           .. thumbnail:: images/kdsmart_bc_numeric_example.png
               :show_caption: true
               :width: 60%
               :align: center
               :title:  (select to zoom image)

           |center-end|


       .. only:: latex

           .. figure:: images/kdsmart_bc_numeric_example.png
              :scale: 40 %
              :alt:


     - If scanning the input, to enter a value of 75
         1. Scan the first digit – 7;
         2. Scan the second digit – 5; Then
         3. Scan the end-input barcode which instructs KDSmart the input is complete.




|br|

Suggestions
============

A few suggestions follow for practical usage and also how trait datatypes and their validation could improve data collection, both manually or with barcodes.

Trait Value Barcodes
------------------------

Using barcodes for traits requires the operator to carry those codes in some manner, possibly in laminated form to the field. In many situations using a barcode will be much quicker to record a trait, however in some instances it maybe slower or less convenient. The suggestions are to inspire some thought as to how best define and manage traits to ensure efficient and accurate data collection.

Traits can be represented with a barcode (TR/ trait barcodes) to streamline data recording. For these one of the most applicable datatypes is canonical. Barcodes for these traits can also be associated with a value, so scanning with a trait value barcode is a single operation.

The simple canonical example described earlier, repeated below, is for a trait grain colour *GC* with values of:  white, purple, red, etc. (12 bar codes).
At the current plot in KDSmart, just scanning one of these barcodes records the specific value for the trait.

.. only:: html

    |center-start|

    .. thumbnail:: images/kds_barcode_ex_Categorical.png
        :show_caption: true
        :width: 60%
        :align: center
        :title: Example Trait Barcodes - Categorical (select to zoom image)

    |center-end|


.. only:: latex

    .. figure:: images/kds_barcode_ex_Categorical.png
       :scale: 17 %
       :alt: Example Trait Barcodes - Categorical

       Example Trait Barcodes - Categorical


|br|

An integer example could be for a trait *Soil_PH* with 14 values would have 14 bar codes: PH1, PH2, PH3, ......, PH14. Scanning one of these barcodes would set that trait to the value scanned for the current plot.

For some situations traits may have too many barcodes to make them worthwhile e.g. an integer trait with a valid range of 50 which would involve carrying a sheet of 50 trait barcodes. Locating and scanning the correct one could be more cumbersome and impractical, so either scanning value barcodes or manual entry could be more convenient. |br|

Alternatively for this scenario, the most frequent trait values could be carried and entered using trait value barcodes and the less frequent values recorded manually.

|br|

Trait Preparation
--------------------------------

When preparing traits consider alternative datatypes. Data collection could be made easier, with or without barcodes as selection of a value from a list can be easier than always needing to enter values.
