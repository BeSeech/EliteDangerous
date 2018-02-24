Foreword:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
All images contained within this Application are Property of Frontier Development 
plc. I take credit only for the implementation of the Manager. Graphics content 
is all property of Frontier, and I thank them for your efforts making this 
awesome game series.

EHM; What IS it?:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
The EHM (Elite HUD Manager) is an application that can generate random colour 
matrices for deployment in Elite Dangerous. This Application is optionally launched 
instead of Elite Dangerous, as it includes functions which open ED's launcher 
itself.

FEATURES:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- HUD generator with pre-game preview.
- HUD Presets. Just drop any HUD configurations you like into the EHMPresets 
folder, and make sure you save with the application in Preset Mode.
- The ability to save generated HUDs as Presets.
- Colour Range adjustments, with customisable Max/Min Intensity of each Colour in each Matrix.
- Silent Running, for launching straight into Elite Dangerous with random colours or presets 
each time you play.

- TODO: Allow Cyclic selection of Preset HUDs.

HOW TO USE:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Place EliteHUDManager.exe in Elite Dangerous' installation directory. 
(For Steam Users, this can be found by right clicking ED in your Steam Library 
> Properties > Local Files > Browse Local Files)
- Open EliteHUDManager.exe. If you are using Elite Dangerous through Steam, 
check the box "I am using Steam". If this is not checked, the Steam Overlay will 
be disabled when using this Application and loading ED through it. 
- You can specify the maximum and minimum ranges for each Matrix colour and row. 
- Pressing "Generate GraphicsConfigurationOverride.xml" will generate a colour
palette.
- If you'd like to save a palette as a Preset, press "Switch to Preset Mode",
then press "Save as Preset". A numbered .xml item will appear in the box to
the right. You can Rename these xml files whatever you'd like, as long as the
extension is unchanged.

Enabling Silent Running:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- IF YOU LAUNCH ED OUTSIDE OF STEAM, create a shortcut to EliteHUDManager.exe.
- Right Click the shortcut and select "Properties".
- In the Target Field, append " -s" to the end of the line, excluding quotes.
- Open the Shortcut; the randomiser will generate a HUD Config and launch the ED 
Loader.

- IF YOU LAUNCH ED WITHIN STEAM, Go to Games > Add a Non-Steam Game to my Library.
- Select "Browse..."
- Browse to ED's installation directory, then select EliteHUDManager.exe.
- Make sure EliteHUDManager is checked, then Add Selected Programs.
- Right Click EliteHUDManager in your Steam Library, then select "Properties".
- Press "Set Launch Options", and type "-s" excluding quotation marks.
- Launch Elite Dangerous via the EliteHUDManager Steam Library Entry.

UNINSTALLATION:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Delete the EHMPresets folder, EliteHUDManager.exe and EliteHUDManagerconfig.txt
- You're done. :D

KNOWN BUGS:~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Launching the application outside of ED's Installation Directory WILL result in 
problems. Since the program is useless outside of that directory anyway, I would 
recommend you refrain from doing so unless you like seeing crash reports.
- Launching the application with Config settings out of acceptable bounds WILL 
result in crashes. Users should refrain from modifying values in the Config file, 
as all controls are available within the Application.







