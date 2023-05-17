.. This help file was formerly csv-transfer.rst




.. include:: imagerefs.txt

.. Following raw and role is required to allow use of brown text

.. raw:: html

    <style> .brown  {color:brown}  </style>
    <style> .green  {color:green}  </style>
    <style> .orange {color:orange} </style>


.. role:: brown
.. role:: green
.. role:: orange

.. |trial-imp-menu|  image:: images/kds-trial-imp-menu.png
                :scale: 80 %

.. |tt-imp-menu|  image:: images/kds-trait-tag-imp-menu.png
                :scale: 80 %

.. |importtagmsg|  image:: images/kds-importtagmsg.png
                :scale: 80 %

.. |menu_btn|  image:: images/buttons/ic_action_overflow_black.png
  :scale: 40 %

.. |save_btn|  image:: images/buttons/ic_action_save.png
  :scale: 30 %
  
.. |folder_btn|  image:: images/buttons/ic_action_collection.png
   :scale: 30 %
    
.. |import_btn|  image:: images/buttons/ic_action_download.png
  :scale: 40 %


.. _data - import, export, backup:

=============================
Data Import, Export & Backup
=============================
   

KDSmart contains three types of data that can be used in experiments: trials, traits, and tags. KDSmart manages it's own database located on your Android device which contains this data but they can also be imported, exported, and backed up.

Any trial that is imported or exported will also contain any traits or tags that is used in it. However, traits and tags can also be imported or exported in separate files if required. 

To commence using KDSmart with your own trials, that trial data must first be imported into KDSmart.


.. note:: There is a separate *Data Transfer* page at http://www.kddart.org/help/kdsmart/html/exchangedata.html#data-exchange-kdxchange-method which provides examples for transferring data between KDXplore and KDSmart using the Google Drive and KDXchange methods. It is a separate page because it provides instructions on using both KDXplore and KDSmart. The objective of this page is to provide more information on the various options available for KDSmart.  


|br|

.. _csv-transfer - Loading from CSV:

Importing Data  
==============
KDSmart can be used as a standalone application or as a part of the integrated KDDart platform. This means that there is a need for several different methods for importing files and data depending on how KDSmart is used. There are also options for both offline and online imports which can be helpful depending on the user's location and access to the internet. 

Since Android version 4.4, the Storage Access Framework (SAF) has been used for browsing and opening files. This has been implemented in KDSmart and makes it possible to import (and export) files from document providers such as Google Drive or Dropbox, or files that are stored internally on the device. This means that there are many options for importing files whether your device is offline/online and what file hosting services you use.  

If you have exported a *scoring set* from KDXplore, it will be importable as a *trial* in KDSmart. There is only a distinction between the terms in KDXplore. KDSmart views scoring sets and trials as the same thing.  

Depending on whether you are importing trials, traits, or tags, there will be different options available. These will be outlined in the following sections.  


|br|

