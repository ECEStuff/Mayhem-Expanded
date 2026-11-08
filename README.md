# Mayhem Expanded

Mayhem Expanded is an expansion of Renegades, built upon Mayhem 3 Zero Hour and the original Mayhem 3. It includes Azimuth, a map generator for creating and customizing galaxies.

## Downloads and support

- [Download Mayhem Expanded on ModDB](https://www.moddb.com/mods/mayhem-expanded)
- [Azimuth source code and standalone releases](https://github.com/ECEStuff/Azimuth_Mayhem_MapGen)
- [Discussion and support on the Egosoft forums](https://forum.egosoft.com/viewtopic.php?t=473331)
- [Mayhem Expanded discussion and support — SWLU Discord](https://discord.com/invite/S587CRb)

**Read the changelog included with your release before installing or updating.** It contains compatibility requirements, gameplay changes, and any additional migration steps.

## Before installing

**Mayhem Expanded 2.2 requires both a new game and a new galaxy generated with Azimuth. Existing saves and previously generated galaxies are not compatible.**

For a fresh installation, you need:

- A clean English installation of **X3: Albion Prelude**, without the Bonus Package.
- The **Mayhem Expanded release package** from ModDB.

Install into a separate copy of the game, outside `Program Files` and `Program Files (x86)`. Back up any existing installation, saves, and customized configuration files before making changes.

## Fresh installation

### 1. Prepare the game directory

Copy a clean X3: Albion Prelude installation to a separate folder, such as `C:\Games\Mayhem_Expanded`.

This is your **Expanded directory**, also called the **game root**. It contains `X3AP.exe` and the `addon` folder.

**Steam users:**

- Set the game language to English before copying the installation.
- Do not install the Bonus Package; it is incompatible with Mayhem 3.
- Register your game with Egosoft and download the [no-Steam executable](https://www.egosoft.com/download/x3ap/bonus_en.php).
- Replace `X3AP.exe` in your Expanded directory with the no-Steam executable.
- See [Egosoft's Steam registration instructions](https://www.egosoft.com/support/faq/faq_answer_en.php?answer=2110&version=0) if needed.

**GOG users:**

- Use an English installation without the Bonus Package.
- Keep the supplied `X3AP.exe`; no replacement is required.

### 2. Install Mayhem Expanded

Download the latest Expanded release package from [ModDB](https://www.moddb.com/mods/mayhem-expanded). It includes the required Renegades files; no separate Renegades download or installation is needed.

Open the archive and locate the folder containing `addon`, `mayhem_data`, `cleanup.bat`, and the other release files.

Extract those contents directly into your Expanded directory, allowing files to be overwritten. The package's `addon` folder must merge with the existing `addon` folder; do not create an extra nested installation folder.

Run the included `cleanup.bat` from your Expanded directory to remove obsolete files.

### 3. Generate and activate a galaxy with Azimuth

Use the version of Azimuth included with the Expanded release. Launch `Azimuth.exe`, then:

1. Set **Mayhem Root Folder** to your Expanded directory.
2. Set **Mayhem Save Game Folder** to your X3: Albion Prelude save folder.
3. Choose your galaxy settings.
4. Click **Generate Sectors**.
5. Open **Save/Load Galaxy**, enter a name, and save the galaxy.
6. Select the saved galaxy and click **Set Active**.

**Saving a galaxy does not activate it.** Set Active copies the selected galaxy's files into your Expanded directory so the game can use them.

The root `GalaxySettings.json` is created or replaced during activation. You do not need to create it manually.

### 4. Optional customization

Before starting a new game:

- Use **Ships and Weapons** in Azimuth to randomize ship and weapon attributes.
- Use the **Config** menu to review supported game settings.
- Use the **Help** menu for Azimuth's user guide, release notes, and About information.

Configuration files can also be edited manually:

- `addon\t\9972-L044.xml`
- `addon\t\9973-L044.xml`

Follow the comments in those files. Some settings apply only during initialization or become locked after the starting questions. Later edits to locked settings do not change an existing campaign.

### 5. Launch Expanded

Run `X3AP.exe` from your Expanded directory.

Check that the selected galaxy's name appears in the bottom-right corner of the main menu, then start a new game.

If the name is missing or incorrect, check Azimuth's game-root path and confirm that you used **Set Active**, rather than only saving the galaxy.

## Updating an existing installation

These instructions apply when upgrading Renegades 5.4 to Expanded or updating an existing Expanded installation.

1. Read the new release's changelog. Check whether it requires a new game, a new galaxy, or other migration steps.
2. Back up your installation, saves, and customized configuration files.
3. Download the latest Expanded release package from [ModDB](https://www.moddb.com/mods/mayhem-expanded).
4. Extract its contents into your existing Expanded directory, allowing files to be overwritten.
5. Follow any additional instructions in the changelog.

If a new galaxy is required: generate, save, and activate one with the included version of Azimuth before starting a new game.

Do not restore old configuration files wholesale. Compare them with the updated files and reapply only supported changes.

Do not routinely reactivate an old galaxy or restore old ship and weapon overrides after updating. These actions can overwrite files supplied by the new release. Follow the release's migration instructions first.

Azimuth replaces ZMap in this workflow. The old instructions for copying `TShips.txt` and `TBullets.txt` into a separately installed ZMap folder no longer apply.

## Help and bug reports

Use Azimuth's **Help** menu for generator instructions and the in-game encyclopedia for gameplay information. Consult the release changelog for changed rules and known issues.

For discussion and support, visit the [Egosoft forum thread](https://forum.egosoft.com/viewtopic.php?t=473331) or the [SWLU Discord server](https://discord.com/invite/S587CRb). On Discord, use the appropriate Mayhem channel.

When reporting a problem, include:

- Your Expanded version and, for generator issues, your Azimuth version.
- Whether the issue occurs in a fresh installation or after an update.
- The steps needed to reproduce it.
- The exact error message, relevant log output, and screenshots where useful.
- Relevant galaxy settings and any additional mods or customizations.

## Localization

Expanded's installation instructions assume English game files.

[Russian localization by Alexalsp](https://github.com/alexalsp2/Renegades_AddOns_russian) is available separately, but is outdated and may not match the current release. Do not assume it is compatible with Expanded 2.2.

## Versioning policy

- **Major releases** (`X.0`, such as `2.0`) introduce substantial changes and require a new game.
- **Minor releases** (`X.Y`, such as `2.2`) may change persistent world behavior and may require a new game.
- **Patch releases** (`X.Y.Z`, such as `2.1.2`) are safe to install mid-save.
- **Hotfix revisions** (`X.Y.Za`, such as `2.1.2a`) contain small corrections and are safe to install mid-save unless otherwise noted.

Always check the release changelog for specific savegame and galaxy compatibility requirements.

## Credits

### Mayhem and its expansions

- **Egosoft** — X3: Albion Prelude and the underlying game.
- **Litcube** — Litcube's Universe, upon which Mayhem was built.
- **Joubarbe** — The original Mayhem series, Mayhem 3, and the original Mayhem galaxy generator.
- **Hector0x** — Mayhem 3 Zero Hour.
- **Mordan (Hairless-Ape)** — Mayhem 3 Renegades, ZMap, and credited contributions ported from Mayhem FoF.

### Localization and assets

- **XenonArchitect7** — Tips and Flail Barrage Missile icon.
- **Cycrow** — X3AP documentation and QnA.
- **Alexalsp** — Russian localization work.
- **Solek** — Asteroid textures used in Expanded.
- [Sector Names icon by Cap Cool](https://www.flaticon.com/free-icons/text-box).
- [Constellation app icon by Magnific](https://www.flaticon.com/free-icons/constellation).
- **XTC for X3TC/AP** — Goner TS/TP ship models.

Thank you to everyone who contributed testing, bug reports, feedback, and suggestions. Additional asset and script credits remain in the included documentation and source files.

## Licenses and notices

Consult the license and attribution notices included with each component before redistributing or modifying it. Azimuth's licensing terms do not automatically apply to Expanded, inherited code, or third-party assets.

Mayhem Expanded is an unofficial fan project. It is not affiliated with, endorsed, or supported by Egosoft. Egosoft does not provide technical support for this project. Use at your own risk.

Names, trademarks, and game content associated with X3: Albion Prelude belong to Egosoft or their respective owners. See [Egosoft's fan content policy](https://www.egosoft.com/community/fanpolicy_en.php).
