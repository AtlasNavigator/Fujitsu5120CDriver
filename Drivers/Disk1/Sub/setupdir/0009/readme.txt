         --------------------------------------------------------
                        TWAIN Data source Software
                            < 32-bit version >
                               README File
                            2, November. 2012
                           Version 9.21.1307.0
         --------------------------------------------------------

                     Copyright PFU LIMITED 1995-2012


Please read this file before using this product.  The file includes 
important notes and also the latest additional information not included
in the on-line help.

------------------------------------------------------------------------
Table of Contents 
------------------------------------------------------------------------

1. System Requirement
2. How to install
3. Note on power management
4. When using the Adaptec-made SCSI adapter
5. Notes on Two or more scanner devices at same PC.
6. Notes on duplex-scanning feature
7. Notes on scanning-area specification 
8. Notes on document-jam
9. Notes on 256 color and 8 color
10. Cautions on Automatic Size and Skew Detection
11. Notes on Automatic Page Size Detection
12. Usage note for Adobe Acrobat
13. Notes on power-off during scanning
14. Notes on system font
15. Notes on SCSI BIOS setting
16. Notes on Job Control with Cache Mode
17. About the Cache Mode setting when specifying number of sheets to scan
18. Notes on Blank Page Skip
19. About the usage of Long Page Scanning combined with Overscan
20. Notes on the use of SDTC
21. High Safety Required Use

-------------------------------------------------------------
1. System Requirement
-------------------------------------------------------------

This software is required following environments.

  1) CPU
     A PC with an Intel(R) Pentium(R) Processor or compatible one, and equipped
     with SCSI or USB1.1/2.0 interface.

  2) Operating System
     - Microsoft(R) Windows(R) 2000 Professional
     - Microsoft(R) Windows(R) XP Home Edition
     - Microsoft(R) Windows(R) XP Professional
     - Microsoft(R) Windows(R) XP Professional x64 Edition
     - Microsoft(R) Windows Server(R) 2003, Standard Edition
     - Microsoft(R) Windows Server(R) 2003 R2, Standard Edition
     - Microsoft(R) Windows Server(R) 2003 R2, Standard x64 Edition
     - Windows Vista(R) Home Basic (32/64bit)
     - Windows Vista(R) Home Premium (32/64bit)
     - Windows Vista(R) Business (32/64bit)
     - Windows Vista(R) Enterprise (32/64bit)
     - Windows Vista(R) Ultimate (32/64bit)
     - Microsoft(R) Windows Server(R) 2008, Standard Edition (32/64bit)
     - Windows(R) 7 Home Premium(32/64bit)
     - Windows(R) 7 Professional(32/64bit)
     - Windows(R) 7 Enterprise(32/64bit)
     - Windows(R) 7 Ultimate (32/64bit)
     - Microsoft(R) Windows Server(R) 2008 R2, Standard
     - Windows(R) 8 (32/64bit)
     - Windows(R) 8 Pro(32/64bit)
     - Windows(R) 8 Enterprise(32/64bit)
     - Microsoft(R) Windows Server(R) 2012, Standard

-------------------------------------------------------------
2. How to install
-------------------------------------------------------------

 - In case of installer included by SETUP DISK media
   Follow the instruction on star-up dialog starting by inserting SETUP DISK media.

 - In case of installer provided by Web or other media
   Run "setup.exe" and follow the instruction on the screen.

 - Be sure to log on as a user with Administrator privileges to install the program.


---------------------------------------------------
3. Notes on power management 
---------------------------------------------------

If a personal computer enters system standby or hibernates mode while a scanner connected 
to the personal computer is scanning documents, scanning may fail because of a breakdown 
of data communications.
To avoid this problem, disable the power options, and then scan documents again.


-------------------------------------------------------------
4. When using the Adaptec-made SCSI adapter
-------------------------------------------------------------

Information about connectable SCSI adapters is available at URL: 

http://www.fujitsu.com/global/support/computing/peripheral/scanners/scsi/index.html


