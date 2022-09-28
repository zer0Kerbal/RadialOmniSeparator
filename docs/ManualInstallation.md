---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Radial Omni Separator (ROS)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Radial Omni Separator (ROS)

[Home](./index.md)

Hallowe'en themed parts pack for Kerbal Space Program. Jack-O'Lanterns not included.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `RadialOmniSeparator` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/RadialOmniSeparator`
* Extract the package's `RadialOmniSeparator/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/RadialOmniSeparator` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/RadialOmniSeparator`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/RadialOmniSeparator`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/RadialOmniSeparator`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [RadialOmniSeparator]
      + [Assets]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Flags]
        ...
      + [FX]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      + [Sounds]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * License.txt
        ManualInstallation.htm
      * readme.htm
      * RadialOmniSeparator.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none