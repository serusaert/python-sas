# python-sas

<WORK IN PROGRESS, re-factoring from prototype written in Perl, learning Python at the same time, so bear with me...>

Python module for scripting batch-mode SAS. Useful for data management and automation. Makes scripting complicated data builds easier to organize and monitor. If you are using SAS for scripting this might be worth checking out.

Includes methods for parsing logs for errors, warnings, notes, and user-defined messages.

Other features:

* OS independent
* Separate return codes for log errors, warnings, and notes
* Return code for user-defined custom log messages (for example, inserted into log via "put" statement)
* SAS code prepend
* Read SAS datasets (using python module sas7bdat) 
* Configurable temp file location
* 
