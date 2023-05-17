.. About Traits



.. include:: imagerefs.txt

.. Following raw and role is required to allow the use of brown text

.. raw:: html

    <style> .orange   {color:orange}   </style>

.. role:: orange

.. raw:: html

    <style> .brown {color:brown} </style>

.. role:: brown



.. _Traits:

=======
Traits
=======

KDSmart facilitates the recording or scoring of traits for trials and nurseries. Traits are usually phenotypic information although this arbitrary.

KDSmart scoring screens are designed to allow quick recording of measurements, usually with a single touch.

Traits can be defined with validation rules to facilitate strict data capture rules to assist in preventing recording errors. These rules can also be utilised to also make scoring more efficient by minimising the required keystrokes.

The **Traits Screen** (pictured below) provides a list of all available traits and options for management of traits including importing and exporting.

|br|

What is a Trait?
================

Traits are the quality or characteristic being inspected, measured and recorded for the organism. Within KDSmart, traits have the following characteristics and features:

- User definable;
- Defined by six different data types;
- Optionally lockable once scored to prevent accidental change;
- Importable and exportable;
- Can be grouped into bundles for easier management; and
- Are either plot level or sub-plot level.

A measurement is stored for each trait instance in each plot or sub-plot includes the:

-  Date and time when the measurement was taken;
-  GPS coordinates (if this is enabled); and
-  Value of the measurement.

Some examples of traits include the height of a plant (this might be called :brown:`Plant\_Height`) or the date that a plot was irrigated (which could be called :brown:`Irrigated`).


|br|

.. raw:: latex

      \newpage


Trait Attributes
================

Each trait contains a set of attributes that define its characteristics. The following table lists the attributes of a trait:


.. list-table:: Trait Attributes
   :widths: 18 70
   :header-rows: 1

   * - **Attribute**
     - **Description**
   * - **Trait Name**
     - Must be *unique and short* for display in the **Scoring Screen** where space is limited on smaller devices (i.e. phones).
   * - **Alias**
     - An alternative trait name, useful when the trait name is too long for the screen.
   * - **Description**
     - This is an optional longer explanation of the trait to assist in data entry.
   * - **Data Type**
     - Constrains permitted values of traits. Types available are:

          - CATEGORICAL,
          - DATE,
          - ELAPSED_DAYS,
          - INTEGER,
          - DECIMAL;  |nbsp| or
          - TEXT;

       For details refer to `Trait Data Types`_
   * - **Unit**
     - An arbitrary term for the *unit* of the trait to assist with what value to enter when scoring (e.g. measurement in millimetres or centimetres).
   * - **Validation Rule**
     - The validation rule optionally restricts the values being entered. The nature of the rule is dependent upon the selection of a data type.

.. tip:: Within the **Scoring Screen**, a *long press* of any trait name will:

           - Display the trait details; and
           - Allow editing of the trait value if it is locked.


.. note:: Traits loaded from CSV all default to the *TEXT* data type unless they have previously been loaded or defined. Once loaded you may edit the trait definition to define its data type etc.

.. note:: Unless specified in the CSV, traits loaded from CSV default to the *TEXT* data type. If the Trait already exists and is not yet scored unless they have previously been loaded or defined. Once loaded you may edit the trait definition to define its data type etc.


.. raw:: latex

      \newpage

Trait Instances
===============

A trial consists of plots and sub-plots which have traits for scoring. Furthermore, KDSmart allows you to score each trait multiple times - this is called a *Trait Instance*. The benefit of instancing traits is that they are easier to create and manage because only one trait needs to be managed rather than separate ones. Having separate traits also creates more work for data analysis and curation in KDXplore.

For example, you may wish to score :brown:`PH\_Soil` three times: after 3 weeks, after 5 weeks and after 7 weeks. You can either:

-  Define three different traits (e.g. :brown:`PH\_Soil1`, :brown:`PH\_Soil2`, and :brown:`PH\_Soil3`).
-  Define three instances of the single trait (e.g. :brown:`PH\_Soil #1`, :brown:`PH\_Soil #2`, and :brown:`PH\_Soil #3`).

|br|

.. only:: html

    |center-start|

    .. thumbnail:: images/Traits/traits1.png
        :show_caption: true
        :width: 40%
        :align: center
        :title: Trait Instances

    |center-end|


.. only:: latex

    .. figure:: images/Traits/traits1.png
       :scale: 40 %
       :alt: Trait Instances

       Trait Instances

|br|

Trait Naming
============

When preparing traits it is recommended that the use spaces in trait names are avoided and underscores are used instead. For example instead of :brown:`Plant Height` use :brown:`Plant_Height`.

Should KDXplore software be used after scoring it has the ability to calculate trait values from other traits, however, is restricted if trait names contain spaces.


|br|


.. _Trait Data Types:

Trait Data Types
=================

The following table describes the available data types for traits:


