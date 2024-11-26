## OpenNTF Project Database Metadata Export



#### Overview

The **OpenNTF Project Database Metadata Export** is a Java-based utility leveraging the Domino JNX API to extract metadata from the OpenNTF project database. It includes a metadata database template and enables exporting the extracted data into both NSF and JSON formats for further use.

This utility is used for creating the [OpenNTF Projects Dataset](https://www.openntf.org/main.nsf/project.xsp?r=project/OpenNTF Projects Dataset). It is provided as an example of Domino JNX library.



#### Usage:

Use command line parameters:

```
-pmt=server!!path/to/pmt.nsf \
-target=server!!path/to/pmt_metadata.nsf \
-json=path/to/pmt_metadata.json
```



#### Prerequisites

Before using the agent, ensure you have the following:

-   IBM HCL Domino server or client installed locally.

-   OpenNTF Projects database is accessible

-   Tested on Java version 17.

-   Make sure you have set following environment variables. Values are examples for Mac OS

    -   DYLD_LIBRARY_PATH=/Applications/HCL Notes.app/Contents/MacOS
    -   LD_LIBRARY_PATH=/Applications/HCL Notes.app/Contents/MacOS
    -   Notes_ExecDirectory=/Applications/HCL Notes.app/Contents/MacOS

-   If you are using Silicon, make sure you install Rosetta based JVM to run the code. Tested on "IBM Semeru Runtime Open Edition 17 (x86_64)"

    

