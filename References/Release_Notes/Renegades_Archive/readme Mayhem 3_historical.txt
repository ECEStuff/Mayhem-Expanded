
Mayhem 3 is NOT compatible with Mayhem 2. You need a fresh install if you're coming from Mayhem 2.
--------------------------------------------------------------------------------------------------

LICENSE
=======

About the Original Galaxy Generator (referred below as "the software"), and also ZMap:
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

FRESH INSTALL
=============

Renegades - Note, for Renegades, follow the install instructions on the forum post for this mod.  Installation should be far easier than previous releases of Mayhem 3.
	For the most part, installation of Renegades can be done by taking the original Albion Prelude release copy, extracting Rengades over it, and then running a Cleanup.bat
	file to get rid of files the Litcubes install used to get rid of, and then copying the X3AP.exe "NoSteam" executable over.

You can also read the article about installing Mayhem at the following link: https://www.moddb.com/mods/mayhem/tutorials/mayhem-3-how-to-install

Although Mayhem is completely different from Litcube's Universe (LU), it still benefits from its hardcoded commands, various fixes, and of course some features like the new ships. It is therefore mandatory to install it prior to Mayhem. It's highly recommended to install Mayhem on a fresh install to avoid any issues and make sure you can revert back to another mod or vanilla LU at any time. Keep in mind that it's not possible to uninstall Mayhem (you'd have to remove the whole folder). To start from a fresh install, follow these steps: 

1. Copy the whole "X3" folder into a new location. Make sure it's in English https://image.ibb.co/g8VWpR/X3_Mayhem_install01.png and that you don't have the Bonus Package installed (click "manage my DLC" on the right column of your X3:AP page, you may need to scroll down). If your copy is from Steam, use the no-steam exe file https://www.egosoft.com/download/x3ap/bonus_en.php 

2. Install Litcube's Universe, and patch it to 1.7.2 http://litcube.xtimelines.net/wiki/index.php/Download - don't forget the LU soundtrack and the GUI as well.

3. Copy Mayhem 3 - ie. the content of this archive - into your "...\X3" root folder and overwrite LU files. Do not copy into your "addon" folder.

4. Install the graphics pack https://www.moddb.com/mods/mayhem/downloads/mayhem-3-graphics2 into your "...\X3" folder. Do not copy into your "addon" folder. This pack is mandatory.

5. Start "Mayhem Galaxy Generator.exe" from your "...\X3" root folder. If you run into a problem while launching the Galaxy Generator, please deactivate your Antivirus.

6. All the controls you see are optionals. You can just click Generate to have a default galaxy, or use the Randomize button; or customize your next galaxy to your liking. When you're finished, click "Run" to launch the game with the galaxy you have selected.

7. Only use "Use the alternate soundtrack file" if you know what you're doing. It's supposed to go with this ambient soundtrack: https://www.moddb.com/mods/mayhem/downloads/mayhem-3-ambient-soundtrack and sectors will be silent if the music IDs are not there. Alternatively, you can use these IDs to copy your own music and have a different soundtrack for some of your galaxies.

Performance tip: set your Shaders quality to Low in the Graphics menu. It's a big ugly, and doesn't take custom colors into account, but FPS are greatly improved when lots of ships are on screen.

INSTALL FROM A PATCH
====================

There is no "patch" with Mayhem releases. It's always the full package, so the install is pretty straightforward:

1. Copy the content of the archive into your "...\X3" folder and overwrite all files. Do not copy into your "addon" folder.

2. Read the changelog: https://forum.egosoft.com/viewtopic.php?p=4540103#p4540103

Although not necessary, you can safely remove the "...\X3\addon\scripts" folder every time there's a new patch to ensure that the scripts that have been removed no longer exist. This "scripts" folder does always contain ALL the scripts you need (ie. vanilla, LU, and Mayhem, plus a modified version of the Cheat Package, by Cycrow).

If you have modified some gameplay values from the "t-file" (from "...\X3\addon\t\9972-L044.xml"), be aware that the new patch will overwrite any change with the default values.

PERMISSION
==========

You can do whatever you want with Mayhem 3 and all its files.

THANKS
======

Hector0x:  Master of Zero Hour and Mayhem 3 in general;  without whom, I would never have been able to create Renegades.
Icewave (Jack08): He knows the meaning of 42.
Litcube: I've never been a big fan of X3 vanilla. For me, LU was the real thing. http://litcube.xtimelines.net/wiki/index.php/Features
mr.bear: Designer of X-Studio. https://forum.egosoft.com/viewtopic.php?t=301433
XenonArchitect7: Models and feedback.
Darth Fiscus (Hector0x): Awesome video tutorials creator and precious feedback. https://www.youtube.com/playlist?list=PL4c4Ymq37GHTWnfAx9mQvtusQg87exbiM
Cycrow: Cheat package and help.
temetvince: Various fixes.

Thank you to the whole community!

TASKS (incomplete)
=====

201/202: Mayhem.Task.Station.Outpost, Mayhem.Task.Station.ResearchStation and Mayhem.Task.TradingStation
1221: Mayhem.Task.Expedition
1312: Mayhem.Task.ExploreScan
1313: Mayhem.Task.TemplateWhenReady
1314: Mayhem.Fleet.ProtectCarrier
1315: Mayhem.Fleet.Whip
1316: !move.undock
1317: !ship.cmd.attack.std (see Mayhem.Fleet.Attack)
2044: Mayhem.Task.Claimeable
1318: Mayhem.StallEngine
1319: Mayhem.Task.Defend.Watch
1320: Mayhem.Task.DefendObject.Follow
1321: Mayhem.Task.Jump
1322: Mayhem.Task.Station.Credits
1323: Mayhem.Task.Station.Destruction
1324: Mayhem.Task.Station.Autoassign
1325: Mayhem.Task.Station.MaxJumpsCheck
1326: Mayhem.Task.Station.Autopricing
1327: !fight.defend.monitor
1328: Mayhem.Task.CarrierRepair
1329: Mayhem.Task.OCVVirus
1330: Mayhem.Task.MarineMission
1331: Mayhem.Task.Station.Repair
203: Mayhem.Task.Station.PirateBase
1332: !fight.attack.object.stationTactics