.. tabularcolumns:: |\Y{0.2}|\Y{0.2}|\Y{0.2}|\Y{0.2}|


.. list-table:: Trait Data Types
   :header-rows: 1
   :class: longtable


   * - **Data Type**
     - **Description**
     - **Data Entry Style**
     - **Example Validation Rule**
   * - **TEXT**
     - No constraint on what may be entered.
     - A text input field with a full keyboard.
     - No rule required.
   * - **CATEGORICAL**
     - Value is constrained to be one from a list of allowed values. |br| Translations to other languages are supported.
     - A list of the allowed values is presented and the user touches the value desired.
     - Example: |br| :orange:`CHOICE(BLUE|YELLOW|RED)` |br| There must be at least two values provided in the pipe separated list (such as in the example above). |br| In a later release, the format will support providing a description for each value. This will likely be of the form |br| value:description |br| To prevent future problems you should not use the colon (:) character in any current value.
   * - **DATE**
     - Value is a date.
     - A calendar is presented from which to choose a date.
     - May be left blank or specified as :orange:`date`.
   * - **ELAPSED_DAYS**
     - Value is the number of days since the trial’s planting date. |br| The range in the calendar is constrained by the start date and an optional upper limit. |br| KDSmart stores the values as a date but presents the value as a number when required.
     - A list of days around the current date are presented and the user selects the desired value or chooses ':orange:`Other`' to use a calendar to pick a date outside this range. |br| The choices in the list (:orange:`-3d,  -2d, -1d, Today, +1d, +2d, +3d`) may be presented in different languages depending on locale support.
     - May be left blank or specified as |br| :orange:`elapsed_days`. |br| To enforce a maximum value, use: |br| :orange:`elapsed_days_max=NNN`.
   * - **INTEGER**
     - Integer numeric values in a range specified. |br| The range is specified as a lower and upper bound and whether or not the bounds are included in the range.
     - If the number of values is 'small' then the entry is similar to the categorical data type.  Otherwise, a numeric keypad is presented (excluding a decimal point key). |br| The changeover from categorical style to numeric keypad may be altered in the **Settings Screen**. |br| For Example: :orange:`RERANGE(1..5)`  presents as a list of choices: :orange:`1,2,3,4` but :orange:`RANGE(1..500)` presents a keypad.
     - Specify the range of values as: |br| :orange:`RANGE(min..max)` |br| or use `LERANGE, RERANGE, BERANGE` to exclude the left, right or both limits respectively. |br|  |br| Example: :orange:`RERANGE(-1..5)` |br| means the accepted values are |br| -1, 0, 1, 2, 3, 4 |br| |br| **Note:** If you use a custom keyboard, this may affect the appearance of the numeric keypad.
   * - **DECIMAL**
     - Specify a lower and upper bound and whether or not the bounds are included in the range and the number of digits of precision that will be recorded.
     - Entry is done using a numeric keypad that includes the decimal point. |br| NOTE: If you use a custom keyboard, this may affect the appearance of the numeric keypad.
     - :orange:`RANGE(min..max)` |br| or use :orange:`LERANGE, RERANGE, BERANGE` |br| However, min and max must now contain a decimal point and at least one digit following the point. |br| So: :orange:`BERANGE(1.0..2.99)` |br| means accept values for x where :orange:`1.00 < x < 2.99` |br| (the greater number of digits after the "." for min/max is  the "precision" desired).
   * - **CALC**
     - Calculated or Derived Trait. |br| |br| See `Calculated or Derived Traits`_ below for further description.
     - Data entry is not permitted for this type. |br| |br| Traits with this data type **cannot** be scored during data collection.
     - A simple calculated or derived trait is: |br| :orange:`CALC( max(PH_CM/5,1) )` |br| This calculation references a trait named :orange:`PH_CM`, dividing the value by 5 and returning the maximum of the division or :orange:`1`, whichever is the greater. So a value of :orange:`17` for :orange:`PH_CM` gives a result of :orange:`3`. |br| Alternatively, |br| :orange:`CALC( max(PH_CM/5,1) , 1 )` |br| will retain the result with one decimal place. |br| In this case the value of :orange:`17` for  :orange:`PH_CM` results in :orange:`3.4`.


|br|

.. _Calculated_or_Derived_Traits:

Calculated or Derived Traits
=============================


The validation rule has either one or two components (with a comma separating them if required):

     - The first component provides a formula that may reference other traits (by the trait name), using the operators and functions listed below.
     - If present, the second component indicates the number of decimal digits to retain in the computed result.

The functions available are in a table below. Arithmetic operators are:

    :orange:`* / %` (the last is the **modulo** operation) |br|
    :orange:`+ -` (unary minus is also supported) |br|
    :orange:`^ **` (for exponentiation).


.. Note:: The comparison operators: :orange:`< <= = != > >=` and the logical operators: :orange:`&& ||` evaluate to either :orange:`1` or :orange:`0` representing **true** or **false** respectively. This is relevant for the :orange:`if(cond,a,b)` function.


