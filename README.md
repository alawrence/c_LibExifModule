c_LibExifModule
Sleuth Kit Framework C++ Module
May 2012
===============

C++ Sleuth Kit Framework module that wraps libexif to pull out EXIF data.

DESCRIPTION

This module is a file analysis module that will check all files for an exif
header, then parse any found headers for metadata of interest. Any metadata
of interest will be posted to the blackboad as TSK_METADATA_EXIF artifacts.

This module allows you to extract information from the system's registry.

USAGE

Add this module to a file analysis pipeline. See the TSK
Framework documents for information on adding the module
to the pipeline:

    http://www.sleuthkit.org/sleuthkit/docs/framework-docs/


RESULTS

All results will be posted to the blackboard as TSK_METADATA_EXIF artifacts.


TODO
- Make metadata of interest configurable. 