---------------------------------------------------
5. Notes on Two or more scanner devices at same PC.
---------------------------------------------------

On Windows2000, this software does not support multi-device.

When using USB interface, this software does not support multi-device.


---------------------------------------------------
6. Notes on duplex-scanning feature
---------------------------------------------------

To use the duplex scanning feature in this software, the application you use 
must support the continuous-scanning feature of image data.

Thus, duplex-image data may not be scanned depending on the application, even 
though the duplex-scanning is specified. 


---------------------------------------------------
7. Notes on scanning-area specification
---------------------------------------------------

Scanning-area can be specified using the 3-type units such as millimeter(mm), 
inch, and pixel. However, please note, the scanning area may have an error of 
max.32-pixel per one line in each unit. 


---------------------------------------------------
8. Notes on paper-jam 
---------------------------------------------------

When paper-jam occurs, the error message: "Paper Jam" is displayed.
 
After the jammed documents was pulled out and the OK button on the error-message
 dialogue was pressed, the software becomes input-ready condition, and scanning 
is ready to be started. 

However, regarding the simplex scanning (duplex-scanning is not specified), in 
the case that paper-jam occurs while the top of the document is being scanned, 
one extra document may be ejected out of the documents on the tray when pressing
 the OK button in the error-message dialogue.
In this case, return the ejected document back to the tray and start to scan 
again.


---------------------------------------------------
9. Notes on 256 color and 8 color
---------------------------------------------------

This software supports 256 color and 8 color. We know that there are some 
software applications do not provide support for these two functions. They are 
Adobe PhotoShop and Adobe Acrobat and Kodak Imaging which produce a all black image.
We recommend you to use Image Professional 2.6 or Imaging on Windows OS and 
ScandAll2001 V.4.0 (or greater) for these two color features. Or simply not use 
256 color and 8 color if you do not need to.


---------------------------------------------------
10. Cautions on Automatic Size and Skew Detection
---------------------------------------------------

This driver has a function to detect document size and skew automatically and provide 
corrected output. However, certain applications do not support this function and may 
not work properly, or the output image may get corrupted. The following applications 
were found to have the problems. If you use these applications, please disable 
[Automatic Size and Skew Detection] function. 
 - Adobe Photoshop
 - Adobe Acrobat
 - Kodak Imaging


---------------------------------------------------
11.Notes on Automatic Page Size Detection
---------------------------------------------------

When Halftone, SEE or Automatic Separation scan mode selected with Automatic 
Page Size Detection turned on,
It depends on whether white/black pixel and paper size detected the time while 
scanning. 
If the while pixel is detected, it usually produces correct image as expected.
Otherwise, it doesnot produce correct image which may has a black frame 
surrounded.
It is the nature of Halftone, SEE and Automatic Separation image which filled 
with Black/White pixels and is also the limitation of Automatic Page Size 
Detection function.


---------------------------------------------------
12. Usage note for Adobe Acrobat
---------------------------------------------------

Acrobat's default settings overrides the previous settings for "Resolution", "Scan 
Type" and "Image Mode".
The following functions cannot be used.
  - "256 Color" or "8 Color"
  - Automatic Page Size Detection
  - "Rotation Degree" selection when "End of Page Detection" is selected
  - Long Page Scanning


---------------------------------------------------
13. Notes on power-off during scanning
---------------------------------------------------

If power cable or interface cable of scanner is detached during scanning, this 
software may be terminated illeagally.
So, please do not remove them during the scanner is scanning.


---------------------------------------------------
14. Notes on System font
---------------------------------------------------

Some string on dialog box of this software is cut off, if the system-font is 
changed to LARGE or greater. It is depending on a using OS and graphic 
accelerator and display drivers.
depending on graphic accelerator and display driver that you use.  
In this case, select smaller system-font for the normal display.   


---------------------------------------------------
15.  Notes on SCSI BIOS setting
---------------------------------------------------

