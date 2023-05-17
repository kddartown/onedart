.. 5Jan2018 - The Sphinx help for KDSmart and KDXplore have a common topic for "KDXplore - KDSmart Data Exchange".
   This is achieved by the following:
   The images for this section are stored in commonimages/kdaps to avoid duplication.
   
   The topic in KDSmart/source/exchangedata-include.txt is where the topic really resides.
   This topic "exchangedata-include.txt" is included by ".. include:: ../../kdsmart/source/exchangedata-include.txt" in:
   KDXplore Topic "KDXplore-TrialManagement.rst" and
   KDSmart topic "exchangedata.rst".
   
   The treatment for topic levels is the include file needed them pushed down 1 level.
   KDSmart's "exchangedata.rst" has the original header and preliminary elements.


.. include:: imagerefs.txt


.. Following raw and roles are required to allow use of coloured text



================================
Data Transfer
================================




.. include:: ../../kdsmart/source/exchangedata-include.txt
