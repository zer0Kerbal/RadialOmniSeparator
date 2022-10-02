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

To install, place the `nli2work` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/nli2work/RadialOmniSeparator`
* Extract the package's `nli2work` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/nli2work` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/nli2work/RadialOmniSeparator`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/nli2work/RadialOmniSeparator`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/nli2work/RadialOmniSeparator`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [nli2work]
      + [RadialOmniSeparator]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
          ManualInstallation.htm
        * readme.htm
        * RadialOmniSeparator.version
          ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
