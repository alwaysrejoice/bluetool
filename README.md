# bluetool
========================================================================
    WIN32 APPLICATION : bluetool Project Overview
========================================================================

This application is created for writing ID into device, following are funtionality explanation:

scan device: first, you have to enter COMport into the box below Scan device button, then press scan device button.
connect: press this button to connect to a selected device.
disconnect: press this button to disconnect device
scan Label: clean all text in edit boxes
Write ID: write ID into device (handle is 38)
Read ID: read ID from handle 38 in the device
Save: save all data to a file which is in "data" folder, the file is named as the format month\day\year\hour\minute\second.txt
for example:123016182426.txt, 12 is month, 30 is day, 16 is year, 18 is hr(24 hr format), 24 is minutes, 26 is seconds.

please remember to save data every time, because if you close the application without saving data, the record will be missing.



AppWizard has created this bluetool application for you.

This file contains a summary of what you will find in each of the files that
make up your bluetool application.


bluetool.vcxproj
    This is the main project file for VC++ projects generated using an Application Wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    Application Wizard.

bluetool.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

bluetool.cpp
    This is the main application source file.

/////////////////////////////////////////////////////////////////////////////
AppWizard has created the following resources:

bluetool.rc
    This is a listing of all of the Microsoft Windows resources that the
    program uses.  It includes the icons, bitmaps, and cursors that are stored
    in the RES subdirectory.  This file can be directly edited in Microsoft
    Visual C++.

Resource.h
    This is the standard header file, which defines new resource IDs.
    Microsoft Visual C++ reads and updates this file.

bluetool.ico
    This is an icon file, which is used as the application's icon (32x32).
    This icon is included by the main resource file bluetool.rc.

small.ico
    This is an icon file, which contains a smaller version (16x16)
    of the application's icon. This icon is included by the main resource
    file bluetool.rc.

/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named bluetool.pch and a precompiled types file named StdAfx.obj.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" comments to indicate parts of the source code you
should add to or customize.

/////////////////////////////////////////////////////////////////////////////
