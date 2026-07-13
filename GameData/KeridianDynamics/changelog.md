# Changelog  
  
| modName    | Keridian Dynamics (KDVA) by Eleusis La Arwall                     |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0+ARR                                                  |
| author     | Eleusis La Arwall, zer0Kerbal, and Jaheay                          |
| forum      | (<https://forum.kerbalspaceprogram.com/index.php?/topic/202945-*/>) |
| github     | (<https://github.com/zer0Kerbal/zer0Kerbal/KeridianDynamics>)       |
| curseforge | (<https://www.curseforge.com/kerbal/ksp-mods/KeridianDynamics>)     |
| spacedock  | (<https://spacedock.info/mod/308>)                                  |
| ckan       | KeridianDynamicsVesselAssembly                                    |

* 📌 Pinned
  * Dependencies (can be useful without, but very limited):
    * Either [SimpleConstruction! (SCON)](https://www.curseforge.com/kerbal/ksp-mods/SimpleConstruction) or [Extraplanetary Launchpads (XPL)](https://forum.kerbalspaceprogram.com/index.php?/topic/54284-*/)
    * [ModularManagement (MM)](https://www.curseforge.com/kerbal/ksp-mods/ModularManagement) or [Module Manager](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/)
  * search `kd`, `kdva` in editors
  * ghostparts.cfg has been updated and temporarily added for 3D Printer

## 0.8.99.8 - Cleanup and Modernization

### Changes 0.8.99.8

#### Parts and balance 0.8.99.8

* Rebalanced construction, launch, workshop, refinery, and recycling hardware
* Updated crew capacities and selected part masses
* Added stock inventory and ground placement support for portable launch and recycle sites when KIS is absent
* Removed Stock SCON part additions when used with KD.
* Fixed SCON Ratios which previously had a 1% Ore-> Metal Ratio created 5x mass when converting metal to rocket parts.

#### Station and cargo tanks 0.8.99.8

* Consolidated matching ST and T tanks when B9 Part Switch is installed
* Updated B9 tank volumes and added Community Resource Pack `MetallicOre` storage
* Categorized station and cargo tanks consistently under Payload

#### Compatibility 0.8.99.8

* Moved conditional B9 and Not So SimpleConstruction behavior into the mod's Compatibility layer
* Hid duplicate Not So SimpleConstruction launchpad, recycler, auger, stake, and mallet parts
* Updated KIS integration so portable site parts remain usable without KIS
* Updated `KD-NoCargoTanks` for consolidated cargo variants
* Updated `KD-NoStationTanks` to restore legacy cargo tanks when station tanks are disabled

#### Localization and cleanup 0.8.99.8

* Reworked English part names, descriptions, converter actions, and legacy-part labels
* Removed the Ore Sample experiment and stock drill science module

---

## Version 0.8.99.7-prerelease - `<#8 Please Read the Instructions>` edition

* Released
  * 17 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 0.8.99.7

* 49/49 parts have undergone initial modernization
* mostly the patches are what are needing to be modernized
* Corrected the illogical logic in the SimpleConstruction! (SCON) patch
* Misplaced excitement, removed `!` from where it shouldn't be
* Crew no longer are incorporeal and now cannot pass through solid tanks at will
* English, Simplified Chinese, and Taiwanese localization files
  * Update and synchronize
  * Add additional strings for upcoming parts
  * custom science experiment now can be localized
* remove extraneous and superfluous resource definitions
* loads of behind the scenes changes

### Changes 0.8.99.7

#### Compatibility 0.8.99.7

* Update
  * [CommunityTechTree.cfg] v1.1.1.0
  * [ConnectedLivingSpace.cfg] v1.2.1.0
    * Crew no longer are incorporeal and now cannot pass through solid tanks at will
  * [Converters.cfg] v1.0.0.0
  * [DrillScience.cfg] v1.1.1.0
  * [ExtraplanetaryLaunchpads.cfg] v1.1.1.0
  * [FuelSwitchNew.cfg] v1.1.0.0
  * [JSIAdvTransparentPods.cfg] v1.1.0.0
  * [KAS.cfg] v1.1.0.0
  * [KerbalInventorySystemcfg] v1.1.0.0
  * [OSEWorkshop.cfg] v1.1.0.0
  * [SimpleConstruction.cfg] v1.1.0.0
    * Corrected the illogical logic in the SimpleConstruction! (SCON) patch
    * Misplaced excitement, removed `!` from where it shouldn't be
    * thank you to [x13x54](https://github.com/x13x54)
* closes #81 - [Bug 🐞]: Does not work with SimpleConstruction (W workaround!)
* updates #80 - Compatibility patches

#### Config 0.8.99.7

* Update
  * [ghostparts.cfg] v1.1.0.0
  * [KeridianDynamics.cfg] v1.0.3.0

#### Resources 0.8.99.7

* Update
  * [ScienceDefs.cfg] v0.8.99.7
    * localize
  * [ResourcesGeneric.cfg] v0.8.99.7
    * remove extraneous and superfluous definitions

#### Localization 0.8.99.7

* Add
  * Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
* English, Simplified Chinese, and Taiwanese localization files
  * Add additional strings for upcoming parts
  * Update and synchronize
  * [en-us.cfg] v1.2.0.0
  * [zh-cn.cfg] v1.2.0.0 (missing localizations)
  * [zh-tw.cfg] v1.2.0.0 (missing localizations)
* updates #15 - Localization - Master
* updates #16 - English <us-en.cfg>
* updates #24 - Simplified Chinese (简体中文) <zh-cn.cfg>
* updates #31 - Taiwanese (国语) <zh-tw.cfg>

#### Documentation 0.8.99.7

* Update
  * [_config.yml] v1.0.7.0
  * [404.md] v1.0.7.0
  * [Attribution.md] v1.0.7.0
  * [changelog.md] v1.0.7.0
  * [index.md] v1.0.7.0
  * [LegalMumboJumbo.md] v1.0.7.0
  * [Localizations.md] v1.0.7.0
  * [ManualInstallation.md] v1.0.7.0
  * [Marketing.md] v1.0.7.0
  * [Notices.md] v1.0.7.0
  * [PartsCatalog.md] v1.0.7.0
  * [readme.md] v0.8.99.7
  * [ReleaseLayout.md] v0.8.99.7
* Add
  * [FAKQ.md] v1.0.0.0
  * [Flags.md] v1.0.0.0
  * [Why.md] v1.0.0.0

### Status 0.8.99.7

* Issues
  * closes #77 - Keridian Dynamics (KDVA) 0.8.99.7-prerelease `<#8 Please Read the Instructions>` edition
  * closes #78 - 0.8.99.7 Additional Tasks
  * updates #79 - Part costs need to be evaluated and adjusted generally up

---

## Version 0.8.99.6-prerelease - `<#7 Please Read the Instructions>` edition

* Released
  * 13 Jan 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 0.8.99.6

* This is next in a series of updates with each (pre)release updating some of the forty-nine (49) parts and numerous patches. This allows for updating in manageable way.
* loads of behind the scenes changes
* some tags were playing hide and seek and have been found and now are 'it'
* updated
  * agent
* Updated parts
  * kd-fabricationcontainer.cfg
  * kd-fava
  * kd-Furnace.cfg
  * kd-LaunchPadSide.cfg
  * kd-Keronica.cfg
  * kd-LaunchPad.cfg
  * kd-LaunchPadSide.cfg
  * kd-LaunchPadTop.cfg
  * kd-LaunchSite.cfg
  * kd-orbital-hangar.cfg
  * kd-pad.cfg
  * kd-pam-small.cfg
  * kd-PAM.cfg
  * kd-RecycleSite.cfg
  * kd-recycler-small.cfg
  * kd-recycler.cfg
  * kd-SIMPLEXColonies-OASIS.cfg
  * kd-vab-mobile.cfg
* Can search `kd`, `kdva` in editors
* ghostparts.cfg has been updated and temporarily added for renamed parts

### Changes 0.8.99.6

* some tags were playing hide and seek and have been found and now are 'it'
* updated
  * agent
* parts updated
  * kd-fabricationcontainer.cfg v1.1.1.0
  * kd-fava v1.1.1.0
  * kd-Furnace.cfg v1.1.1.0
  * kd-LaunchPadSide.cfg v1.1.1.0
  * kd-Keronica.cfg v1.1.1.0
  * kd-LaunchPad.cfg v1.1.1.0
  * kd-LaunchPadSide.cfg v1.1.1.0
  * kd-LaunchPadTop.cfg v1.1.1.0
  * kd-LaunchSite.cfg v1.1.1.0
  * kd-orbital-hangar.cfg v1.1.1.0
  * kd-pad.cfg v1.1.1.0
  * kd-pam-small.cfg v1.1.1.0
  * kd-PAM.cfg v1.1.1.0
  * kd-RecycleSite.cfg v1.1.1.0
  * kd-recycler-small.cfg v1.1.1.0
  * kd-recycler.cfg v1.1.1.0
  * kd-SIMPLEXColonies-OASIS.cfg v1.0.1.0
  * kd-vab-mobile.cfg v1.1.1.0
* updates #15 - Localization - Master

### Status 0.8.99.6

* Issues
  * closes #60 - [compatibility] TETRIX  tech tree
  * closes #73 - Keridian Dynamics (KDVA) 0.8.99.6-prerelease `<#7 Please Read the Instructions>` edition
  * closes #74 - 0.8.99.6 Additional Tasks

---

## Version 0.8.99.5-prerelease - `<#6 Please Read the Instructions>` edition

* Released
  * 12 Dec 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 0.8.99.5

* This is next in a series of updates with each (pre)release updating some of the forty-nine (49) parts and numerous patches. This allows for updating in manageable way.
* loads of behind the scenes changes
* fixed texture not found log spam
* corrected some part tags having a double `=` instead of `= //`
* added
  * agent
  * many new flags
* Updated parts
  * kd-pad-extension
  * kd-pad
* Can search `kd`, `kdva` in editors
* ghostparts.cfg has been updated and temporarily added for renamed parts

### Changes 0.8.99.5

* fixed texture not found log spam
  * texture files where present, just not the correct encoding
* corrected tags (had a double = instead of = //)
* loads of behind the scenes changes
* convert from .png --> .dds
* Added
  * <Agents.cfg> v1.0.0.0
  * New Flags
* Updated
  * <kd-pad.cfg> v1.1.0.0
  * <kd-pad-extension.cfg> v1.1.0.0
  * <ConnectedLivingSpace.cfg> v1.2.0.0
  * <en-us.cfg> v1.1.5.0

### Status 0.8.99.5

* Issues
  * closes #69 - Keridian Dynamics (KDVA) 0.8.99.5-prerelease `<#6 Please Read the Instructions>` edition
  * closes #70 - 0.8.99.5 Additional Tasks
  * closes #59 - SimplexColonies
  * closes #65 - [Bug 🐞]: Log Spam - textures not found

---

## Version 0.8.99.4-prerelease - `<#5 Please Read the Instructions>` edition

### Summary 0.8.99.4

* Found hiding textures for passable tanks
* lots of linting and reorganizing
* Parts Catalog now has images
* Can now search for `kd` or `kdva` in the editor search bar to find all Keridian Dynamics parts.

### Changes

* Passable tanks missing texture
  * Thank you to reddit user [u/Galxemo](https://www.reddit.com/u/Galxemo/)
  * passable tanks were playing hide and go seek with a texture; now in same folder
  * closes #66 - [Bug 🐞]: passable tanks missing texture
* <en-us.cfg> v1.1.4.0
  * eliminated many duplicated strings
* KSP.log is reporting missing textures (28x each)
  * <KD-OrbitalHangar_IVALight.dds>
  * <KD-OrbitalHangar_IVALight_EMM.dds>
  * updates #65 - [Bug 🐞]: Log Spam - textures not found
* Eliminated duplicated textures
  * saves ~5.32mb
  * <KD-FurnaceSmall_EMM.dds> 1.33mb
  * <KD-FurnaceSmall_NRM.dds> 1.33mb
  * <KD-FurnaceSmall.dds> 1.33mb
  * <KD-FurnaceSmall.mu> 1.33mb
* Experimental part added (but hidden)
  * updates #59 - SimplexColonies

### Status 0.8.99.4

* Issues
  * closes #63 - Keridian Dynamics (KDVA) 0.8.99.4-prerelease `<#5 Please Read the Instructions>` edition
  * closes #64 - 0.8.99.4 Additional Tasks

---

## Version 0.8.99.3-prerelease - `<#4 Please Read the Instructions>` edition

* 19 Oct 2022
* Released for Kerbal Space Program 1.12.3

### Summary 0.8.99.3

* More parts updated
* Parts Catalog now has images
* Can now search for `kd` or `kdva` in the editor search bar to find all Keridian Dynamics parts.

### Changes

This is the next in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

Part of the complexity is the advanced design of this addon. The addon is designed to be as modular as possible, so that it can be used in a variety of ways.

### Parts 0.8.99.3

* Update
  * [KD-PAM.cfg] v1.1.0.0
  * [KD-PAMSmall.cfg] v1.1.0.0
  * [KD-FabricationContainer.cfg] v1.1.0.0
  * [KD-MobileVAB.cfg] v1.1.0.0
  * [KD-OrbitalHangar.cfg] v1.1.0.0

### Localization 0.8.99.3

* Lint
  * <en-us.cfg> v1.1.3.0
  * <zh-cn.cfg> v1.1.3.0
  * <zh-tw.cfg> v1.1.3.0
* updates #15 - Localization - Master
* updates #16 - English <us-en.cfg>
* updates #24 - Simplified Chinese (简体中文) <zh-cn.cfg>
* updates #31 - Taiwanese (国语) <zh-tw.cfg>

### Config 0.8.99.3

* Update
  * <KeridianDynamics.cfg> v1.0.1.0
  * :NEEDS replace 'DaMichel/Fuselage' with 'KeridianDynamics'

### Compatibility 0.8.99.3

* Add
  * <TETRIXTechTree.cfg> v1.0.0.0
    * placeholder (for now)
* updates #60 - [compatibility] TETRIX  tech tree
* updates #59 - SimplexColonies
  
### Status 0.8.99.3

* Issues
  * closes #55 - Keridian Dynamics (KDVA) 0.8.99.3-prerelease `<#4 Please Read the Instructions>`
  * closes #56 - 0.8.99.3 Verify Legal Mumbo Jumbo
  * closes #57 - 0.8.99.3 Update Documentation
  * closes #58 - 0.8.99.3 Update Social Media

---

## Version 0.8.99.2-prerelease - `<#3 Please Read the Instructions>` edition

* 27 Jul 2022
* Released for Kerbal Space Program 1.12.x

### Summary

* Taiwanese (国语) 太感谢了 (thank you) to [@ShadowSTAR616](https://github.com/ShadowSTARS616)
* Updated: RecyclerSmall and Recycler
* Mostly internal updates to localization.
* RecycleSite had a pass.
* Can now search for `kd` or `kdva` in the editor search bar to find all Keridian Dynamics parts.

### Changes

This is the second in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

Part of the complexity is the advanced design of this addon. The addon is designed to be as modular as possible, so that it can be used in a variety of ways.

### Parts 0.8.99.2

* Update
  * [KD-RecyclerSmall] v1.1.0.0
  * [KD-Recycler] v1.1.0.0
* Fix
  * [KD-RecyclerSmall]
  * remove duplicate localization (one localized, one not)
  * (thank you) to [@ShadowSTAR616](https://github.com/ShadowSTARS616)
  * closes #47 - [Bug 🐞]: KD-RecyclerSmall part not fully localized

### Localization

* Add Taiwanese (国语)
  * <zh-tw.cfg> v1.1.2.0
  * 太感谢了 (thank you) to [@ShadowSTAR616](https://github.com/ShadowSTARS616)
* Update
  * <en-us.cfg> v1.1.2.0
  * <zh-cn.cfg> v1.1.2.0
    * simplified
    * scraped KSP dictionary for settings
* Spelling
  * Strait --> straight
* Add new strings to the localization files
  * used for editior search (tags)
  * #KDVA-tags = KD KDVA
* closes #16 - English <us-en.cfg>
* closes #24 - Simplified Chinese (简体中文) <zh-cn.cfg>
* closes #31 - Taiwanese (国语) <zh-tw.cfg>
* updates #15 - Localization - Master
* updates #33 - Part Localization

### Compatibility

* Add
  * [KeridianDynamics.cfg] v1.0.0.0
  * adds cck-sc, cck-el, kd, kdva to tags
* Rename
  * Remove extra .cfg.cfg
  * <ExtraplanetaryLaunchpads.cfg.cfg> --> <ExtraplanetaryLaunchpads.cfg>
  
### Status

* Issues
  * closes #49 - Keridian Dynamics (KDVA) 0.8.99.2-prerelease `<#3 Please Read the Instructions>`
  * closes #50 - 0.8.99.2 Verify Legal Mumbo Jumbo
  * closes #51 - 0.8.99.2 Update Documentation
  * closes #52 - 0.8.99.2 Update Social Media

---

## Version 0.8.99.1-prerelease - `<#2 Please Read the Instructions>` edition

* 17 Jul 2022
* Released for Kerbal Space Program 1.12.x

### Summary

* All Cargo Tanks are now finished with the initial pass.
* RecycleSite had a pass.
* All thumbs should now be available.
* Can now search for 'kdva' in the editor search bar to find all Keridian Dynamics parts.

### Changes

This is the second in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

Part of the complexity is the advanced design of this addon. The addon is designed to be as modular as possible, so that it can be used in a variety of ways.

* Parts Updated in this Pass:
  * [KD-RecycleSite.cfg] v1.1.0.0
  * Cargo Tanks (all of them)
    * [KD-ST2001FS.cfg] v1.1.0.0
    * [KD-ST2002FS.cfg] v1.1.0.0
    * [KD-ST2501FS.cfg] v1.1.0.0
    * [KD-ST2502FS.cfg] v1.1.0.0
    * [KD-ST2503FS.cfg] v1.1.0.0
    * [KD-ST3751FS.cfg] v1.1.0.0
    * [KD-ST3752FS.cfg] v1.1.0.0
    * [KD-ST3753FS.cfg] v1.1.0.0
    * [KD-ST3001FS.cfg] v1.1.0.0
    * [KD-ST3002FS.cfg] v1.1.0.0
    * [KD-ST3251FS.cfg] v1.1.0.0
    * [KD-ST3252FS.cfg] v1.1.0.0
    * [KD-T3753FS.cfg] v1.1.0.0
    * [KD-T1251FS.cfg] v1.1.0.0
    * [KD-T1252FS.cfg] v1.1.0.0
    * [KD-T1253FS.cfg] v1.1.0.0
    * [KD-T2001FS.cfg] v1.1.0.0
    * [KD-T2501FS.cfg] v1.1.0.0
    * [KD-T2502FS.cfg] v1.1.0.0
    * [KD-T2503FS.cfg] v1.1.0.0
    * [KD-T3251FS.cfg] v1.1.0.0
    * [KD-T3751FS.cfg] v1.1.0.0
    * [KD-T3752FS.cfg] v1.1.0.0

### Localization

* Add Simplified Chinese (简体中文)
  * <zh-cn.cfg> v1.0.0.1
  * 太感谢了 (thank you) to [@ShadowSTAR616](https://github.com/ShadowSTARS616)
* Many minor updates to [en-us.cfg] v1.1.1.0
  * simplified the localization string names
  * scraped KSP dictionary for settings
* [DrillScience.cfg] v1.1.1.0
  * Add strings for drill science
    * [#KDVA-drill-name] = Dig Ore sample
    * [#KDVA-drill-coll] = Collect Ore sample
    * [#KDVA-drill-rset] = Reset Drill
* Spelling
  * Strait --> straight
* tags
  * add 'kdva' to all tags
* updates #15 - Localization - Master
* closes #16 - English <us-en.cfg>
* closes #24 - Simplified Chinese (简体中文) <zh-cn.cfg>
* closes #33 - Part Localization

### Compatibility

* Add header
  * [CommunityTechTree.cfg] v1.1.0.0
  * [ConnectedLivingSpace.cfg] v1.1.0.0
  * [DrillScience.cfg]
  * [EL-Launchpad.cfg]
* Rename
  * [EL-Launchpad.cfg] --> [ExtraplanetaryLaunchpads.cfg.cfg] v1.1.0.0

### Status

* Issues
  * closes #43 - 0.8.99.1 Update Social Media
  * closes #42 - 0.8.99.1 Update Documentation
  * closes #41 - 0.8.99.1 Verify Legal Mumbo Jumbo
  * closes #40 - Keridian Dynamics (KDVA) 0.8.99.1-prerelease `<#2 Please Read the Instructions>`

---

## Version 0.8.99.0-prerelease - `<Please Read the Instructions #1>` edition

* 04 Jul 2022
* Released for Kerbal Space Program 1.12.x

### Changes

This is the first in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update, I can update the addon in a more manageable way.

* Parts Updated in this Pass:
  * [KDChemicalReactor]
  * [KD3DPrinter-250.cfg]
  * [KD-SledgeHammer.cfg]
  * Cargo Tanks
    * [KD-ST1001FS]
    * [KD-ST1251FS]
    * [KD-ST1252FS]
    * [KD-ST1253FS]

### minor changes

* [SimpleConstruction.cfg] v v1.1.0.0
  * add header
  * remove `!` hitchhiker
    * was
      * @MODULE[ModuleResourceConverter],*:HAS[!#ConverterName[Ore-->Metal+LFO]]
    * now
      * @MODULE[ModuleResourceConverter],*:HAS[#ConverterName[Ore-->Metal+LFO]]
* [KD-OSERocketParts.cfg] v1.1.0.0
  * PatchManager\PluginData
  * add header
  * was
    * @OSE_DefaultRecipe:AFTER[Workshop]
  * now
    * @OSE_DefaultRecipe:NEEDS[Workshop]:AFTER[Workshop]
  * was
    * @PART[*]:HAS[OSE_PartRecipe:HAS[#MaterialKits[1]]]:AFTER[Workshop]
  * now
    * @PART[*]:HAS[@OSE_PartRecipe:HAS[#MaterialKits[1]]]:NEEDS[Workshop]:AFTER[Workshop]+

### Compatibility

* [KerbalInventorySystem.cfg] v1.1.0.0
  * rename from [KIS.cfg]
  * remove Sledgehammer patches
  * no longer necessary

### Parts

* Replace
  * [KD-3DPrinter.cfg] NEW
  * [KD-3D-Printer.cfg] Original
  * new part name is: KD-3DPrinter-250
* [ghostparts.cfg]
  * which will go away with version 0.9.0.0-release
    * KD-3D-Printer
    * KD-3DPrinter
* Update/Lint/Asset pass
  * [KD-ST1001FS] v1.1.0.0
  * [KD-ST1251FS] v1.1.0.0
  * [KD-ST1252FS] v1.1.0.0
  * [KD-ST1253FS] v1.1.0.0
  * [KD-SledgeHammer.cfg] v1.1.0.0
    * move KIS module into part
    * add :NEEDS[KIS] to make part only show if KIS is installed
  * closes #6 - [Bug 🐞]: Also survey stakes are upside down when placed,
  * closes #5 - [Bug 🐞]: Cannot equip sledgehammer or stakes
  
### Graphical changes

* Resize Flags
  * from 256x160 to 512x320
* HeroLogo
  * update

### IVA/Spaces

* renamed from `_` to `-` in IVA names
* started splitting out the individual IVA's into separate files

### Localization

* Add
  * [readme.md] v2.1.2.0
  * [quickstart.md] v1.0.1.1
* Many minor updates to [en-us.cfg]
  * including renaming from us-en.cfg to en-us.cfg
  * simplified the localization string names
  * scraped KSP dictionary for settings
* [KS-FAVA.cfg]
  * [@ShadowSTAR616](https://github.com/ShadowSTARS616) reports
  * part now localized
  * closes #37 - [Bug 🐞]: KS-FAVA part not localized
* [KDChemicalReactor]
  * add "2.5m" to title
* [KD3DPrinter-250.cfg]
  * add "2.5m" add "2.5m" to title
* updates #33 - Part Localization
* updates #16 - English <us-en.cfg>
* updates #15 - Localization - Master

### Status

* Issues
  * closes #10 - KeridianDynamics 0.8.99.0-prerelease `<Please Read the Instructions #1>` edition
  * closes #11 - 0.8.99.0-prerelease Verify Legal Mumbo Jumbo
  * closes #12 - 0.8.99.0-prerelease Update Documentation
  * closes #13 - 0.8.99.0-prerelease Social Media
  * closes #4 - friznit updates

---

## Version 0.8.9.1-prerelease - `<Brushing off the Construction Dust>`

* >>-- adopted for curation by @zer0Kerbal --<<
* moved changelog into separate file
* Changelog.md -> Kerbal Changelog Changelog.cfg
* updated Readme.md
* created Forum Thread
* updated SpaceDock
* renamed GitHub repository to NotSoSimpleConstruction
* updated CKAN/NetKAN
* modernization, polish, update pass on .cfg
* large .png -> .dds
* added .version file
* added license(s) file(s)
* merged in patches
* automated deploy/release process

* much lint was shaved
* misplaces spare right brace in Changelog.cfg
* Changelog.cfg:32 :: unexpected
* KD-ExtensionPad.cfg:224 :: unexpected
* KD-Keronica.cfg:164 :: unexpected
* KD-LaunchPad.cfg:132 :: unexpected
* KD-LaunchPadSide.cfg:138 :: unexpected
* KD-LaunchPadTop.cfg:138 :: unexpected
* KD-Pad.cfg:84 :: unexpected

---

## Version 0.8.9.1-prerelease - `<Vacuuming the Carpets>`

* initial update to 1.7.3
* updated KIS (thank you to Justin @Khalendros)

 ---

## Version 0.8.9(.0) - The No-Title-Pre-Release Update

* 2018.04.15
* Compatibility to EL 6.0
* Re-export all models (except Internals)
  * unity 2017.1.3p1
  * latest parttools
* B9PartSwitch support
* A Resource-Switcher (FS, IFS or B9PS) is now mandatory
* All Resource Converters are enabled by default (some require CRP)
* Patchmanager support
* Ore->Metal converters can be disabled
* MetalOre->Metal converters can be disabled
* ScrapMetal->Metal converters can be disabled
* Metal->RocketParts converters can be disabled
* Metal->MaterialKits converters can be disabled
* Metal+Ore->SpecializedParts converters can be disabled
* Dirt->RareMetals+ExoticMinerals converters can be disabled
* Old costs can be restored
* Station Tank Series can be disabled
* (Cargo) Tank Series can be disabled
* Station Tank Series can be crewed
* OSE Workshop default Resource can be switched from MaterialKits to RocketParts
* Integrated 534443s cost-rebalance (thanks a lot!)
* Reintegrated Station Tank Series
* Fixed unused switcher for Cargo Tanks
* StockDrill Patch only applies if no other MetalOre harvester is present already
* Added MetalOre Harvester to MiniDrill
* Reworked Spawn Markers
* Redo MetalOre converters (density change 0.0275->0.026)
* Removed very old hexagonal tanks used when FS and IFS are not installed (no replacement)
* Removed KD-OrbitalPad, KD-SidePad and KD-TopPad
* New Parts:
  * KD-Keronica
    * Rework of the old OrbitalPad
    * Advanced Probe Core with Launchpad.
  * KD-LaunchPad
    * 2 Variants 1.25, 2.5
    * Light-weight replacement for OrbitalPad
  * KD-LaunchPadSide
    * 2 Variants 1.25, 2.5
    * Light-weight replacement for SidePad
  * KD-LaunchPadTop
    * 2 Variants 1.25, 2.5
    * Light-weight replacement for TopPad
  * KD-ExtensionPad
  * 6 variants, 0.625-5.0 meters
  * Light-weight part to extend exisiting vessels (ELDisposablePad)
  * KD-FAVA (early prototype)
    * Fully Automated Vessel Assembler
    * generates productivity without the need for Kerbals

### Localization

* English

 ---

## Version 0.8.2(.0) - Recycling Everything

* 2017.01.21
* Moved parts to customisation: KD-STXXXXFS. New Adapters included.
* New part
  * KD-FurnaceSmall
  * KD-FabricationContainer
    * Metal --> Rocketparts
    * needs an engineer
  * KD-PAM
    * Planetary Assembly Management aka SurveyStation
    * has no IVA currently
  * KD-PAMSmall.
  * KD-RecyclerSmall
  * KD-RecycleSite
    * Needs KAS
  * KD-T125XFS (X=variant)
    * 1.25 m Storage Tanks
    * 3 sizes(1, 2, 4 m)).
  * KD-T2001FS
    * 1.25 to 2.5 m storage adapter
* Re-exported most of the models with improved shading and materials.
* Re-worked most of the animations. Except the tanks all parts use ModuleColorChange for glow animations (can be changed in cfg).
* Overhauled resource storage and mass for ALL tanks.
* Added
  * ScrapMetal setup
  * LFO setup (temporary, for balancing. Will be replaced in the future).
  * surface attach to some parts (Launchpads for example).
* Fixed Furnaces MetalOre extraction ratio. Now really 70% (was 100 before).
* Recycling produces ScrapMetal and small amounts of Metal.
* Added
  * ScrapMetal-->Metal converters
  * Furnaces
  * ChemicalReactor
* Changed SpecialistBonus
  * KD-Furnace
  * KD-3D-Printer
* ChemicalReactor can now extract RareMetals and ExoticMinerals from Dirt (if OSE Workshop is installed).
* Changed dependency for Metal,
  * Ore-->SpecializedParts converter to require UmbraSpaceIndustries.
* Changed SimpleConstruction support:
  * If SC is installed the following changes are applied:
    1. No MetalOre Harvester.
    2. No MetalOre-->Metal converters.
    3. Ore-->Metal converters give 70 times more Metal.
    4. Metal tanks storage-capacity is increased by factor 5 (ingame units, not mass!).
* Changed FS/IFS priority
  * If both are installed IFS module will be used.
* Added optional config to use RocketParts with OSE Workshop instead of MaterialKits, RareMetals & ExoticMinerals (KeridianDynamics-OSE-RP.cfg).

 ---

## Version 0.8.1(.0) - Balancing update one

* 2016-11-28
* New part
  * KD-ChemicalReactor
    * Ore --> Metal+LFO
  * KD-T250XFS (X=variant)
    * 2.5 m non-passable Storage Tanks
    * 3 sizes (1, 2, 3 m).
  * KD-T375XFS (X=variant)
    * 3.75 m non-passable Storage Tanks
    * 3 sizes (1, 3, 6 m).
  * KD-T3252FS
    * 3.75 m to 2.5 m non-passable Storage Tank adapter (2 m).
* Removed parts
  * KD-T125FS
  * KD-T250FS
* Increased
  * Furnace conversion speed
  * ~15 times faster, extr.-rate remains 1%-mass
* Added
  * MetalOre --> Metal converter to Furnace by default (~70%-mass extr.-rate).
  * MetalOre harvester to Stock drill (Big one only).
* Increased
  * 3D-Printer conversion speed
  * ~21 times faster, conv.-rate remains 100%-mass
* Reduced
  * 3D-Printer mass to 1.85 tons
* Compatibility patch
  * SimpleConstruction.
* Updated converter specialty
  * ExperienceEffect
    * 3D Printer and Furnace = ConverterSkill
    * ChemicalReactor = ScienceSkill
* Added
  * [bulkheadProfiles]
  * [tags]
  * ScienceExperiment
    * OreScience to Stock Drill
    * Big one only

 ---

## Version 0.8(.0.0) - Storage update

* 2016-07-06
* New part
  * KD-OrbitalHangar
    * Big Launchpad for orbital construction and other stuff.
  * KD-ST250XFS (X=variant)
    * 2.5 m crew-passable Storage Tanks
    * 3 sizes (1, 2, 3 m).
  * KD-ST375XFS (X=variant)
    * 3.75 m crew-passable Storage Tanks
    * 3 sizes (1, 3, 6 m).
  * KD-ST3252FS
    * 3.75 m to 2.5 m crew-passable Storage Tank adapter (2 m).
* Community Resource Pack now triggers storage configurations for MaterialKits,... (instead of OSE because CRP is bundled with OSE).
* Added
  * JSI Advanced Transparant Pods dependency
  * ConnectedLivingSpace support.
  * optional config that allows the 3D-Printer to make MaterialKits from Metal in customisation.
* KD-MobileVAB
  * Minor model tweaks
  * Airlock moved to the bottom
  * Fixed IVA light.
* LaunchSite
  * One arm glows in a darker blue now.
* Launchpads and MobileVAB have proper names for EL GUI.
* All parts
  * rebalanced in cost
  * cost to unlock
  * tech-node (Stock and CTT).
* Changed capacity for MaterialKits, RareMetals, ExoticMinerals and Monoprop. on old tanks.

 ---

## Version 0.7(.0.0) - Universal Assembly

* 2016-05-16
* New Parts
  * KD-MobileVAB
    * Acts primary as Survey Station
    * offers a high productivity factor for up to 12 Kerbals.
  * New part (previously experimental)
    * KD-LaunchSite (reworked)
      * Acts as Survey Stake.
    * KD-SledgeHammer
      * Needed to attach the LaunchSite to the ground.
  * All parts above need Kerbal Inventory System to work properly.
* Added support for OSE workshop.
* KD-3D-Printer can convert Ore to MaterialKits.
* KD-MobileVAB can be used as OSE workshop and OSE recycler.
* KD-T125FS and KD-T250FS have 2 additional setups
  * Materialkits
  * RareMetals/ExoticMinerals
* InterstellarFuelSwitch
  * is not a dependency anymore
  * still supported and highly recommended.
* Added support
  * Firespitter
    * FSmeshSwitch
    * FSfuelSwitch
* Added
  * MM-config
  * autodetects if Firespitter and/or InterstellarFuelSwitch is installed and applies the corresponding modules to the tanks. (If both are NOT installed, two tanks for RocketParts and two tanks for Metal are available)

 ---

## Version 0.6.1(.0) - PECUNIA PER KERBULUS

* 2016-05-01
* Reexported models
  * Unity 5
  * PartTools 1.1.
* New Company Motto
  * PECUNIA PER KERBULUS
  * Thanks to DaniDE for translation!
* Reworked Logo and Flags.
* Used "Icon_Hidden" tag
  * Thanks to Badsector for the hint!
* Added ExperimentalSection
  * needs KIS
* New experimental part
  * KD-Fundament
    * Thanks to colmo for the suggestion!
  * KD-LaunchSite
  * KD-SledgeHammer "Susie"

 ---

## Version 0.6(.0.0) - Recycling

* 2016-04-16
* Added Interstellar Fuel Switch dependency.
  * Tank names have changed, be careful with savegames!
* Reworked models
  * Colliders have not changed.
* Added Normal maps.
* Added Emissive maps.
* Added new animations.
* Reworked Furnace behavior
  * No more seperate heating needed.
* Furnace needs much less EC but produces more heat.
* New part
  * KD-Recycler
  * Roll-animation and ExRecycler need to be activated seperately
* Updated CTT-compatibility.

 ---

## Version 0.5(.0.0) - 2016 update

* 2016-02-27
* Reworked tanks. (Names have changed, so be carefull with savegames!)
* Changed RoverPads to TopPad and SidePad. (Names have changed, so be carefull with savegames!)
* New mesh-colliders for all parts (be carefull with savegames!).
* Toggleable Spawn Marker for all Pads added. A vessel from SPH will point in the direction of the arrowtip. VAB vessels will still point upwards.
* tanks now share the same texture
  * KD-OrbitalPad
  * KD-SidePad
  * KD-TopPad
  * all KD-OrbitalPad.dds
* Added thermal properties to KD-Pad and KD-OrbitalPad to prevent overheating-explosions during vessel-launch (might be exploitable ...).
* Added thermal curves to KD-Furnace and KD-3D-Printer.
* The Furnace needs to heat up before Metal can be extracted. CoreTemperature must at least reach 1800 K to start the extraction! Heating needs a lot of ElectricCharge. Once the extraction has started the heater can be turned off.
* The 3D-Printer needs 20 ElectricCharge instead of 10. It needs RoomTemperature to operate (300 K). Heat production is rather low.
* Some minor model and texture changes.
* Added 512x512 textures to Customisation.
* Added "KD-Example Craft.craft" to Customisation.
* Updated CTT-compatibility.

 ---

## Version 0.4(.0.0) - License update

* 2015-08-23
* License changed to CC-BY-SA 4.0 International
* New experimental parts
  * KD-RoverPad
  * KD-RoverPad2
* KD-Furnace
  * CoM -0.1 down
* KD-Pad
  * CoM -0.87 down
* KD-OrbitalPad
  * CoM -0.47 down
* Moved MM-patches for EL into one config. (Delete old versions before updating!)

 ---

## Version 0.3(.0.0) - Orbital Assembly

* 2015-08-10
* New part
  * KD-OrbitalPad
* KD-Pad fixes
  * Now transparent in Editor when not attached.
* Model and texture refined.
* Center of mass adjusted.
* KD-3D-Printer
  * Model and texture refined (a little).
* Added support for AVC.

 ---

## Version 0.2(.0.0) - Hotfix

* 2015-08-03
* Fixed MM-config for MetalOreFurnace and MetallicOreFurnace.
* Reconverted textures to DDS.

 ---

## Version 0.1(.0.0) - Initial Release

* 2015-07-27
* New part: KD-Furnace
* New part: KD-3D-Printer
* New part: KD-Pad
* New part: KD-TankHex1-Metal
* New part: KD-TankHex1-RocketParts
* New part: KD-TankHex2-Metal
* New part: KD-TankHex2-RocketParts

---
