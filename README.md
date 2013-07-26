******************************************************************************
                         Delphi freeware Zip Project
                     Copyright (c) 2005 by Kiril Antonov
******************************************************************************

KAZIP README
------------------
Contents:
 1. Description
 2. Installation
 3. Disclaimer of warranty

DESCRIPTTION
------------
KAZIP is fast, simple zip archiver/dearchiver which uses most popular
Inflate/Deflate zip compression format.
KAZip is totaly based on Delphi VCL - no dll, ActiveX or other external libraries.
KAZip is totaly stream oriented so you can deal with data 
only in memory without creating temporary files, etc.
If you need to add zip/unzip functionality to your application,
KAZIP is the right solution. 

Functionality:
--------------
1. Zip/Unzip using Inflate/Deflate (NO ENCRYPTION SUPPORT)
2. BZip2 unzipping trough usage of BZIP2 units from Edison Mera Menéndez.
3. Functions:
   Adding Files, Folders, Streams 
   Selecting, Deselecting, Checking, 
   Extracting to files and streams

LICENCE
-------
KAZIP IS FREE FOR COMMERICAL AND NON COMMERICAL USE!
if you want to support free coding purchase KADBZIP - 
a database-oriented version od KAZip

INSTALLATION
------------
If you want to enable BZIP2 functionality 
  1. Download BZIP2 pas files and put them in the KAZIP folder or 
     folder in the delphi search path
  2. Open KAZip.Pas and change {DEFINE USE_BZIP2} to {$DEFINE USE_BZIP2}
Open KZ.DPK and press Install


DISCLAIMER OF WARRANTY
----------------------
COMPONENTS ARE SUPPLIED "AS IS" WITHOUT WARRANTY OF ANY KIND. THE AUTHOR
DISCLAIMS ALL WARRANTIES, EXPRESSED OR IMPLIED, INCLUDING, WITHOUT LIMITATION,
THE WARRANTIES OF MERCHANTABILITY AND OF FITNESS FOR ANY PURPOSE. THE AUTHOR
ASSUMES NO LIABILITY FOR DAMAGES, DIRECT OR CONSEQUENTIAL, WHICH MAY RESULT
FROM THE USE OF COMPONENTS.
USE THIS COMPONENTS AT YOUR OWN RISK

For contacts:
 my e-mail: kiril at pari.bg, kirila at abv.bg
 my site  : http://kadao.dir.bg/

Best regards
   Kiril Antonov
   Sofia
   Bulgaria
