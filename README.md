Download and install AutoHotKey --> https://github.com/AutoHotkey/AutoHotkey/releases
Download and move the file "ScreenSaverHotKeyV2.ahk" to your 'Documents' folder
Open Task Scheduler on and follow through with "Create Basic Task"
  -Give it a Name and Description
  -Set it to start "When I log on"
  -Choose "Start a program"
  -In "Program/script" field, use "browse" to find your AutoHotKey.exe    e.g. --> "C:\Program Files\AutoHotkey\v2\AutoHotkey64.exe"
  -In "Add arguments (optional)" field, add the file path for where you moved the ".ahk" file to    e.g. --> "C:\Users\kdsam\Documents\#AutoHotkey\ScreenSaverHotKey (INS and SCR LCK).ahk"
  -Hit Finish after progressing through the last step
  -Find the task you just created in the list, right click the task and open "Properties"
  -In the "General" tab, make sure "Run with the highest privileges" is checked marked, or else "Smart App Control" might block the script.
  -In the "Triggers" tab, make sure it is set to "Any User", and only the "Enabled" checkbox at the bottom is marked. Every other box in between is left unmarked. No need to delay the task.
Make sure all settings are saved and you're now ready to restart your PC, to check if the program and script are appropriately opening at startup
You can now open your gamepad manager (Xbox Accessories, Steam Controller settings, etc.) and bind the "INS" key and "SCR LCK" key to your gamepad to be able to activate and exit the Windows Mystify screensaver on command.

Hope these instructions help! Feel free to reach out for more guidance/assistance.

This effort was put together to help protect my OLED Screens if I needed to step away. Now instead of digging through menus in Windows or LG's laggy mess of a UI, we can now throw on a screensaver at the press of a button, quickly and consistently.
  
