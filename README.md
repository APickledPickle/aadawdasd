Mono path[0] = 'C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Managed'
Mono config path = 'C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/MonoBleedingEdge/etc'
Initialize engine version: 2019.4.30f1 (e8c891080a1f)
[Subsystems] Discovering subsystems at path C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/UnitySubsystems
GfxDevice: creating device client; threaded=1
Direct3D:
    Version:  Direct3D 11.0 [level 11.1]
    Renderer: Intel(R) HD Graphics 520 (ID=0x1916)
    Vendor:   
    VRAM:     1996 MB
    Driver:   31.0.101.2111
Begin MonoManager ReloadAssembly
- Completed reload, in  0.211 seconds
<RI> Initializing input.

<RI> Input initialized.

<RI> Initialized touch support.

UnloadTime: 1.290700 ms
RimWorld 1.4.3704 rev896
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013A22000080.dll
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013BFE637780.dll
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013BFE75D010.dll
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013A220E3890.dll
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013BFDF11120.dll
Fallback handler could not load library C:/Users/LocalAdmin/Documents/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorld.v1.4.3704.Incl.ALL.DLC/RimWorldWin64_Data/Mono/data-0000013A225470A0.dll
Checking Multiplayer Compat
Combat Extended :: Checking Vehicle Framework
Combat Extended :: Checking Misc Turrets
Combat Extended :: Checking Better Turrets
Combat Extended :: Harmony_GenRadial_RadialPatternCount :: Info: Post GenRadial patch maximum radius: 119.4194
Combat Extended :: initialized
Error in ParallelFor(): System.IO.DirectoryNotFoundException: Could not find a part of the path "C:\Users\LocalAdmin\Documents\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\Mods\2890901044\Patches\Frontline Collection\Frontline - Additional Guns For Trenches\FrontlineAdditionalGunsForTrenches_GA_TRLMGII.xml"
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.Boolean anonymous, System.IO.FileOptions options) [0x0019e] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.IO.FileOptions options, System.String msgPath, System.Boolean bFromProxy, System.Boolean useLongPath, System.Boolean checkHost) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.FileStream..ctor(string,System.IO.FileMode,System.IO.FileAccess,System.IO.FileShare,int,System.IO.FileOptions,string,bool,bool,bool)
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize, System.Boolean checkHost) [0x00067] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Boolean detectEncodingFromByteOrderMarks) [0x0000d] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.StreamReader..ctor(string)
  at System.IO.File.ReadAllText (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at Verse.DirectXmlLoader+<>c__DisplayClass1_0.<XmlAssetsInModFolder>b__0 (System.Int32 i) [0x00024] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GenThreading+<>c__DisplayClass8_1.<ParallelFor>b__0 (System.Object _) [0x0000f] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Error in ParallelFor(): System.IO.DirectoryNotFoundException: Could not find a part of the path "C:\Users\LocalAdmin\Documents\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\Mods\2890901044\Patches\Frontline Collection\Frontline - Additional Guns For Trenches\FrontlineAdditionalGunsForTrenches_HA_TRMMGII.xml"
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.Boolean anonymous, System.IO.FileOptions options) [0x0019e] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.IO.FileOptions options, System.String msgPath, System.Boolean bFromProxy, System.Boolean useLongPath, System.Boolean checkHost) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.FileStream..ctor(string,System.IO.FileMode,System.IO.FileAccess,System.IO.FileShare,int,System.IO.FileOptions,string,bool,bool,bool)
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize, System.Boolean checkHost) [0x00067] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Boolean detectEncodingFromByteOrderMarks) [0x0000d] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.StreamReader..ctor(string)
  at System.IO.File.ReadAllText (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at Verse.DirectXmlLoader+<>c__DisplayClass1_0.<XmlAssetsInModFolder>b__0 (System.Int32 i) [0x00024] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GenThreading+<>c__DisplayClass8_1.<ParallelFor>b__0 (System.Object _) [0x0000f] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Error in ParallelFor(): System.IO.DirectoryNotFoundException: Could not find a part of the path "C:\Users\LocalAdmin\Documents\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\Mods\2890901044\Patches\Frontline Collection\Frontline - Additional Guns For Trenches\FrontlineAdditionalGunsForTrenches_IA_TRHMGII.xml"
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.Boolean anonymous, System.IO.FileOptions options) [0x0019e] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.IO.FileOptions options, System.String msgPath, System.Boolean bFromProxy, System.Boolean useLongPath, System.Boolean checkHost) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.FileStream..ctor(string,System.IO.FileMode,System.IO.FileAccess,System.IO.FileShare,int,System.IO.FileOptions,string,bool,bool,bool)
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize, System.Boolean checkHost) [0x00067] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Boolean detectEncodingFromByteOrderMarks) [0x0000d] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.StreamReader..ctor(string)
  at System.IO.File.ReadAllText (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at Verse.DirectXmlLoader+<>c__DisplayClass1_0.<XmlAssetsInModFolder>b__0 (System.Int32 i) [0x00024] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GenThreading+<>c__DisplayClass8_1.<ParallelFor>b__0 (System.Object _) [0x0000f] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Error in ParallelFor(): System.IO.DirectoryNotFoundException: Could not find a part of the path "C:\Users\LocalAdmin\Documents\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\RimWorld.v1.4.3704.Incl.ALL.DLC\Mods\2890901044\Patches\Biotech Mech Stuff Elongated - Mechanoid Upgrades V2\Booster_HeavyUltraHeavy\HeavyUltraHeavy_EMPResistance.xml"
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.Boolean anonymous, System.IO.FileOptions options) [0x0019e] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.FileStream..ctor (System.String path, System.IO.FileMode mode, System.IO.FileAccess access, System.IO.FileShare share, System.Int32 bufferSize, System.IO.FileOptions options, System.String msgPath, System.Boolean bFromProxy, System.Boolean useLongPath, System.Boolean checkHost) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.FileStream..ctor(string,System.IO.FileMode,System.IO.FileAccess,System.IO.FileShare,int,System.IO.FileOptions,string,bool,bool,bool)
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize, System.Boolean checkHost) [0x00067] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Text.Encoding encoding, System.Boolean detectEncodingFromByteOrderMarks, System.Int32 bufferSize) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path, System.Boolean detectEncodingFromByteOrderMarks) [0x0000d] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at System.IO.StreamReader..ctor (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at (wrapper remoting-invoke-with-check) System.IO.StreamReader..ctor(string)
  at System.IO.File.ReadAllText (System.String path) [0x00000] in <eae584ce26bc40229c1b1aa476bfa589>:0 
  at Verse.DirectXmlLoader+<>c__DisplayClass1_0.<XmlAssetsInModFolder>b__0 (System.Int32 i) [0x00024] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GenThreading+<>c__DisplayClass8_1.<ParallelFor>b__0 (System.Object _) [0x0000f] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Exception from asynchronous event: System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ModContentPack.LoadPatches () [0x0003c] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.ModContentPack.get_Patches () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LoadedModManager.ErrorCheckPatches () [0x00018] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LoadedModManager.LoadAllActiveMods () [0x000bf] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.PlayDataLoader.DoPlayLoad () [0x00026] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.PlayDataLoader.LoadAllPlayData (System.Boolean recovering) [0x0002e] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root+<>c.<Start>b__6_1 () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.RunEventFromAnotherThread (System.Action action) [0x00008] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

No active language! Cannot translate from key InitializingInterface. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Tried to use an uninitialized DefOf of type ExpansionDefOf. DefOfs are initialized right after all defs all loaded. Uninitialized DefOfs will return only nulls. (hint: don't use DefOfs as default field values in Defs, try to resolve them in ResolveReferences() instead) 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Exception from long event: System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MainMenuDrawer.Init () [0x00075] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.Init () [0x00010] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.<Start>b__6_0 () [0x0004a] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.UpdateCurrentSynchronousEvent (System.Boolean& sceneChanged) [0x0001d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

No active language! Cannot translate from key CE_LongEvent_LoadoutProperties. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

No active language! Cannot translate from key CE_LongEvent_AmmoInjector. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

CE Ammo Injector found no weapon defs 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Combat Extended :: Ammo injected
No active language! Cannot translate from key CE_LongEvent_BoundingBoxes. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Combat Extended :: Bounds pre-generated
No active language! Cannot translate from key CE_LongEvent_BoundingBoxes. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

No active language! Cannot translate from key CE_LongEvent_CompatibilityPatches. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.DivideByZeroException: Attempted to divide by zero.
  at Verse.GameplayTipWindow.DrawContents (UnityEngine.Rect rect) [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.GameplayTipWindow.DrawWindow (UnityEngine.Vector2 offset, System.Boolean useWindowStack) [0x000b5] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.LongEventHandler.LongEventsOnGUI () [0x001e7] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x00019] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Checking Multiplayer Compat
Combat Extended :: Checking Vehicle Framework
Combat Extended :: Checking Misc Turrets
Combat Extended :: Checking Better Turrets
Tried to use an uninitialized DefOf of type KeyBindingDefOf. DefOfs are initialized right after all defs all loaded. Uninitialized DefOfs will return only nulls. (hint: don't use DefOfs as default field values in Defs, try to resolve them in ResolveReferences() instead) 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Tried to use an uninitialized DefOf of type SongDefOf. DefOfs are initialized right after all defs all loaded. Uninitialized DefOfs will return only nulls. (hint: don't use DefOfs as default field values in Defs, try to resolve them in ResolveReferences() instead) 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.StartPlaying () [0x000a0] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x0001b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Alignment was MiddleCenter at end of frame. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Tried to use an uninitialized DefOf of type SoundDefOf. DefOfs are initialized right after all defs all loaded. Uninitialized DefOfs will return only nulls. (hint: don't use DefOfs as default field values in Defs, try to resolve them in ResolveReferences() instead) 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.ScreenshotTaker.Update () [0x00008] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootUpdate () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.Update () [0x0004e] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in Update(): System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.MusicManagerEntry.get_CurSanitizedVolume () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.MusicManagerEntry.MusicManagerEntryUpdate () [0x00021] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root_Entry.Update () [0x00017] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Reached max messages limit. Stopping logging to avoid spam. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Root level exception in OnGUI(): System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.DebugWindowsOpener.DevToolStarterOnGUI () [0x00099] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot.UIRootOnGUI () [0x0003b] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.UIRoot_Entry.UIRootOnGUI () [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at Verse.Root.OnGUI () [0x0003d] in <95de19971c5d40878d8742747904cdcd>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

