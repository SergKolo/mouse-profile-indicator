If you like software in this repository, please consider making a donation to support the developer
[![paypalbutton](https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CB9L72S9LEF66)

# mouse-profile-indicator
Indicator for Ubuntu with Unity desktop, which allows saving mouse speed profiles

[![Sample Screenshot](http://i.imgur.com/GbZSJau.png)](http://i.imgur.com/GbZSJau.png)

### Overview

The purpose of this indicator is to allow  easy switching between user-defined mouse speeds. This is useful for :

* laptop users with wireless mouses ,working on different surfaces; 
* users who share same account with two or more users 
* users who alternate between multiple mouses that differ in sensitivity

### Usage
When current value of mouse speed does not equal to any of the saved profiles, the indicator label is set to "N/A". Under such condition, users can click "Store current" or middle-click on the indicator icon, and popup window asking user to name this new profile will appear. Note, that profile names and values should be unique, i.e. you cannot have two profiles named "Profile 1", and cannot have two profiles with value -0.5

Once profile is stored, the menu of the indicator will be re-build to include that profile. Clicking on the profile menuentry will activate that profile.

Effects of the profile switching can be tested via observing the scales in System Settings -> Mouse & Touchpad menu change as you click on your stored profile

The configuration for the indicator is stored in `~/.mouse_profile.json` file, where `~` is user's home directory.

### Side notes:

This indicator is related in its codebase and logic to another indicator I've created, [launcher-list-indicator](https://github.com/SergKolo/launcher-list-indicator), that allows storing and switching between multiple lists of launcher icons.

