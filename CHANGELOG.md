# Change Log

## To do

*  Add logging options (yep, since the beginning)
*  Add notification options (yep, also since the beginning)

## 2301.2

* Fixed typo in New-Item command (thanks for pointing it out, riebest!)

## 2301.1

* Added Admx for Microsoft Windows 10 (22H2)
* Added Admx for Adobe Reader and Adobe Acrobat (`breaking change`)
* Fixed Microsoft Edge (Chromium) Admx download
* Fixed Zoom Desktop Client Admx downloads (hardcoded version)
* Replaced mkdir command by native posh one
* Cleanup code

## 2209.1

* Fixed bug for Microsoft OneDrive, thanks Jonathan!
* Fixed bug for Citrix Workspace App
* Added Admx for Microsoft Windows 11 (22H2)
* Added cleanup logic for Google Chrome ADMX version checking, thanks for noticing Jonathan!
* Cleanup on code, thanks Jonathan!

## 2207.1

* Fixed bug where Citrix Workspace App would fail, thanks to Jonathan Pitre! (https://github.com/JonathanPitre)

## 2206.1

* Added requirement for elevation to prevent running unelevated
* Added parameter -UseDefaultCredentials to all Invoke-WebRequest commands, except for Adobe since that is ftp :(
* Fixed bug where Amd64 OneDrive would mess everything up
* Removed support for Zoom Desktop Client (403 error when checking for new version)

## 2112.2

* Fixed bug where Windows 10 would throw a WindowsVersion variable error

## 2112.1

`Breaking change introduced!` (See [README][read-me] for more info)

* Added parameter 'Windows10Version' (`breaking change`)
* Added parameter 'Windows11Version' (`breaking change`)
* Removed parameter 'WindowsVersion' (`breaking change`)
* Added Admx for Microsoft Windows 10 (21H2)
* Added Admx for Microsoft Windows 11 (21H2)
* Fixed bug where copying the ADMX files for Citrix Workspace App would fail
* Fixed bug where terminating a running OneDrive process would fail if a process was not found

## 2111.1

*  Internal version

## 2109.2

* Fixed bug where uninstall information for OneDrive would throw an error

## 2109.1

* Fixed bug where downloading the ADMX files for Citrix Workspace App would fail
* Fixed bug where downloading the ADMX files for BIS-F would fail to copy the .adml file
* Fixed bug where downloading the ADMX files for Microsoft OneDrive would fail

## 2107.1

* Fixed bug where Get-FSLogixOnline would fail using code provided by severud (thanks!)
* Typo corrected for Windows 20 (21H1)

## 2106.2

*  Fixed bug where script was unable to get the version for Citrix Workspace App Admx

## 2106.1

*  Added Admx for Microsoft Windows 10 (21H1)

## 2101.2

`Breaking change introduced!` (See [README][read-me] for more info)

*  Added parameter 'CustomPolicyLocation'
*  Added 'CustomPolicyLocation' logic
*  Added parameter 'Include' (`breaking change`)
*  Added 'Include' logic
*  Added parameter 'PreferLocalOneDrive'
*  Added 'PreferLocalOneDrive' logic

## 2101.1

*  Internal version

## 2012.6

*  Added parameter 'UseProductFolders'
*  Added parameter 'Languages'
*  Added 'UseProductFolders' logic
*  Added 'Languages' logic
*  Fixed bug where extracting of .cab files would fail
*  Updated verbose output

## 2012.5

*  Added Admx for Base Image Script Framework (BIS-F)
*  Added Admx for Microsoft Desktop Optimization Pack (disabled by default)
*  Updated cleanup logic

## 2012.4

*  Added Admx for Adobe AcrobatReader DC
*  Added Admx for Citrix Workspace App
*  Added Admx for Mozilla Firefox
*  Added Admx for Zoom Desktop Client

## 2012.3

*  Added Admx for Google Chrome
*  Fixed bug where hash for json output would throw an error. Switched to Xml output.

## 2012.2

*  Added .xml file for Scheduled Task creation

## 2012.1

*  Added Admx for Microsoft Windows 10 (1903/1909/2004/20H2)
*  Added Admx for Microsoft Edge (Chromium)
*  Added Admx for Microsoft OneDrive
*  Added Admx for Microsoft Office
*  Added Admx for FSLogix

[read-me]: https://github.com/msfreaks/EvergreenAdmx/blob/main/README.md