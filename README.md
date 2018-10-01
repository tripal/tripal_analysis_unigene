DEPRECATED  
==========
This module is no longer needed for Tripal v3 or later.  

Summary
=======
In summary, This module extends the Tripal v2 Analysis Module and provides visualization of Unigenes derived from ESTs. 

Conversion of Tripal v2 Unigene Analyses to Tripal v3
=====================================================
First, be sure you have the most recent run updatedb for this module so you have the analysis_type set
• define a unigene bundle with that cvterm config
• run alchemist “automatic” with the vanilla analysis as the soruce and your new, unigene bundle as aathe destination (edited)
the first step is necessary because as that issue points out, it uses some random property (analysis_unigene_name?) to determine if its a unigene (edited)
alternatively you could create a Tripal 3 collection of all the analyses you want to convert.  Alchemist supports collections.
