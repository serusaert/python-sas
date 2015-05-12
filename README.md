# python-sas

WORK IN PROGRESS: I am re-factoring from a prototype written in Perl and learning Python at the same time, so bear with me. I am currently setting up and validating aruguments for the Sas object intialization class and the run method. I am also gradually adding methods for the features below.

DESCRIPTION:

PySAS is a Python module for scripting SAS in batch-mode. It is useful for data management and automation. PySAS makes scripting complicated data builds easier to organize and monitor. If you are in need of a scripting tool for SAS or are currently using Perl or Python to script SAS, PySAS might be worth checking out.

PySAS includes methods for parsing logs for errors, warnings, notes, and user-defined messages.

Other features:

* OS independent
* Separate return codes for all SAS log message categories: Errors, Warnings, and Notes
* Return code for user-defined custom log messages (for example, inserted into log via "put" statement)
* Log extracts for each type of log message
* Read SAS datasets (via python module sas7bdat)
* Prepend or append specified SAS code to all programs (for example, pre-pend with a set-up program)
* Run SAS code from string or file
* Configurable temp file location

Process:

Code for most of these features exists in my SASRun Perl module. I am re-factoring and translating to Python as I progress. Still somewhat in yak shaving mode.

Future:

There appears to be interest in an analytical tool in Python that uses SAS. PySAS could be used for such an implementation.

Other uses:

PySAS can be used for writing very insecure CGI scripts. I find it useful on my personal webserver (locked down to local-host) for developing data management tools such as data dictionaries, data viewers, etc..


