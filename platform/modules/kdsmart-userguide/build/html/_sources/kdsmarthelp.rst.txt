.. File converted, quickly, from Brian's HowTo-Score_A_Trial.html
 


.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .brown {color:brown} </style>


.. role:: brown

.. |menu_btn| image:: images/buttons/ic_action_overflow_black.png
            :scale: 17 %

.. |image4| image:: images/ic_action_visibility_dark_blackback.png
            :scale: 100 %

.. |image5| image:: images/ic_action_visibility_light.png
            :scale: 100 %

.. |image6| image:: images/main-black-active-trial_framed.png
            :scale: 50 %

.. |image7| image:: images/main-white-active-trial_framed.png
            :scale: 50 %

.. |traits| raw:: html

   <a href="http://www.kddart.org/help/kdsmart/html/traits.html" target="_blank">traits</a>   



============== 
Scoring
============== 

Scoring is the collecting of data for a trial with KDSmart. It mostly involves applying values to predefined traits in that trial, but could also include adding tags, notes, and attachments to plots or sub-plots as well. 

This page will provide information on how to score trials, as well as some scoring options and features. 

For more information on scoring and how it works within the context of the KDDart Platform, see the *KDSmart* section of the Tutorials page at: http://www.kddart.org/help/kdtutorials/html/KDSTutorial.html

|br|

The Scoring Screen 
==================

The **Scoring Screen** that you will be presented with when you start scoring will depend on the *Scoring View* that you choose when configuring the collection parameters of your trial. For more information see the *Collection Parameters* section of the Trial Details Page at: http://www.kddart.org/help/kdsmart/html/preparation.html#collection-parameters


|br|

Sheet Scoring Mode 
""""""""""""""""""

**Sheet Scoring Mode** is a simple-sheet style view, similar to CSV or Excel document. This mode presents all traits for plots and sub-plots in a spreadsheet and selecting a cell will allow for entering of data. It has limited plot navigation features and can be slower to score, but many users find the view familiar and easy to use. 

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring5.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Sheet Scoring Mode 

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring5.png
       :scale: 17 %
       :alt: Sheet Scoring Mode 
       
       Sheet Scoring Mode 
             
|br|

|br|

