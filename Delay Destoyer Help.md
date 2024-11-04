1. Powerplan doesn't show up.

Open Cmd as admin and paste reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power" /v PlatformAoAcOverride /t REG_DWORD /d 0 /f then restart. The powerplans should be visable now!
