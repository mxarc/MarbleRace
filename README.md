# MarbleRace
Marble Race - Giveaway System

# v1.1.1 _(04 Febr 2017)_
## -=NEW=-
- data Folder no longer saves in Application_Data folder. Instead, files will be saved in AppData/MarbleRace/data to keep resources through different versions

## -=EXTRA=-
- Folder "DefaultSprites". Contains 3 sprites for PixelsRealm, Thycon and Mstiekema. Copy to your Sprites folder to make them work. (Default: %AppData%/MarbleRace/data/sprites/)

# v1.1.0 _(04 Febr 2017)_
## -=NEW=-
- Leaderboard increased in width (Names no longer get wrapped and fit in the entire Panel)
- Names in Leaderboard have a drop shadow (Increased readability)
- Leaderboard Save Format can now be set in Config
- Added Sprite System for Custom Colored Marbles. 
    * Supports .JPEG, .JPG and .PNG. 
    * Preferred Image Ratio: 1:1. 
    * Minimum Resolution for Optimal Quality: 128*128px. 
    * Capitals not important

## -=FIXES=-
- Minor Bugs in Controls and Config save/load scripts

# v1.0.5 _(28 Dec 2017)_
## -=NEW=-
- Leaderboard now has colored text. Colors correspond with the color of the user's marble.
- Leaderboard automatically saves when the winner has touched the Finish.

## -=FIXES=-
- Bottom Part of Race 1 was fixed (Marbles no longer get stuck)

# v1.0.4 _(17 Dec 2017)_
## -=NEW=-
- Added Menu Screen
- Added Race Select Screen
- Added Race Edit Screen (Empty)
- Added Settings Screen
- Added Controls Screen
- Added Config Screen
- Added Quit Button in menu
- Controls are now changed within the App (Don't use "Input" tab when starting app)
- Ability to configure paths and webpage to get users from
- Added Back button in Race to go back to Menu (will reset race)
- Autosave of entered users
- Ability to Save leaderboard (Save button in race)

## -=FIXES=-
- Camera can't go through Race anymore
- Start can no longer be triggered before giveaway is closed

## -=KNOWN BUGS=-
- "Add Marble Delay" slider text values do not show correctly when loading the Config screen, 
    even though the value of the slider itself is correct.
- Bottom Lane of Bottom part has a straight bit where marbles get stuck.

# v1.0.3 _(30 Oct 2017)_
## -=NEW=-
- Application now runs in background
- GUI element lets user know if giveaway hasn't been closed

## -=FIXES=-
- Elements that are partly inside background bumped back a pixel, so it is behind background color
- Added wheel from v1.0.1 wasn't placed correctly. Shifted it to better location

# v1.0.2 _(27 Oct 2017)_
## -=NEW=-
- Added 60 FPS target

# v1.0.1 _(27 Oct 2017)_
## -=FIXES=-
- Added wheel at the beginning, bottom lane, to prevent queue

# _TO DO_
- Add More Races
- Add Course editing
- Add System for Knockout-Race
- Options: !gstop triggers start
- Options: Enable/Disable countdown