CSV Import 
""""""""""
Comma Separated Value (CSV) files are a common file format that many users collect data with prior to using KDDart. Some users also use CSV files if they use KDSmart as a standalone application. More information about formatting CSV files can be found on the *CSV Formats* page at http://www.kddart.org/help/kdsmart/html/kdsmart-app-b.html

After selecting a file to import, each column in the CSV must be assigned an attribute type. This determines how the data in the column will be interpreted. Columns can be selected as **Don't Import** as well as whether the data is related to the trial, a plot, or a trait name to be scored. 

TO successfully import a CSV trial, the file must contain at least a Plot ID **OR** both Plot Column and Plot Row **OR** all three columns.

See the steps below on how to import CSV files:

|br|
|center-start|

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/2ohM8Guu7Bs" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

|center-end|    
|br|

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: CSV Import (SAF)
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Open the **Trial Screen**, **Trait Screen**, or **Tag Screen** on KDSmart and select the |import_btn| **Import Button** or the *Import As* option in the |menu_btn| **Menu Options**. 
   * - **2.** 
     - The **Import Options** will open. If you are importing traits or tags, there will be the following options:
     
        - |tt-imp-menu|
        
       Importing from the **Trials Screen** will result in an additional option to import KDX files:
       
        - |trial-imp-menu|
        
   * - **3.** 
     - Choose the **File CSV Button**. This will open the SAF as pictured below:
   * - **4.**
     - Select the CSV file you want to import and then select the **Open Button**. 
   * - **5.**
     - Ensure that all headings are present and the *Import As* options are correct such as plot attributes and traits for plots.
   * - **6.**
     - Select the **Import Button** to finalise the trial import.

.. note:: All types of CSV files (trials, traits, and tags) can be imported into KDSmart. 

|br|

KDX Import 
""""""""""
KDX files contain all experiment information including a trial, traits, and tags. It is similar to a zipped folder and is much easier to transfer than a CSV because there is no import mapping. It is recommended to use KDX files when using KDXplore and KDSmart together as it reduces complexity of importing and the chance of errors. See the instructions below for how to import a KDX file: 

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: KDX Import (SAF) 
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Open the **Trial Screen**, **Trait Screen**, or **Tag Screen** on KDSmart and select the |import_btn| **Import Button** or the *Import As* option in the |menu_btn| **Menu Options**. 
   * - **2.** 
     - The **Import Options** will open. If you are importing traits or tags, there will be the following options:
     
        - |tt-imp-menu|
        
       Importing from the **Trials Screen** will result in an additional option to import KDX files:
       
        - |trial-imp-menu|
        
   * - **3.** 
     - Select the **File KDX Button**. This will open the Storage Access Framework for choosing files on the device internal storage or an application such as Google Drive.
   * - **4.**
     - If the file you need is in the folder that has been opened then select it. If you need to search for the file then select the **SAF Menu Button** at |circle1| (as outlined in the image below):
     
         .. only:: html
         
             |center-start|
         
             .. thumbnail:: images/ImportExportBackup/IEB1.png
                  :width: 40%
                  :show_caption: True
                  :alt: SAF (Select to zoom)
                  :title: SAF (Select to zoom)
         
             |center-end|
         
         .. only:: latex
         
             .. figure:: images/ImportExportBackup/IEB1.png
                :scale: 40 %
                :alt: SAF (Select to zoom)
                
                SAF (Select to zoom) 
                
   * - **5.**
     - The **SAF Menu** will be opened and you will be able to select either folders on the device, or any application that is installed. 
     
         .. only:: html
         
             |center-start|
         
             .. thumbnail:: images/ImportExportBackup/IEB2.png
                  :width: 40%
                  :show_caption: True
                  :alt: SAF Menu (Select to zoom)
                  :title: SAF Menu (Select to zoom)
         
             |center-end|
         
         .. only:: latex
         
             .. figure:: images/ImportExportBackup/IEB2.png
                :scale: 40 %
                :alt: SAF Menu (Select to zoom)
                
                SAF Menu (Select to zoom) 
                
   * - **6.**
     - Select an internal location or application (such as Google Drive or Dropbox) and locate then choose the KDX file that you are importing. Once selected, an **Open Button** will appear at the top of the screen. Select the **Open Button** and the KDX file will be imported with no additional configuration.  

The video referenced below is a part of our KDTutorial series which demonstrates how to import a scoring set (KDSmart views scoring sets as trials) from Google Drive to KDSmart. 

|br|
|center-start|

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/yFKUwK-kMng" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

|center-end|    
|br|

.. note:: KDX files can contain all types of data (trials, traits, and tags) however, you will only be able to find the option to import a KDX file in the **Trial Import Options**.
       
|br|

