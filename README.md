# Mayhem Expanded

Mayhem Expanded (hereafter Expanded) is an expansion of Renegades, which builds upon Mayhem 3 Zero Hour and the original Mayhem 3. 

Before updating an existing installation, read the changelog for the release you are installing.

Forum thread: https://forum.egosoft.com/viewtopic.php?t=473331

Base Renegades Full Install (original): https://eve.transcendsharp.com/Mayhem/Renegades/Install_540.zip

Base Renegades Full Install - Alternative location on Google Drive: https://drive.google.com/file/d/1y5tHTYfXYe9FXuQMfDC0d3MFMbTd2vOo/view?usp=sharing

Russian localization (outdated): https://github.com/alexalsp2/Renegades_AddOns_russian

Azimuth (improved Mayhem map generator): https://github.com/ECEStuff/Azimuth_Mayhem_MapGen

# Fresh installation 
If you're installing Expanded from scratch:
1. Prepare a clean game directory. Obtain a fresh copy of vanilla X3AP.
   - Copy this somewhere to a new location.
   - Rename it to something like Mayhem_Expanded
     - This will be referred to as the Expanded directory.
   - DO NOT put your copy in your /Program Files or /Program Files (x86) folder.
   - Follow either step a or b, depending on where you purchased your copy of X3AP from.
  
   a. If you purchased X3AP from Steam:
     - Your game must be registered on the Egosoft Forums in order to download the no-Steam executable.
     - Download the no-Steam X3AP.exe here: https://www.egosoft.com/download/x3ap/bonus_en.php
     - Replace the X3AP.exe inside your Expanded directory with the no-Steam version.
     - Ensure that:
       - The game's language is set to English (check X3AP Steam properties).
       - The bonus package is disabled (not compatible with Mayhem 3).
     - See this FAQ article (https://www.egosoft.com/support/faq/faq_answer_en.php?answer=2110&version=0) regarding registering your games from Steam.
  
   b. If you purchased X3AP from GOG:
     - Your existing X3AP.exe is compatible. No changes required.

2. Install Renegades Base
   - Download the Renegades Full Install from the main Renegades thread or Google Drive. Both downloads are identical. As of July 2025, Base Renegades is version 5.4.
   - Extract all contents into your Expanded directory.

3. Install Expanded
   - Download the latest Mayhem Expanded .zip in Releases.
   - Open the zip and double-click the folder inside. Verify that you see:
     - addon
     - mayhem_data
     - cleanup.bat (updated)
     - Other included files
   - Extract all contents to the Expanded directory.
   - Run cleanup.bat
  
4. Generate the Galaxy with ZMap
   - From the Expanded root folder, navigate to the ZMap folder.
   - Open X3_Mayhem_Galaxy_Generator.exe
   - Set:
     - Game folder path (Expanded root directory)
     - Savegame path
   - Generate your galaxy.
   - Save it and set it as active.

5. Optional Configuration
   - Customize galaxy settings before generating.
   - In ZMap, you may use the Weapons and Ships Editor (third icon, top-left) to randomize ship and weapon stats.
   - Configuration files can also be edited manually:
     - /t/9972-L044.xml
     - /t/9973-L044.xml
    
6. Final Step
   - Run X3AP.exe from the Expanded directory.
   - On the main menu, verify that the active galaxy name appears in the bottom-right corner. If it appears, installation is complete.
    
# Updating or Installing over Renegades 5.4
If you're installing from Renegades 5.4 or are patching Expanded:
  - Download the latest Expanded package and extract its contents into your game's root directory, allowing files to overwrite when prompted.
  - If ZMap is installed outside of the game's root directory, manually copy TShips.txt and TBullets.txt from the release into your existing ZMap folder.
    - This applies only to very old installations where ZMap was installed separately from Renegades.
    - If ZMap is included within Renegades (default setup), no additional action is required.

# Versioning Policy
- Major versions (X.0, e.g. 2.0) change persistent world behavior or introduce major new mechanics and requiring a new game.
- Minor versions (X.Y, e.g. 2.2) may change persistent world behavior and may require a new game. Check the release changelog before updating.
- Patch versions (X.Y.Z, e.g. 2.1.2) are safe to install mid-save.
- Hotfix revisions (X.Y.Za, e.g. 2.1.2a) contain small fixes to the corresponding patch release and are safe to install mid-save unless otherwise noted.