Path Scoring Mode 
"""""""""""""""""
In **Path Scoring Mode**, you will only select one plot at a time, for which you will be able to see all plot info, including plot traits, sub-plots, sub-plot traits, tags, etc. This mode is designed for easy navigation between plots as you physically walk through a field, score the traits, then move to the next plot on the **Scoring Screen**. This also allows the user to choose the **Auto-Advance Mode** which is the quickest way to score but will be explained further below. Additionally, **Path Scoring Mode** includes **Field View** which displays a top-down view of your field.

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring6.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Path Scoring Mode

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring6.png
       :scale: 17 %
       :alt: Path Scoring Mode
       
       Path Scoring Mode
             
|br|

|br|

Field Scoring Mode 
""""""""""""""""""

.. Note:: Coming soon with KDSmart version 3.1 in June 2019!

|br|

Screen Orientation
""""""""""""""""""

The **Scoring Screen** in KDSmart (in **Path Scoring Mode**) can be oriented to best suit the user who is scoring. You can choose between **Portrait** or **Landscape Orientation**, and **Left-handed** or **Right-handed Mode**. The default is **Right-handed/Portrait Orientation** but this can easily be changed. |br| |br|

To change screen orientation, select the |menu_btn| **Menu Button** and then the **Change Screen Orientation Button**. You will have a few seconds to physically tilt your device into the **Landscape** or **Portrait Orientation** and the orientation will be set. |br|


.. list-table:: Landscape Orientations 
   
   * - 
       |br|
       
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/Scoring/scoring1.png
               :show_caption: true
               :width: 100%
               :align: center
               :title: Right-handed/Landscape Orientation
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/Scoring/scoring1.png
              :scale: 100 %
              :alt: Right-handed/Landscape Orientation
              
              Right-handed/Landscape Orientation
       
       |br|

   * - 
       |br|
       
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/Scoring/scoring4.png
               :show_caption: true
               :width: 100%
               :align: center
               :title: Left-handed/Landscape Orientation
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/Scoring/scoring4.png
              :scale: 100 %
              :alt: Left-handed/Landscape Orientation
              
              Left-handed/Landscape Orientation
       
       |br|

|br|

Select the |menu_btn| **Menu Button** in the top right-hand corner of the **Scoring Screen** to be presented with menu options. Select the **Swap Sides Button** to swap between **Right-handed** and **Left-handed Mode**. |br|

.. list-table:: Portrait Orientations 
  
  * - 
      |br|
      
      .. only:: html
      
          |center-start|
      
          .. thumbnail:: images/Scoring/scoring2.png
              :show_caption: true
              :width: 100%
              :align: center
              :title: Left-handed Portrait Orientation
      
          |center-end|
      
      
      .. only:: latex
      
          .. figure:: images/Scoring/scoring2.png
             :scale: 100 %
             :alt: Left-handed Portrait Orientation
             
             Left-handed Portrait Orientation
                   
      |br|
      
    - 
  
      |br|
      
      .. only:: html
      
          |center-start|
      
          .. thumbnail:: images/Scoring/scoring3.png
              :show_caption: true
              :width: 100%
              :align: center
              :title: Right-handed Portrait Orientation
      
          |center-end|
      
      
      .. only:: latex
      
          .. figure:: images/Scoring/scoring3.png
             :scale: 100 %
             :alt: Right-handed Portrait Orientation
             
             Right-handed Portrait Orientation
                   
      |br|
             
.. note:: **Sheet Scoring Mode** and the upcoming **Field Scoring Mode** can operate in **Portrait** or **Landscape Mode** but there is no **Left-handed** or **Right-handed Mode**.   


|br|

Applying a Trait Value
======================
Applying trait values is the primary function of scoring trials. Selecting a trait to score will be different depending on what scoring mode you are using, however applying traits will always be the same as each scoring mode utilises the same **Trait Measurement Screen**. Follow the instructions below to learn how to score a trait. 

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Scoring
  :widths: 1 99
  :class: longtable
  :header-rows: 1
  
  * - **Step**
    - **Action**
  * - **1.**
    - To open the **Trait Measurement Screen**, select any trait on the **Scoring Screen**. You can choose a trait with no value such as the trait outlined at |circle1| in the below image, or a trait that already has a value such as the trait outlined at |circle2|. 

       .. only:: html

           |center-start|

           .. thumbnail:: images/Scoring/scoring8.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Selecting a Trait to Score
     
           |center-end|


       .. only:: latex
     
           .. figure:: images/Scoring/scoring8.png
              :scale: 17 %
              :alt: Selecting a Trait to Score
             
              Selecting a Trait to Score
  * - **2.**
    - The screen below is the **Trait Measurement Screen** which allows you to choose a trait value. This will be different depending on the trait data type - this example is of an *elapsed days* trait. You can also swipe right to see more information about the current plot. Either select a value or choose one of the trait scoring options at the bottom of the screen e.g. **Reverse Button** to go to the previous trait. The table below provides information on the scoring options.  
    
    
      .. only:: html

          |center-start|

          .. thumbnail:: images/Scoring/scoring9.png
              :show_caption: true
              :width: 40%
              :align: center
              :title: Selecting a Trait Value
    
          |center-end|


      .. only:: latex
    
          .. figure:: images/Scoring/scoring9.png
             :scale: 17 %
             :alt: Selecting a Trait to Value
            
             Selecting a Trait to Value
  * - **3.**
    - After applying a trait, you will be taken back to the **Scoring Screen**. Select another trait to choose a value for it and repeat the process until you have scored all traits. 
    
    
.. tabularcolumns:: |\Y{0.4}|\Y{0.6}|


.. list-table:: Scoring Options of the Trait Measurements Screen
  :class: longtable
  :header-rows: 1
  
  * - **Button**
    - **Action**
  * - |cancel_btn| **Cancel Button**
    - Cancels the scoring of the selected trait. Cancelling will return the user to the **Scoring Screen**
  * - |backspace_btn| **Delete Value Button** 
    - Deletes a current value and returns the user to the **Scoring Screen**. 
  * - |missing_btn| **Missing Value Button**
    - Applies the value of *Missing* to a trait instance. This can be used if the actual value is missing.
  * - |na_btn| **Not Applicable Button**
    - Applies the value of *Not Applicable* to a trait instance. This can be used when the trait does not need to be scored for the selected plot or sub-plot.
  * - |accept_btn| **Accept Value Button**
    - Accepts and applies a value that has been entered such as confirming a decimal trait.  
  * - |calendar_btn| **Date Button** (only available for *elapsed days* traits) 
    - Opens a *Date Picker* so that a date can be chosen.
  * - |reverse_btn| **Reverse Button** (only available in **Auto-Advance Mode**)
    - Navigates to the previous trait instance.
  * - |forward_btn| **Forward Button** (only available in **Auto-Advance Mode**)
    - Navigates to the next trait instance by skipping the current trait.


.. only:: html

    The video below is a demonstration of scoring at trial in KDSmart. You will be able to see how trait values are applied to trait instances. |br|
    Please note that whilst this video demonstrates scoring in **Path Scoring Mode**, the application of trait values is done from the same **Trait Measurement Screen** in any scoring mode. 
    
    |br|
    
    |center-start|
    
    .. raw:: html
    
        <iframe width="560" height="315" src="https://www.youtube.com/embed/2qilBe2xGwM" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    
    |center-end|
    

.. only:: latex
    
    The video available at https://www.youtube.com/embed/2qilBe2xGwM is a demonstration of scoring at trial in KDSmart. You will be able to see how trait values are applied to trait instances. 
    Please note that whilst this video demonstrates scoring in **Path Scoring Mode**, the application of trait values is done from the same **Trait Measurement Screen** in any scoring mode. 


|br| 


Additionally, the sections below provide further information on navigation between plots.

|br|

Navigating Between Plots 
========================

It is crucial that users are able to navigate between plots quickly so that trials can be efficiently scored. This is why there are plenty of options for navigating between plots. The video referenced above (Scoring a Trial in KDSmart) also outlines the navigation methods in **Path Scoring Mode**. See the sub-sections below for more information on navigation between plots. 

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring10.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Navigation Options

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring10.png
       :scale: 17 %
       :alt: Navigation Options
       
       Navigation Options
             
|br|

|center-start|

.. tabularcolumns:: |\Y{0.1}|\Y{0.5}|

.. list-table:: Navigation Options in Path Scoring Mode
  :widths: 1 2
  :class: longtable
  :header-rows: 1
  
  * - **Button**
    - **Action**
  * - |circle1| 
    - Advance/Retreat 
  * - |circle2| 
    - Plot Selection
  * - |circle3| 
    - Field View

|center-end|  
  
.. note:: The information in this section is about navigation in **Path Scoring Mode**. Scoring in **Sheet Scoring Mode** is simpler, as you only need to select a cell to score it, but it can also be slower than using **Path Scoring Mode**. 

|br|

Advance/Retreat
"""""""""""""""
Advancing and retreating is moving to the next or previous plot that is determined by your collection order. For example, if you are starting on plot 1, you can advance to plot 2 and then retreat back to plot 1. The |advance_btn_black| **Advance Button** will move you to the next plot and the |retreat_btn_black|  **Retreat Button** will move you to the previous plot.    