Also, when using the software, the setting for DISCONNECT on SCSI board must be 
valid.

When using the SCSI boards described in the above "4",  the changing is not 
required because the standard setting value is already set to "DISCONNECT 
Enable".
  
For the detailed setting-procedures, please refer to the instruction manual 
attached to the SCSI board that you use.   


---------------------------------------------------
16. Notes on Job Control with Cache Mode
---------------------------------------------------

With some scanner devices:fi-4860C, fi-4990C, and M4099D, "Use Both Memory" or 
"Use Memory on Scanner" appear in "Cache Mode" of the software's option dialog.
But, if "Use Both Memory" or "Use Memory on Scanner" is selected, "Job Control" 
setting is ignored in same option dialog.


---------------------------------------------------
17. About the Cache Mode setting when specifying number of sheets to scan
---------------------------------------------------

When scanning documents by specifying the number of sheets (Page Counts) to scan from 
your application, in [Cache mode], select an item other than [Use Memory on Scanner] 
or [Use Both Memory].


---------------------------------------------------
18. Notes on Blank Page Skip
---------------------------------------------------

When the "Blank Page Skip" function is enabled, if the last page of the scanned document 
is blank, there may be cases where the "TWAIN driver" dialog is closed after the blank 
page is skipped. 


---------------------------------------------------
19. About the usage of Long Page Scanning combined with Overscan
---------------------------------------------------

If Overscan/Automatic Page Size Detection is selected together with a long page scan, 
the maximum page length is reducted by the overscan distance.

---------------------------------------------------
20. Notes on the use of SDTC
---------------------------------------------------
If you scan documents with "Black background" using "Black & White" and "SDTC Mode" 
as Image Mode, the scanned document images may not be output properly. 
In this case, set "DTC Variance" to 1 or 3 under SDTC in the Advance dialog box and 
scan documents.


---------------------------------------------------
21. High Safety Required Use
---------------------------------------------------

This Product is designed, developed and manufactured as contemplated for 
general use, including without limitation, general office use, personal use, 
household use, and ordinary industrial use, but is not designed, developed 
and manufactured as contemplated for use accompanying fatal risks or dangers 
that, unless extremely high safety is secured, could lead directly to death, 
personal injury, severe physical damage or other loss (hereinafter 
"High Safety Required Use"), including without limitation, nuclear power 
reactioncore control in nuclearatomic facility, airplane automaticaircraft 
flight control, air traffic control, operation control in mass transport 
controlsystem, medical instrument for life support system, missile launching 
control in weapon system. 
You shall not use this Product without securing the sufficient safety 
required for the High Safety Required Use. 
In addition, PFU (or other affiliated company) shall not be liable against 
the Customer and/or any third party for any claims or damages arising in 
connection with the High Safety Required Use of the Product.

------------------------------------------------------------------------
The following component is used in this product.

libtiff

Copyright (c) 1988-1997 Sam Leffler

Copyright (c) 1991-1997 Silicon Graphics, Inc.

Permission to use, copy, modify, distribute, and sell this software and its documentation for any purpose is hereby granted without fee, provided that (i) the above copyright notices and this permission notice appear in all copies of the software and related documentation, and (ii) the names of Sam Leffler and Silicon Graphics may not be used in any advertising or publicity relating to the software without the specific, prior written permission of Sam Leffler and Silicon Graphics.

THE SOFTWARE IS PROVIDED "AS-IS" AND WITHOUT WARRANTY OF ANY KIND, EXPRESS, IMPLIED OR OTHERWISE, INCLUDING WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. 

IN NO EVENT SHALL SAM LEFFLER OR SILICON GRAPHICS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND, OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER OR NOT ADVISED OF THE POSSIBILITY OF DAMAGE, AND ON ANY THEORY OF LIABILITY, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
------------------------------------------------------------------------
Microsoft and  Windows are registered trademarks of Microsoft Corporation in 
the United States and/or other countries. 
Other company name and product name are trademarks or registered trademarks of 
individual companies.
