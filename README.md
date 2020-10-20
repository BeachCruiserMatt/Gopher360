This version:

1. Slow down mouse move.
2. Upgrade to Visual Studio 2019




Download
======
https://github.com/BeachCruiserMatt/Gopher360/tree/master/Windows/Release


Compatible Controllers
======
### Xbox 360
* [Official Wired Xbox 360 Controller for Windows](https://www.amazon.com/Microsoft-Wired-Controller-Windows-Console/dp/B004QRKWLA/)
* [Official Wireless Xbox 360 Controller](https://www.amazon.com/Xbox-360-Wireless-Controller-Glossy-microsoft/dp/B003ZSP0WW/)
* [A compatible wireless adapter](https://www.amazon.com/Microsoft-Xbox-Wireless-Receiver-Windows/dp/B000HZFCT2/) is required to get a standard controller to connect to a Windows PC)

### Xbox One
* [Offical Xbox One Wireless Controller](https://www.amazon.com/Xbox-Wireless-Controller-Black-one/dp/B01LPZM7VI/)
* [A bluetooth adapter/antenna](https://www.amazon.com/Bluetooth-Wireless-Headphone-Controller-Keyboard/dp/B0774NZNGX/) is needed for XBone controller Bluetooth mode. Many laptops and tablets will *already* have this. Read the manual!
* [A wireless adapter](https://www.amazon.com/Microsoft-Xbox-Wireless-Adapter-Windows-one/dp/B00ZB7W4QU/) is needed if you want wireless mode.
* [A decently long MicroUSB cable](https://www.amazon.com/Charger-Durable-Charging-Smartphones-Motorola/dp/B06XZTK2JL/) will be needed for comfortable direct wired mode usage. This is the cheapest option if you already have the controller and no Bluetooth antenna!

### DualShock
DualShock controllers are great, but you need to emulate Xinput for Gopher to see and understand. Fortunately, Xinput emulation is a very popular thing, as there are just as many people with DualShock controllers as there are Xbox controllers.

### Third party
Third party controllers will most likely work as well.  


Table of contents
=================

  * [About](#about-gopher)
  * [Default Controls](#default-controls)
  * [Requirements](#requirements)
  * [DualShock Controllers](#using-dualshock-controllers)
  * [Re-binding Controls](#config-file-instructions)
  * [Building](#build-instructions)
  * [License](#license)



About Gopher
======

Gopher is a utility for couch-oriented PC users that wish to entirely control their PC from the couch with a controller. Gopher works by transforming Xbox (or PlayStation, if using DS3Tool) controller input into traditional keyboard and mouse input that many applications and games still completely rely on with no controller-based alternative input options. The analog sticks move the mouse, the buttons click - it's very simple. Gopher completely skips this requirement and brings controller compatibility to ALL your applications and MOST of your games. Games like Runescape will be just fine. It all depends on what amount of traditional input the game requires. Gopher is an excellent tool for PC gaming from the couch, as it's fully capable of web browsing, playing mouse-based games, controlling media players, and launching emulators. Don't stand up and waste calories, just download Gopher!

Gopher separates itself from the competition by being efficient, small, portable, free, and fully open. If you have something you'd like to see improved, added, or changed, please fill out the survey.



Requirements
======
Gopher needs C++ runtime. 

Download Instructions
======
Download the latest release here: https://github.com/BeachCruiserMatt/Gopher360/tree/master/Windows/Release


Default Controls
======
Gopher360 automatically generates a config file, which will contain documentation information on all input types and key bindings.

**A**: Left Mouse-Click.

**X**: Right Mouse-click.

**Y**: Hide terminal.

**B**: Enter.

**D-pad**: Arrow keys.

**Right Analog**: Scroll up/down.

**Right Analog Click**: F2.

**Left Analog**: Mouse.

**Left Analog Click**: Middle mouse click.

**Back**: Browser refresh

**Start**: Left Windows Key

**Start + Back**: Toggle. Useful for when you launch emulators or open Steam Big Picture mode. Press again to re-enable.

**Start + DPad Up**: Toggle gopher vibration setting.

**LBumper**: Browser previous

**RBumper**: Browser next

**LBumber + RBummper**: Cycle speed (x3)

**LTrigger**: Space

**RTrigger**: Backspace

Config file instructions
======
There is a configuration file (config.ini) that can be reconfigured for simple keybindings.

```diff
- IF YOU MESS SOMETHING UP, Gopher will automatically re-generate a config file.
```

You can set which controller buttons will activate the configuration events based on the official microsoft keys hexadecimal values.

Virtual Windows Keys:
https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731

XInput Controller Buttons:
https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_gamepad%28v=vs.85%29.aspx

More instruction in the configuration file.


```diff
+ If you make a config file you feel could benefit people with the same use scenario as you, feel free to make a pull request for it in the public configs directory.
```


Build Instructions
======
If you get missing windows.h error, you may need to (right click Solution -> Retarget solution).

License
======
Gopher is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.





