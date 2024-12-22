**Delay Destroyer V2.0 Changelog**

Delay Destroyer V1.0 = 31KB & 742 lines of code. 
                        ^
Delay Destroyer V2.0 = 36KB & 783 lines of code.

*Added*
- Added Windows 11 Detection, If user is win 11 adds GlobalTimerRes reg.
- Added Auto Setting Windows Processes Priority.
- Added bcdedit /set useplatformtick No, lowers delta's by 0.0400ms or higher!
- Added Hex Conversions to Priority Separation.
- Added Ultimate Performance delete and removed High Performance delete.
- Added PlatformAoAcOverride reg could fix power plan import problems.
- Win 10 20H2 and above detection, if it's detected it applies the timeres 10 fix.
- Updated Power Plans they now have AWAYMODE, ALLOWSTANDBY, HYBRIDSLEEP, PROCTHROTTLEMIN, CPMINCORES and THROTTLING changes instead of disabling after.
- Made (Khorive, Inspired) NDIS Tweaks optional.
- Added Power Plan and VC Redist Delete. 

*Removed*
- Removed Windows Defender Detection.
- Removed bcdedit /set useplatformtick yes.
- Removed the 0.504ms Timer Res Recommendation, now 0.507ms.
- Removed the 22dec Priority Separation Recommendation, now 42dec.

*Fixed*
- Fixed Restore Point name.
- Fixed Grouping Svchost Processes, missing a ".
- Fixed 46 Decimal, it's actually supposed to 42 Decimal.
- Fixed Spelling of wifi devices.
- Optimized Device Manager code from 245 lines to 121.
- Changed the Visual C++ 2015-2022 Redistributable download link to offical source.
- Fixed Visual C++ 2015-2022 Redistributable being added to Oneclick Tools Folder.

---