|br|

Plot Selection
""""""""""""""
Plot selection is directly entering the number or x/y coordinates of a plot to navigate to it. Selecting the **Plot Button** as outlined in |circle2| in the image above will display the **Plot Selection Window** as below:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring11.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Plot Selection Window

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring11.png
       :scale: 17 %
       :alt: Plot Selection Window
       
       Plot Selection Window
             
|br|

You can navigate to a plot by either choosing it's x/y coordinates or the plot number and then selecting the **Go Button** to confirm. 

|br|

Field View
"""""""""" 
**Field View** is a top-down look at the field which offers an alternative way to navigate between plots, search plots, and produce heatmaps. It will provide different information depending on the level that it is being viewed at (how zoomed in/out you are). At a minimum, the collection order (the arrows in each plot) and the percentage of each plot scored (the grey bar in each plot) will be displayed. Select the |zoom_in_btn|/|zoom_out_btn| **Zoom In/Out Button** to reach higher or lower level views. Lower level views have more information about tags, traits, trait values, etc.  The image below is an example of **Field View** at the *highest* level:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring16.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Field View

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring16.png
       :scale: 17 %
       :alt: Field View
       
       Field View
             
|br|

A *long press* on a plot will reveal a window with information on that plot. A *short press* will provide both plot information and options for selecting multiple plots and navigating to that plot (as seen in the image below). Select the **Go To Button** to navigate to the selected plot.   

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring12.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Field View Plot Options

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring12.png
       :scale: 17 %
       :alt: Field View Plot Options
       
       Field View Plot Options
             
|br|

Auto-Advance 
""""""""""""
The quickest way to score traits is to use the **Auto-Advance Mode**. Auto-advance also allows the user to concentrate on only those traits for which a measurement has not been provided. 

When the user provides a value for a trait, KDSmart moves the focus to the next un-scored trait, skipping over those traits (and sometimes entire plots) which have already been scored. This is useful when starting scoring as it quicker and when scoring has been finished if the user needs to find any un-scored plots or traits. The following video and instructions demonstrate how to use *Auto-Advance*:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring7.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Auto-Advance Options  

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring7.png
       :scale: 17%
       :alt: Auto-Advance Options 
       
       Auto-Advance Options 

|br|

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|

       
.. list-table:: Using Auto-Advance
   :widths: 7 60
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Select the |autoadvance_btn| **Start Auto-Advance Button** at the top menu of the **Scoring Screen** to turn on **Auto-Advance Mode**. This will provide auto-advance options as seen in the image above. 
   * - **2.** 
     - Choose either the *All Traits* option to score all traits within the dialogue box, or the *Un-scored Traits* option.
   * - **3.**
     - Begin scoring by selecting the blank area next to an un-scored trait. This displays a new screen with the data entry form for the trait on one side and the *Plot Information* on the other side (this is demonstrated in the image above).
   * - **4.**
     - The |advance_btn_black|/|retreat_btn_black| **Advance/Retreat Buttons** are no longer available, but there are |reverse_btn|/|forward_btn| **Backward/Reverse Buttons** along the bottom that may be used if you want to skip to the next trait or revisit the previous one. If a plot is skipped, then KDSmart will let the user know this by:                                                  
        
        -  Vibrating the device;           
        -  Posting a system notification; and                 
        -  Displaying a popup message for the user to confirm that they have reached the correct plot to continue scoring.  
   * - **5.**
     - Return to the **Scoring Screen** and select the |autoadvance_pause_btn| **Stop Auto-Advance Button** then the **Cancel Button** to stop auto-advancing between traits.

|br|


.. only:: html
    
    
    |center-start|
    
    .. raw:: html
        
            <iframe width="560" height="315" src="https://www.youtube.com/embed/vsnCG3Ef40c" frameborder="1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        
    |center-end|
    

.. only:: latex
    
    The video available at https://www.youtube.com/embed/vsnCG3Ef40c is a demonstration and instructions on the use of *Auto-Advance*.
    

|br|

.. note:: The Auto Advance feature is only available in **Path Scoring Mode**. 

|br|

Assigning Tags 
============== 

Tags are short text descriptions that are designed to be like reusable notes that can be applied to plots or sub-plots. Along with scoring traits, assigning tags is a part of the scoring process. One or more tags may be assigned to a plot (or sub-plot) or reassigned if required. More information about tags and their management can be found in the *Tags* page at http://www.kddart.org/help/kdsmart/html/tags.html


To assign a tag in **Path Scoring Mode**, follow these steps:

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Assigning Tags
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Locate a plot or sub-plot to tag in the **Scoring Screen**. 
     
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/scoring/scoring13.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Tags on the Scoring Screen
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/scoring/scoring13.png
              :scale: 17 %
              :alt: Tags on the Scoring Screen
              
              Tags on the Scoring Screen
   * - **2.**
     - Select the |assign_tag_btn| **Assign Tag Button**.     
   * - **3.**
     - Select one or more tags to assign them to a plot.
     
       .. only:: html
       
           |center-start|
       
           .. thumbnail:: images/scoring/scoring14.png
               :show_caption: true
               :width: 40%
               :align: center
               :title: Assigning Tags
       
           |center-end|
       
       
       .. only:: latex
       
           .. figure:: images/scoring/scoring14.png
              :scale: 17 %
              :alt: Assigning Tags
              
              Assigning Tags
   * - **4.**
     - Select the **Confirm Button** (tick) to save changes and return to the **Scoring Screen**. This displays the tag short name above the traits for the selected plot.


|br|

Adding Notes 
============

Notes can be added on each plot or sub-plot in a trial. In any scoring mode, this can be done by selecting the |plot_btn|/|subplot_btn| **Plot/Sub-plot Button** which will display some options such as an **Edit Note Button**. This can be seen in the image below (**Path Scoring Mode**).

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring17.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Adding Notes 

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring17.png
       :scale: 17%
       :alt: Adding Notes
       
       Adding Notes

|br|
 
.. note:: The **Sub-plot Button** in this example is of maize but it may be different depending on your settings e.g. a leaf or DNA icon. You can see that you can also deactivate plots and sub-plots in this menu and add sub-plots if needed. 

Adding Attachments 
==================

Both images and audio files can be attached to each plot and sub-plot in KDSmart and can be used instead of notes or tags. The |attachment_btn| **Attachment Button** can be found on each plot and sub-plot (next to the |assign_tag_btn| **Tag Button**) and will open the **Attachment Screen** as seen below:

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Scoring/scoring18.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Attachments Screen

    |center-end|


.. only:: latex

    .. figure:: images/Scoring/scoring18.png
       :scale: 17%
       :alt: Attachments Screen
       
       Attachments Screen

|br|

There are two attachments currently saved in the example above; one is an image and one is an audio file. This can be seen by the .jpg and .3gp file extensions. There are two tables below with instructions on attaching images and audio files.

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Attaching and Viewing Image Files
   :widths: 1 70
   :class: longtable
   :header-rows: 1

   * - **Step**
     - **Action**
   * - **1.**
     - Image files can be attached by taking a picture with the device camera. Select the |camera_btn| **Camera Button** to open the device's camera application.
   * - **2.**
     - Take a picture and select the **Confirm Button**. This will look different depending on what device you are using.
   * - **3.**
     - The new attachment should appear in the list of attachments as seen in the image above. Select the |view_btn| **View Button** to open the image.
   * - **4.**
     - Select the |discard_btn| **Delete Button** to delete the image. Please note that there is no way to reverse a deletion. 

.. tabularcolumns:: |\Y{0.1}|\Y{0.7}|


.. list-table:: Attaching and Listening to Audio Files 
   :widths: 1 70
   :class: longtable
   :header-rows: 1
 
   * - **Step**
     - **Action**
   * - **1.**
     -  Audio files can be attached by making an audio recording with the device microphone. Select the |record_btn| **Record Button** to start recording. The button will turn red to indicate that recording has started.
   * - **2.**
     - The |pause_btn| **Pause Button** will now be available if you want to pause the recording of the audio file. If you pause the audio recording, the button will turn red to indicate that recording is currently paused. Press the |pause_btn| **Pause Button** again to resume recording. 
   * - **3.**
     - Select the |record_btn| **Record Button** again (when it is red) to stop the recording. 
   * - **4.**
     - The new attachment should appear in the list of attachments as seen in the image above. Select the |play_btn| **Play Button** to listen to the recording and the |stop_btn| **Stop Button** to stop the recording.   
   * - **5.**
     - Select the |discard_btn| **Delete Button** to delete the recording. Please note that there is no way to reverse a deletion. 
        
|br|









.. |autoadvance_btn| image:: images/buttons/ic_action_play_over_video_black.png
   :scale: 17 %
   
.. |autoadvance_pause_btn| image:: images/buttons/ic_action_pause_over_video_black.png
   :scale: 17 %
      
.. |retreat_btn_black| image:: images/buttons/ic_object_retreat_black.png
   :scale: 17 %
         
.. |advance_btn_black| image:: images/buttons/ic_object_advance_black.png
   :scale: 17 %
            
.. |reverse_btn| image:: images/buttons/reverse_black.png
   :scale: 17 %
               
.. |forward_btn| image:: images/buttons/forward_black.png
   :scale: 17 %

.. |plotloc| image:: images/plot-and-location-black-512.png
   :scale: 80 %

.. |zoom_in_btn| image:: images/buttons/ic_action_zoom_in_black.png
   :scale: 50 %
      
.. |zoom_out_btn| image:: images/buttons/ic_action_zoom_out_black.png
   :scale: 50 %
         
.. |missing_btn| image:: images/buttons/ic_action_help_black.png
   :scale: 50 %
      
.. |accept_btn| image:: images/buttons/ic_action_accept_black.png
   :scale: 50 %

.. |cancel_btn| image:: images/buttons/ic_action_cancel_black.png
   :scale: 50 %
   
.. |calendar_btn| image:: images/buttons/ic_action_go_to_today_black.png
   :scale: 50 %
   
.. |na_btn| image:: images/buttons/na.png
   :scale: 50 %
  
.. |backspace_btn| image:: images/buttons/backspace_black.png
   :scale: 50 %

.. |search| image:: images/ic_action_search_black.png
   :scale: 50 %

.. |camera_btn| image:: images/buttons/camerabutton.png
   :scale: 50 %
      
.. |discard_btn| image:: images/buttons/discardbutton.png
   :scale: 50 %
         
.. |pause_btn| image:: images/buttons/pausebutton.png
   :scale: 50 %
            
.. |play_btn| image:: images/buttons/playbutton.png
   :scale: 50 %

.. |stop_btn| image:: images/buttons/stopbutton.png
   :scale: 50 %
                     
.. |record_btn| image:: images/buttons/recordbutton.png
   :scale: 50 %
                  
.. |view_btn| image:: images/buttons/viewbutton.png
   :scale: 50 %
                     
.. |action_upload| image:: images/ic_action_upload_black.png
   :scale: 50 %

.. |action_download| image:: images/ic_action_download_black.png
   :scale: 50 %

.. |plus-action| image:: images/kds-plus-action.png
   :scale: 50 %

.. |assign_tag_btn|  image:: images/buttons/ic_action_new_label_black.png
   :scale: 50 %
   
.. |attachment_btn|  image:: images/buttons/ic_action_new_attachment_black.png
   :scale: 50 %
      
.. |find-plots-tag| image:: images/kds-find-plots-tag.png
   :scale: 70 %

.. |edit-action| image:: images/ic_action_edit_black.png
   :scale: 50 %

.. |new-action| image:: images/ic_action_new_black.png
   :scale: 50 %

.. |plot_btn| image:: images/buttons/ic_object_plot.png
   :scale: 50 %
      
.. |subplot_btn| image:: images/buttons/ic_organism_maize_live.png
   :scale: 50 %

.. |black5| image:: images/blackbrackets5.png
   :scale: 50 %
.. |black3| image:: images/blacknumber3.png
   :scale: 50 %
.. |black2| image:: images/blacknumber2.png
   :scale: 80 %
.. |arrows| image:: images/arrows.png
            :scale: 100 %

.. |image8| image:: images/06-ScoreConfig_Options-Phone-P.png
            :scale: 100 %

.. |image9| image:: images/configure-trait-black_framed.png
            :scale: 100 %

.. |important| image:: images/ic_action_important.png
            :scale: 100 %

.. |half-important| image:: images/ic_action_half_important.png
            :scale: 50 %

.. |not_important| image:: images/ic_action_not_important.png
            :scale: 100 %

.. |image12| image:: images/ic_action_overflow.png
            :scale: 100 %

.. |image13| image:: images/ic_action_play.png
            :scale: 100 %

.. |image17| image:: images/ic_action_play.png
            :scale: 100 %

.. |image18| image:: images/ic_action_play.png
            :scale: 100 %

.. |image19| image:: images/ic_action_visibility_dark_blackback.png
            :scale: 100 %

.. |image20| image:: images/ic_action_visibility_light.png
            :scale: 100 %

.. |image21| image:: images/lockdown_inactive.png
            :scale: 100 %

.. |image22| image:: images/lockdown_inactive.png
            :scale: 100 %

.. |image23| image:: images/kds_settings.png
            :scale: 50 %

.. |image26| image:: images/Scoring.png
   :scale: 80 %

.. |new_label_btn| image:: images/ic_action_new_label_black.png
            :scale: 100 %

.. |image28| image:: images/ic_action_new_attachment_black.png
            :scale: 100 %

.. |image29| image:: images/ic_action_attachment_black.png
            :scale: 100 %

.. |image30| image:: images/ic_object_plot.png
            :scale: 100 %

.. |image31| image:: images/Scoring-Navigation-P.png
            :scale: 100 %

.. |image32| image:: images/btn_advance_black.png
            :scale: 100 %

.. |image33| image:: images/btn_retreat_black.png
            :scale: 100 %

.. |image34| image:: images/ic_action_play_over_video_black.png
            :scale: 100 %

.. |image35| image:: images/reverse_black.png
            :scale: 100 %

.. |image36| image:: images/forward_black.png
            :scale: 100 %

.. |image37| image:: images/autoscoring_framed.png

