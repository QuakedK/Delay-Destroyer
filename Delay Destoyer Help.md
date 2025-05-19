1. Powerplan doesn't show up.

Open Cmd as admin and paste reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power" /v PlatformAoAcOverride /t REG_DWORD /d 0 /f then restart. The powerplans should be visable now!

___

2. DPC  Checker not running on start up. (Unknown Issue)

Download [Start DPC Checker Delay Destroyer Ver](https://github.com/QuakedK/Downloads/blob/main/Start%20DPC%20Checker%20Delay%20Destroyer%20Ver.bat) and then click Winkey + R = Shell:startup and drag the newly download bat into the folder, then restart!

Tired of the UAC prompt? Open CMD and paste reg add "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System" /f /v EnableLUA /t REG_DWORD /d 0 then restart.

Don't want to disable UAC? Use [BatToEXEPortable](https://github.com/Makazzz/BatToExePortable) and convert the Start DPC Checker.bat to an exe and drag it into the Shell:startup folder then right click > Properties > Compatibility and then check "Run this program as an Administrator"

(Unknown Issue) Unsure why some systems have DPC Checker open fine via the registry and other's don't.
___
