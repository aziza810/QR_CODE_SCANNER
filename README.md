LEXMARK QR CODE GENERATOR
Readme for version 5.0.1

1. OVERVIEW

    This Readme file pertains to the current release of the LEXMARK QR CODE
    GENERATOR application.

    Lexmark QR Code Generator is an embedded solution that can be installed on
    printers that support the Lexmark Embedded Solutions Framework (eSF) v5.x.
    QR Code Generator encodes either the printer IP address or a custom string
    into a QR code that can be scanned by mobile devices with cameras. The
    generated QR code is available by selecting the QR code icon.


2. ASSOCIATED FILES

    a. Application files

       *  qrCodeGen_e5-5.0.1.fls
          *  The QR Code Generator application for eSF v5.x printers

    b. Other files

       *  qrCodeGen_e5_desc-5.0.1.xml
          *  The solution descriptor file for eSF v5.x printers


    c. Publications

       *  QR Code Generator Administrator's Guide

       *  Readme.txt
          *  (This file)


3. REQUIREMENTS

    a. A printer that supports eSF v5.x applications

        Supported eSF v5.x printers include:
          *  CS720
             *  Required firmware level: CB.02.015 or later

          *  CS820
             *  Required firmware level: YK.01.093 or later

          *  CX720
             *  Required firmware level: ATL.02.015 or later

          *  CX820
             *  Required firmware level: PP.02.041a or later

          *  CX825
             *  Required firmware level: PP.02.041a or later




    b. Memory: The printer must have a minimum of 256MB RAM.


4. LIMITATIONS AND COMPATIBILITY OF THE RELEASE

    a. The QR code icon, which opens the large QR code, can also be scanned
       with a mobile device. However, if a host name is used as the QR value
       and the host name is changed, then restart the printer for the
       change to take effect. The large QR code will work correctly without a
       restart.


    For more information on installation and configuration, see the
    QR Code Generator Administrator's Guide at http://support.lexmark.com. 
    Adobe Acrobat Reader is required to view this guide.
