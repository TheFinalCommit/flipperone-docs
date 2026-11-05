---
title: Controls
slug: general/tech-specs/controls
---

This page describes the controls of Flipper One — the buttons, touchpad, and D-pad used to navigate the interface, switch apps, and trigger device-level actions like power and recovery. Most buttons are adaptive and context-dependent: their current action is shown on the screen above the button.

![Flipper One controls](/files/pics/controls-explainer.png)

***

## Controls description

<table isTableHeaderOn="true" columnWidths="231,429">
  <tr>
    <td align="center">
      <p><strong>Control</strong></p>
    </td>
    <td align="left">
      <p><strong>Description</strong></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>PTT Button</strong></p>
      <p><img src="/files/icons/controls/ptt-button.svg" alt=""></p>
    </td>
    <td align="left">
      <p>Push-to-talk button to activate microphone in walkie-talkie mode, for voice control and more.</p>
      <p>This button may be used as an adaptive App-Defined Button. In this case, the current action is context-dependent and displayed on the screen.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>Touchpad</strong></p>
      <p><img src="/files/icons/controls/touchpad.svg" alt=""></p>
    </td>
    <td align="left">
      <p>Touchpad for on-screen keyboard and menu navigation, content scrolling. Support horizontal and vertical scroll.</p>
      <p>Most likely will be always duplicate D-pad navigation and will be used for quick move in long lists.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>ESC button</strong></p>
      <p><img src="/files/icons/controls/esc-button.svg" alt=""></p>
    </td>
    <td align="left">
      <p>Adaptive App-Defined Button. Current action is context dependent and displayed on screen above the button.</p>
      <p><strong>Recommended UI actions:</strong> cancel, stop, pause, breake, abort, back, discard.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>Edit button</strong></p>
      <p><img src="/files/icons/controls/edit-button.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Adaptive App-Defined Button. Current action is context dependent and displayed on screen above the button.</p>
      <p><strong>Recommended UI actions:</strong> more, edit, extra, config, rename.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>Power button</strong></p>
      <p><img src="/files/icons/controls/power-button.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p><code>Long press for 1 second:</code> Device power mode control: turn ON/OFF, reboot.</p>
      <p><code>Short press on Linux level:</code> Action is context dependent and displayed on screen above the button.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>View button</strong></p>
      <p><img src="/files/icons/controls/view-button.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Adaptive App-Defined Button. Current action is context dependent and displayed on screen above the button.</p>
      <p><strong>Recommended UI actions:</strong> help, search, view.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>Run button</strong></p>
      <p><img src="/files/icons/controls/run-button.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Adaptive App-Defined Button. Current action is context dependent and displayed on screen above the button.</p>
      <p><strong>Recommended UI actions:</strong> start, run, enter, save.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>App Switcher</strong></p>
      <p><img src="/files/icons/controls/app-switcher.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p><strong>Works only on Linux level:</strong></p>
      <p>ALT+TAB like button, list all opened apps windows.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>Back button</strong></p>
      <p><img src="/files/icons/controls/back-button.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Back, exit in menus and apps.</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>D-pad</strong></p>
      <p><img src="/files/icons/controls/dpad.svg" alt=""></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Main navigation D-pad with 5-buttons: UP, DOWN, LEFT, RIGHT and OK in center.</p>
    </td>
  </tr>
</table>

***

## Buttons shortcuts&#x20;

Some buttons and their combinations have hardware-defined behavior that does not depend on software. These combinations can hardware-reset, power off, or put the device into full recovery mode.

<table isTableHeaderOn="true" columnWidths="231,429">
  <tr>
    <td align="center">
      <p><strong>Action</strong></p>
    </td>
    <td align="left">
      <p><strong>Description</strong></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>Hardware Restart</strong></p>
    </td>
    <td align="left">
      <p><code>Back&nbsp;+&nbsp;Left</code> — hold for 3 seconds. This will send an uninterceptable hardware reset to the CPU and MCU chips.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>Power ON</strong></p>
    </td>
    <td align="left">
      <p>Hold <code>Power</code> button for 1 sec to turn ON device from Power OFF.</p>
      <p>First turn ON from transport mode is the same Power ON. Connecting USB to charging port also Power ON the device.</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><strong>Full Power Cycle 
      (Hardware Reboot)</strong></p>
    </td>
    <td align="left">
      <p>Hold <code>Power</code> button for 10 seconds to completely power cycle device. It will quickly turn off and on battery.</p>
      <p>What will happen when USB charger connected?</p>
      <p>‎</p>
    </td>
  </tr>
  <tr>
    <td align="center" colSpan="1" rowSpan="1">
      <p><strong>Firmware Recovery</strong></p>
    </td>
    <td align="left" colSpan="1" rowSpan="1">
      <p>Hold <code>ESC&nbsp;+&nbsp;Run&nbsp;+&nbsp;Back&nbsp;+&nbsp;Left</code> for 3 seconds.</p>
      <p>Think of this as a normal Hardware Restart made by <code>Back&nbsp;+&nbsp;Left</code>, but Firmware Recovery is triggered if <code>ESC&nbsp;+&nbsp;Run</code> are pressed while the MCU is starting. This puts the RP2350 MCU into the UF2 bootloader (<a href="https://docs.flipper.net/one/mcu-firmware/firmware-update">BOOTSEL mode</a>).</p>
      <p>If Firmware Recovery is successful, you will see a USB Mass Storage Device named <code>FlipOneMCU</code>.</p>
      <p>‎</p>
    </td>
  </tr>
</table>

