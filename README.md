**Description**

These (clunky and slapdash) hotkeys were made to reduce the time spent tiling records for comparision in the OCLC Connexion client. Though they were made with OCLC's Member Merge training in mind, they should be useful in other contexts where the user wants to tile and compare records.

**Download AutoHotKey and macro files**
1. Download AutoHotKey and run the installer: https://autohotkey.com/download/
2. Download the AutoHotKey (.ahk) files in this repository and put them in your local Startup folder
  - Usually here: C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
  - This will be sure they're available to run whenever you turn on your computer
3. Right click on all of the .ahk files and select "Run script". This just makes them available to run when you use the designated keystrokes.

**Download fix for OCLC Connexion**
The default installation for Connexion required administrative privileges to run, which isn't necessary and may makes it impossible to run third-party macros. The following provides a fix for this:

1. Download the Auto-fix installation for Connexion here: https://www.oclc.org/support/software-reports/cataloging-software-downloads.en.html
2. Installation instructions can be found here: https://www.oclc.org/content/dam/support/connexion/documentation/client/auto-fixconnexionclient/auto-fixconnexionclient/Auto-fixConnexionClient.pdf

**Using the macros**
1. Copy the set search to your clipboard (Example: no: 629743 or no: 220509747 or no: 249919733)
2. Open Connexion and be sure you are logged in. Be sure no other windows are open in Connexion.
3. Hit the following keystrokes depending on how many records you are opening to tile the records:
  - Ctrl+2 to tile two records
  - Ctrl+3 to tile three records
  - Ctrl+4 to tile four records
4. When you are done with the records in the set, close all windows in Connexion