KDXplore Import (KDXchange) 
"""""""""""""""""""""""""""
The KDXplore option will open KDXchange which is used for transferring data from KDXplore to KDSmart (and vice versa) over a Wi-fi connection when there is no cellular connection available. You will need access to a router or a mobile device that can host a Wi-fi hotspot. 

Connecting to KDXchange requires both KDXplore and KDSmart to be configured. There is a separate *Data Transfer* page at http://www.kddart.org/help/kdsmart/html/exchangedata.html#data-exchange-kdxchange-method  which gives specific instructions for how to use both Google Drive, and KDXchange for transferring data between KDXplore and KDSmart. See that page for more information on using KDXchange.  

|br|

Exporting & Sharing Data 
========================
Exporting and sharing data files in KDSmart are similar but distinct actions that allow users to send trials, traits, and tags to the device internal memory or other applications. These differences will be outlined in the sections below. 

Both of these methods have the same *Export Options* listed below:

  * Full Data for KDXplore;
  * Full Data in Zip; 
  * Only Scores: Plots (CSV); and
  * Only Scores: Plots & Sub-Plots (CSV). 

|br|

Exporting Data
""""""""""""""
*Exporting* allows the user to export a trial, trait, or tag to either the device internal memory (Tablet) or to KDXplore through KDXchange. 

Tablet (Internal Memory)
------------------------
The *Export to Tablet* option will export data to the internal storage of the KDSmart device. 



|br|

.. only:: html
    
    The video and instructions below outline how to export data:
    
    |center-start|
    
    .. raw:: html
        
        <iframe width="560" height="315" src="https://www.youtube.com/embed/WJsHN0tApWo" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        
    |center-end|
    

.. only:: latex
    
    The video available at https://www.youtube.com/embed/WJsHN0tApWo provides a guide and instructions to exporting data:
    

|br|

.. note::
       The video provides an example of exporting trials but the same process can also be used for traits and tags.



.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Exporting Data 
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Depending on what sort of data you would like to export, navigate to the **Trial Screen**, **Trait Screen**, or **Tag Screen**. Choose a trial to export. 
   * - **2.**
     - Select the **Export To Button**. You will be presented with the **Export To Options**.
   * - **3.**
     - Select the **Tablet Button** to export a data file directly to the device that you are using. The **Choose Export Option Window** will appear with the options that are listed above these instructions. 
   * - **4.**
     - Choose an export option. The Storage Access Framework (SAF) File Chooser will open.
   * - **5.**
     - Select a file location on your device to save the exported file to.
   * - **6.**
     - Select the **Select Button** to finalise the export. There will be a notification on your device when the exported file has saved to that location.


|br|

KDXplore Export (KDXchange) 
---------------------------
The KDXplore option will open KDXchange which is used for transferring data from KDXplore to KDSmart (and vice versa) over a Wi-fi connection when there is no cellular connection available. You will need access to a router or a mobile device that can host a Wi-fi hotspot. 

Connecting to KDXchange requires both KDXplore and KDSmart to be configured. There is a separate *Data Transfer* page at http://www.kddart.org/help/kdsmart/html/exchangedata.html#data-exchange-kdxchange-method  which gives specific instructions for how to use both Google Drive, and KDXchange for transferring data between KDXplore and KDSmart. See that page for more information on using KDXchange.  

|br|

Sharing Data 
""""""""""""

*Sharing* allows the user to send a trial, trait, or tag through a 3rd party application such as Google Drive, Gmail, Drop Box, etc. 


|br|

.. only:: html
    
    The video and instructions below outline how to share data. 

    
    |center-start|
    
    .. raw:: html
        
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VQPYOaGw8hY" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        
    |center-end|
    

.. only:: latex
    
    The video available at https://www.youtube.com/embed/VQPYOaGw8hY provides a guide and instructions on how to share data:
    

.. note::
     The video provides an example of exporting trials but the same process can also be used for traits and tags.
     
|br|


.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table:: Sharing Data 
  :widths: 1 70
  :class: longtable
  :header-rows: 1

  * - **Step**
    - **Action**
  * - **1.**
    - Depending on what sort of data you would like to export, navigate to the **Trial Screen**, **Trait Screen**, or **Tag Screen**.
  * - **2.**
    - Select the **Share Button**. The **Choose Export Option Window** will appear with the options that are listed above these instructions. 
  * - **3.**
    - Choose an export option. A list of applications compatible with the Storage Access Framework (SAF) will open. These applications may include Google Drive, Gmail, Drop Box, etc. 
  * - **4.**
    - Choose an application that you want to share the file with. After making a choice, the application that you chose will open. What you do next will depend on what application you are using to share the file. See the video referenced above for an example of saving a file to Google Drive. 
        
|br|

Data Backup 
===========

Any saved data on KDSmart including trials, traits, and tags, can be backed up improve data security and management.  

There are various options for backing up KDSmart data:

  * Trials as Zip - best for saving files as CSVs;  
  * Trials as KDX - best for using with KDXplore; and  
  * Database Files - for backing up all data.


|br|

.. only:: html
    
    The video and instructions below provide a guide for backing up data with the *Trials as KDX* option:    
    
    |center-start|
    
    .. raw:: html
        
        <iframe width="560" height="315" src="https://www.youtube.com/embed/3w8OAh_amao" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        
    |center-end|
    

.. only:: latex
    
    The video available at https://www.youtube.com/embed/3w8OAh_amao provides a guide and instructions for backing up data with the *Trials as KDX* option:
    

|br|


.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

.. list-table:: Data Backup
  :widths: 1 70
  :class: longtable
  :header-rows: 1

  * - **Step**
    - **Action**
  * - **1.**
    - Navigate to the **Manage Screen**. On the **Database Tab**, there are options for backing up data and database fixes.
  * - **2.**
    - Select the |folder_btn| **Output to Folder Button**. This will open the device SAF.
  * - **3.**
    - Choose a folder to save your backups to by navigating to the folder and then selecting the **Select Button**. You will be directed back to the **Database Tab**.
  * - **4.**
    - Use the radio buttons to select a backup option such as *Trials as KDX*.
  * - **5.**
    - Select the |save_btn| **Save Button** to confirm the backup. The files will now be available in the chosen location.   


|br|