|br|

Functions Available For CALC Data Type
---------------------------------------

The following table describes the functions available for the CALC data type.


.. tabularcolumns:: |\Y{0.2}|\Y{0.4}|\Y{0.4}|


.. list-table:: Functions Available For CALC Data Type
   :widths: 5 40 40
   :header-rows: 1


   * - **Function Name(s)**
     - **Description**
     - **Example**
   * - :orange:`sin cos tan asin acos atan`
     - **Trigonometric functions**
     -
   * - :orange:`sinh cosh tanh`
     - **Hyperbolic functions**
     -
   * - :orange:`abs round floor ceil sqrt exp ln log sign`
     - **Unary mathematical functions:** |br| ROUND, FLOOR and CEIL return an integral portion of the input.  |br| LN is the natural logarithm  |br| LOG is the logarithm to base 10
     - :orange:`round(1.5)` returns 2.0 |br| :orange:`round(1.4)` returns 1.0 |br| :orange:`floor(1.5)` returns 1.0 |br| :orange:`ceil(1.5)` returns 2.0
   * - :orange:`pow min max`
     - **Binary mathematical functions**
     - :orange:`pow(2,3)` returns 8.0 |br| :orange:`pow(3,2)` returns 9.0
   * - :orange:`rnd deg(radians) rad(degrees)`
     - **Other functions:** |br| :orange:`rnd(a)` returns the value of a multiplied by a random number satisfying the constraint :orange:`RERANGE(0..1.0)` i.e. a value :orange:`x` where: :orange:`0.0 <= x < 1.0`  |br| :orange:`deg` and :orange:`rad` convert between degrees and radians.
     - :orange:`rnd(10)` will return a value :orange:`y` satisfying: |br| :orange:`0 <= y < 10`
   * - :orange:`if(expr , a , b)`
     - **Conditional expression:** |br| If the value of **expr** is **1**, the result is the expression **a** otherwise the result is expression **b**
     - :orange:`if(PH_CM <= 5 , 1 , 2)` |br| evaluates to :orange:`1` if the value of the trait :orange:`PH_CM` is 5  or less otherwise to :orange:`2`


.. tip:: Why can't I import my CALC trait?!

     - Ensure validation rules using comma's (e.g. CALC( max(PH_CM/5,1) , 1 )) are wrapped by double quotes (e.g. "CALC( max(PH_CM/5,1) , 1 )"). Excel handles this automatically.
     - Ensure the number of opening and closing brackets match (It's an easy thing to miss at a glance).
     - Trait names that use white spaces in their names cannot be used for derived CALC traits.


|br|

Categorical Traits
===================

At times during scoring, the precision level required can vary.
This may be dictated by a number of factors, e.g. sheer volume of specimens, time frame for data collection, reduced/limited people to perform the scoring, etc.
In these instances, the *Categorical* trait may be useful.


Typicall, categories are used for constraining the data entered to a predefined list of values, such as the following definitions:

- :orange:`CHOICE(BLUE | YELLOW | RED)`; and
- :orange:`CHOICE(White | Yellow | Purple | Variegated | Brown | Orange yellow | Mottled | White top | Red | Sun red | Blue | Other)`.

A *categorical other* trait is one where an *other* field can be used as a text field. In this case, the user can choose either a category that is provided to them, or the other field to enter their own text.

.. Note:: In these examples, the pipe character ‘|’ is shown with a space character either side to improve legibility.

|br|


Using Categorical Traits
------------------------


In some situations using a categorical data type may be more beneficial as this facilitates the use of selection ranges instead of data entry.

The following table illustrates the collection of plant height using both methods:

.. tabularcolumns:: |\Y{0.2}|\Y{0.4}|\Y{0.4}|

.. list-table:: Comparison Scoring Integer VS Categorical Trait Type - Required Precision 5cm
   :widths: 10 30 30
   :header-rows: 1

   * -
     - **Trait Defined as Integer**
     - **Trait Defined as Categorical**
   * - **Entry Method**
     - Plant height entered by selecting a value buttons. |br|
     - Plant height entered by selecting a value range from a list. |br|
   * - **Conditions**
     - Trait validation with a minimum of 5 and maximum of 50
     - Trait validation with six ranges defined (e.g. The unit of measure may be 5 centimetres).
   * - **Validation Rule**
     - 5 <= x <= 50
     - :orange:`CHOICE(5-10 | 10-15 | 15-20 | 20-25 | 25-30 | 30++)`.
   * - **Key Presses**
     - Minimum 2 button press per sub-plot (single digit) then **Accept Button**.
     - Minimum 1 button press per sub-plot, unless a long condition list requires scrolling.


.. Note:: For a categorical trait, the number of choices may be limited to suit the circumstances of the trial stage.

|br|
