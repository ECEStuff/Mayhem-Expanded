Azimuth localization

English is the default. Switch at any time using
Help > Language > English / Русский.

The main window translates immediately without a restart or galaxy reset.
Open modal dialogs (Save/Load, Config, Sector Editor, Ships and Weapons)
finish before returning to Help > Language; newly opened dialogs use the
selected language.

Your preference is saved per Azimuth installation in Settings.txt as
UiLanguage|44 or UiLanguage|07 and restored at the next launch.

Localizations.json supplies optional English overrides and remains the
English release catalog. Localizations/Localizations_Russian07.json
supplies Russian translations; missing keys fall back to English.
The configuration editor uses ConfigDefaults/SettingNames_07.json when
the UI is Russian. HelpMain_07.txt and ReleaseNotes_07.txt are used in
that language, too.

Important: Azimuth's UI language is independent of the X3 language used
for generated addon/t and addon/mov resource files. The game-file language
is preserved from the launch-time installation configuration. Changing
UI languages does not rename or change galaxy resource files.

Older installations that copied the Russian catalog over
Localizations.json are recognized until a UI preference is saved.
After switching to English, restore the shipped English Localizations.json
when convenient to keep files consistent.

Russian translator: alexalsp. Preserve the translation attribution.
