# PURSUIT MODE [STANDALONE]

<div align="center">
<img src="https://github.com/user-attachments/assets/39a30393-e5bc-4e7c-a5ac-bfac5c231d93" alt="thumb" width="700px" />
</div>

## DESCRIPTION

Transform your police pursuits with this sophisticated vehicle class management system. Designed for realism and performance, this script allows officers to dynamically adjust their vehicle's handling and performance characteristics on the fly.
Perfect for police roleplay servers looking to add depth to their pursuit mechanics. Give your officers the tools they need to adapt to any pursuit situation!

## FEATURES

### **Dynamic Class System**
- Multiple vehicle classes
- Instant class switching during pursuits
- Smooth transitions between performance levels
- Customizable class configurations

### **Advanced Handling Modifications**
- Precise handling adjustments per class
- Dynamic performance scaling
- Customizable handling parameters

### **Smart Tuning System**
- Automatic tuning adjustments per class
- Original modifications preservation
- Seamless transitions between states
- Customizable tuning presets

### **User-Friendly Interface**
- Clean, minimal UI design
- Draggable position customization
- Class status display
- Customizable notifications

### **Performance Optimized**
- Efficient resource usage
- Minimal performance impact
- Smooth class transitions
- Stable handling modifications

### **Highly Configurable**
- Easy-to-use configuration file
- Customizable key bindings
- Adjustable UI elements
- Flexible notification system

### Technical Features
- Full vehicle handling customization
- Comprehensive vehicle state tracking
- Persistent UI position saving

## GET NOW

* [DOWNLOAD](https://dking.tebex.io/package/6582380)

## HOW TO INSTALL

* [Download](https://portal.cfx.re/assets/granted-assets) script;
* Place it in the resources folder;
* Add 'ensure dking_pursuitmode' (without quotes) to server.cfg.

## HOW TO USE

### Definitions and configurations of classes, commands, binds, etc., all explained in the [config](https://github.com/user-attachments/assets/61d8cd55-ffbe-4c4d-9562-c5f42b4c8fdc) files.

## PREVIEW

* [YouTube](https://youtu.be/SDDCsqalixM)

## DEPENDENCIES

* [ox_lib](https://github.com/overextended/ox_lib) (Optional, used only for notifications)

## SUPPORT

### [Discord](https://discord.gg/Rw6vjcXspG)

## CHANGELOGS

<details>
  <summary><h2 style="display: inline;">Expand</h2></summary>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.1</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added export to get current class.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2</h3></summary>
    <details>
      <summary style="margin-left: 30px;"><h5 style="display: inline;">New Features</h5></summary>
      <summary style="margin-left: 40px;"><h5 style="display: inline;"><b>Livery System Integration</b></h5></summary>
      <ul style="margin-left: 40px;">
        <li>Added dynamic livery changes based on vehicle class;</li>
        <li>Vehicles now visually display their current performance class through liveries;</li>
        <li>Added support for both standard liveries and mod-based liveries (modType 48);</li>
        <li>Vehicle-specific livery overrides <b>available</b> in configuration.</li>
        (Livery is just an example, you can use any modkit.)
      </ul>
    </details>
    <details>
      <summary style="margin-left: 30px;"><h5 style="display: inline;">Improvements</h5></summary>
      <summary style="margin-left: 40px;"><h5 style="display: inline;"><b>Vehicle Name Recognition</b></h5></summary>
      <ul style="margin-left: 40px;">
        <li>Fixed issue where vehicles with special characters in names weren't being recognized;</li>
        <li>Improved vehicle name handling for better compatibility with custom vehicles;</li>
        <li>Added debug command to check vehicle names (<code>/checkvehicle</code>).</li>
      </ul>
    </details>
    <details>
      <summary style="margin-left: 30px;"><h5 style="display: inline;">Configuration Updates</h5></summary>
      <ul style="margin-left: 30px;">
        <li>Added <code>Config.LiveryClass</code> for class-based livery settings;</li>
        <li>Added <code>Config.VehicleLiveryOverrides</code> for vehicle-specific livery configurations;</li>
        <li>Added <code>Config.Pursuit.checkvehiclename</code> for debugging vehicle names.</li>
      </ul>
    </details>
    <details>
      <summary style="margin-left: 30px;"><h5 style="display: inline;">Bug Fixes</h5></summary>
      <ul style="margin-left: 30px;">
        <li>Fixed issue where vehicles with special characters in names weren't recognized by the system;</li>
        <li>Fixed handling application for certain vehicle types;</li>
        <li>Improved vehicle exit handling to properly restore original vehicle state.</li>
      </ul>
    </details>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.2</h3></summary>
    <details>
      <summary style="margin-left: 30px;"><h5 style="display: inline;">New Feature</h5></summary>
      <summary style="margin-left: 40px;"><h5 style="display: inline;"><b>Speed ​​check</b></h5></summary>
      <ul style="margin-left: 40px;">
        <li>Added <code>Config.Pursuit.Speed</code> option to limit the speed at which class switching will be allowed.</li>
      </ul>
    </details>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.3</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Fixed errors that occurred when ox_lib was missing.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.4</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added translation system;</li>
      <li>Reorganized command and notification configurations;</li>
      <li>Moved Config.HandlingPresets to a separate file.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.5</h3></summary>
    <ul style="margin-left: 20px;">
      <li><code>Config.Notifys</code> moved to a separate file;</li>
      <li>UI Improvements;</li>
      <li>Reworked the handling application logic and added new parameters:</li>
      <details>
        <summary>Parameters</summary>
        <ul>
          <li>fMass</li>
          <li>fDownforceModifier</li>
          <li>fDriveBiasFront</li>
          <li>fBrakeBiasFront</li>
          <li>fHandBrakeForce</li>
          <li>fCamberStiffnesss</li>
          <li>fTractionBiasFront</li>
          <li>fSuspensionForce</li>
          <li>fSuspensionCompDamp</li>
          <li>fSuspensionReboundDamp</li>
          <li>fSuspensionUpperLimit</li>
          <li>fSuspensionLowerLimit</li>
          <li>fSuspensionRaise</li>
          <li>fSuspensionBiasFront</li>
          <li>fAntiRollBarForce</li>
          <li>fAntiRollBarBiasFront</li>
          <li>fRollCentreHeightFront</li>
          <li>fRollCentreHeightRear</li>
          <li>strHandlingFlags</li>
          <li>fBackEndPopUpCarImpulseMult</li>
          <li>fBackEndPopUpBuildingImpulseMult</li>
          <li>fBackEndPopUpMaxDeltaSpeed</li>
          <li>strAdvancedFlags</li>
        </ul>
      </details>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.6</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Added option to show the current class of nearby vehicles (<code>Config.ViewClass</code> and <code>Config.Commands.viewClass</code>).</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.7</h3></summary>
    <ul style="margin-left: 20px;">
      <li>Improvements in class display;</li>
      <li>Improvements in class saving by vehicle;</li>
      <li>Added the possibility to decrease the class (<code>switchClassDown</code>).</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.8</h3></summary>
    <ul style="margin-left: 20px;">
      <li><code>Config.Pursuit.Speed.max</code> is now defined by class.</li>
    </ul>
  </details>

  <details>
    <summary style="margin-left: 20px;"><h3 style="display: inline;">1.2.9</h3></summary>
    <ul style="margin-left: 20px;">
      <li><code>Config.Commands</code> moved to a separate file;</li>
      <li>The UI has been completely redone and improved;</li>
      <li>More optimizations.</li>
    </ul>
  </details>
</details>

# COPYRIGHT

## BY [DKING](https://github.com/Dking07) 2026 ©