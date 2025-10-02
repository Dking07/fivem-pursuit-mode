# PURSUIT MODE [STANDALONE]

<div align="center">
<img src="https://github.com/Dking07/fivem-pursuit-mode/blob/main/THUMB.png" width="700px" />
</div>

## DESCRIPTION

### Transform your police pursuits with this sophisticated vehicle class management system. Designed for realism and performance, this script allows officers to dynamically adjust their vehicle's handling and performance characteristics on the fly.
### Perfect for police roleplay servers looking to add depth to their pursuit mechanics. Give your officers the tools they need to adapt to any pursuit situation!

## FEATURES

### 🚓 **Dynamic Class System**
- Multiple vehicle classes
- Instant class switching during pursuits
- Smooth transitions between performance levels
- Customizable class configurations

### 🛠️ **Advanced Handling Modifications**
- Precise handling adjustments per class
- Dynamic performance scaling
- Customizable handling parameters

### ⚙️ **Smart Tuning System**
- Automatic tuning adjustments per class
- Original modifications preservation
- Seamless transitions between states
- Customizable tuning presets

### 🎮 **User-Friendly Interface**
- Clean, minimal UI design
- Draggable position customization
- Class status display
- Customizable notifications

### ⚡ **Performance Optimized**
- Efficient resource usage
- Minimal performance impact
- Smooth class transitions
- Stable handling modifications

### 🔧 **Highly Configurable**
- Easy-to-use configuration file
- Customizable key bindings
- Adjustable UI elements
- Flexible notification system

### Technical Features
- Full vehicle handling customization
- Comprehensive vehicle state tracking
- Persistent UI position saving

## GET NOW

* [DOWNLOAD](https://dking.tebex.io/package/6582383)

## HOW TO INSTALL

* [Download](https://keymaster.fivem.net/asset-grants) script;
* Place it in the resources folder;
* Add 'ensure dking_pursuitmode' (without quotes) to server.cfg.

## HOW TO USE

### Definitions and configurations of classes, commands, binds, etc., all explained in the config files.

* [Configs](https://github.com/Dking07/fivem-pursuit-mode/tree/main/config)

## PREVIEW

* [YouTube](https://youtu.be/SDDCsqalixM)

## DEPENDENCIES

* [ox_lib](https://github.com/overextended/ox_lib) (Optional, used only for notifications)

## SUPPORT

### [Discord](https://discord.gg/Rw6vjcXspG)

## CHANGELOGS

### 1.1

* Added export to get current class.

### 1.2

##### New Features
- ##### **Livery System Integration**
  - Added dynamic livery changes based on vehicle class
  - Vehicles now visually display their current performance class through liveries
  - Added support for both standard liveries and mod-based liveries (modType 48)
  - Vehicle-specific livery overrides **available** in configuration
  (Livery is just an example, you can use any modkit)

##### Improvements
- ##### **Vehicle Name Recognition**
  - Fixed issue where vehicles with special characters in names weren't being recognized
  - Improved vehicle name handling for better compatibility with custom vehicles
  - Added debug command to check vehicle names (`/checkvehicle`)

##### Configuration Updates
- Added `Config.LiveryClass` for class-based livery settings
- Added `Config.VehicleLiveryOverrides` for vehicle-specific livery configurations
- Added `Config.Pursuit.checkvehiclename` for debugging vehicle names

##### Bug Fixes
- Fixed issue where vehicles with special characters in names weren't recognized by the system
- Fixed handling application for certain vehicle types
- Improved vehicle exit handling to properly restore original vehicle state

### 1.2.2

##### New Feature
- ##### **Speed ​​check**
  - Added `Config.Pursuit.Speed` option to limit the speed at which class switching will be allowed.

### 1.2.3

  * Fixed errors that occurred when ox_lib was missing.

### 1.2.4

  * Added translation system;
  * Reorganized command and notification configurations;
  * Moved Config.HandlingPresets to a separate file.

### 1.2.5

  * Config.Notifys moved to a separate file;
  * Reworked the handling application logic and added new parameters:
    * fMass
    * fDriveBiasFront
    * fBrakeBiasFront
    * fHandBrakeForce
    * fCamberStiffnesss
    * fTractionBiasFront
    * fSuspensionForce
    * fSuspensionCompDamp
    * fSuspensionReboundDamp
    * fSuspensionUpperLimit
    * fSuspensionLowerLimit
    * fSuspensionRaise
    * fSuspensionBiasFront
    * fAntiRollBarForce
    * fAntiRollBarBiasFront
    * fRollCentreHeightFront
    * fRollCentreHeightRear
    * strHandlingFlags
    * fBackEndPopUpCarImpulseMult
    * fBackEndPopUpBuildingImpulseMult
    * fBackEndPopUpMaxDeltaSpeed
    * strAdvancedFlags
  * UI Improvements.

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2025 ©