# python-sas

WORK IN PROGRESS: I am re-factoring from a prototype written in Perl and learning Python at the same time, so bear with me. I am currently setting up and validating aruguments for the Sas object intialization class and the run method. I am also gradually adding methods for the features below. Pass is great!

DESCRIPTION:

PySAS is a Python module for scripting SAS in batch-mode. It is useful for data management and automation. Makes scripting complicated data builds easier to organize and monitor. If you are using SAS for scripting this might be worth checking out.

Includes methods for parsing logs for errors, warnings, notes, and user-defined messages.

Other features:

* OS independent
* Separate return codes for log errors, warnings, and notes
* Return code for user-defined custom log messages (for example, inserted into log via "put" statement)
* Log extracts for each type
* Read SAS datasets (via python module sas7bdat)
* SAS code prepend
* Run SAS code from string or file
* Configurable temp file location


